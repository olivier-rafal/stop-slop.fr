# stop-slop.fr

Un skill pour enlever les tics d'écriture LLM de la prose française.

Inspiré de [stop-slop](https://github.com/hardikpandya/stop-slop) de Hardik Pandya, calibré sur le français et la voix éditoriale [WEnvision](https://wenvision.com).

## Ce que ça fait

L'écriture LLM a des patterns. Openers génériques, contrastes binaires, fausse agentivité, aphorismes creux, jargon conseil empilé. Ce skill apprend à Claude à les détecter et les supprimer.

## Structure

```
stop-slop.fr/
├── SKILL.md                    # Instructions core
└── references/
    ├── phrases-fr.md           # Phrases à supprimer
    ├── structures-fr.md        # Patterns structurels à éviter
    └── examples-fr.md          # Paires avant/après
```

## Installation

**Installation globale** (disponible dans tous vos projets) :

```bash
git clone https://github.com/olivier-rafal/stop-slop.fr.git ~/.claude/skills/stop-slop-fr
```

**Installation par projet** (dans le repo de votre choix) :

```bash
git clone https://github.com/olivier-rafal/stop-slop.fr.git .claude/skills/stop-slop-fr
```

Puis commiter `.claude/skills/` pour que vos collègues en bénéficient au prochain `git pull`.

> Si votre `.gitignore` exclut `.claude/`, ajouter une exception :
> ```
> .claude/
> !.claude/skills/
> ```

## Utilisation

**Claude Code :** ajouter ce dossier comme skill.

**Claude Projects :** uploader `SKILL.md` et les fichiers `references/` dans la base de connaissance du projet.

**API / system prompt :** inclure `SKILL.md` dans votre system prompt. Les fichiers `references/` se chargent à la demande.

## Ce que ça détecte

**Phrases bannies** — openers génériques, throat-clearing, jargon conseil, adverbes vides, qualificatifs sans preuve, meta-commentary sur l'entreprise. Voir `references/phrases-fr.md`.

**Patterns structurels** — contrastes binaires, structure en N piliers annoncée à voix haute, passif et nominalisations, tours impersonnels, fausse agentivité, conclusions-aphorismes. Voir `references/structures-fr.md`.

**Règles phrase à phrase** — Sentence Case, pas de majuscules non justifiées, pas de CTA dans le corps de l'article, acteurs nommés, ouverture sur un fait précis.

## Scoring

| Dimension | Question |
|-----------|----------|
| Ancrage | Faits précis ou abstractions ? |
| Clarté | Acteurs nommés ou fausse agentivité ? |
| Voix | Active ou passive/nominalisée ? |
| Confiance | Respecte l'intelligence du lecteur ? |
| Authenticité | Sonne humain ou généré ? |

En dessous de 35/50 : réviser avant publication.

## Licence

MIT
