---
name: stop-slop-fr
description: Supprimer les tics d'écriture LLM de la prose française. Utiliser lors de la rédaction, révision ou génération de contenu WEnvision pour éliminer les patterns prévisibles des modèles de langage.
metadata:
  trigger: Rédiger du contenu, réviser une prose, corriger une sortie Gemini/GPT, préparer un article wenvision.com
  author: WEnvision / Olivier Rafal
---

# Stop Slop FR

Éliminer les patterns d'écriture LLM de la prose française. Calibré sur la voix WEnvision.

## Règles core

1. **Ouvre sur un fait, pas une généralité.** Date, chiffre, événement, nom propre. Jamais "Dans un monde où…", "En 2026, les organisations…", "Force est de constater…". Voir [references/phrases-fr.md](references/phrases-fr.md).

2. **Nomme les acteurs.** Les gens font des choses. Pas "l'IA permet de", pas "des efforts sont déployés", pas "le harnais offre". Qui ? Quand ? Combien ? Si personne ne peut être nommé, utiliser "vous" pour mettre le lecteur dans la scène.

3. **Voix active.** Sujet humain + verbe d'action. Bannir le passif et les nominalisations. "L'équipe a réduit les incidents" bat "une réduction des incidents a été observée". Voir [references/structures-fr.md](references/structures-fr.md).

4. **Zéro contraste binaire.** Pas de "Ce n'est pas X, c'est Y", "X ne ralentit pas, il accélère", "Certains croient X. C'est tout l'inverse." Dire Y directement. Supprimer la négation.

5. **Spécificité contre vague.** Pas de "bénéfices significatifs", "sécurité de niveau industriel", "partenaire de haute précision". Nommer le bénéfice précis, le standard exact, l'action réelle.

6. **Ne pas annoncer la structure.** Pas de "repose sur trois dimensions critiques", "s'articule autour de quatre axes". La structure parle d'elle-même via les titres.

7. **CTA uniquement en bas de page.** L'expertise WEnvision ne s'intègre pas dans le corps du texte. Un seul bloc CTA structuré en bas, jamais "Chez WEnvision, nous croyons que…" dans les paragraphes.

8. **Sentence Case strict.** Seule la première lettre du titre en majuscule. Mots protégés : GenAI, WEnvision, LLM, SaaS, API, MCP, RAG, RSSI, DSI. Pas de pluriel anglais sur les sigles français (KPI ≠ KPIs).

9. **Supprimer les qualificatifs vides.** "crucial", "incontournable", "révolutionnaire", "robuste", "percutant" → les faits démontrent, ils n'annoncent pas.

10. **Varier le rythme.** Les phrases courtes viennent d'un fait percutant ou d'une citation réelle — pas d'un effet stylistique. Pas de fragmentation staccato artificielle.

## Vérifications rapides

Avant de livrer un texte :

- L'ouverture cite-t-elle une date, un chiffre ou un nom propre ? Sinon, réécrire.
- Y a-t-il un "Ce n'est pas X, c'est Y" ? Supprimer la négation, garder Y.
- Un sujet inanimé fait-il une action humaine ("l'outil propose", "le dispositif permet") ? Trouver la personne, la nommer.
- Y a-t-il un "il convient de", "il est à noter que", "on peut constater" ? Trouver le sujet, le nommer.
- Une phrase annonce-t-elle sa propre importance ("C'est le point crucial", "C'est ici qu'intervient") ? Couper l'annonce, aller au fait.
- Y a-t-il un "En conclusion" ou un aphorisme en fin d'article ? Remplacer par un fait ou une action.
- "Chez WEnvision, nous…" apparaît-il dans le corps ? Le déplacer dans le CTA de bas de page.
- Des majuscules non justifiées ("Intelligence Artificielle", "Harnais Technique") ? Corriger.
- Des adverbes en -ment ("véritablement", "fondamentalement", "clairement") ? Supprimer ou reformuler.
- Trois paragraphes suivent-ils le même schéma intro → liste → conclusion ? Casser le pattern.

## Scoring

Noter de 1 à 10 sur chaque dimension :

| Dimension | Question |
|-----------|----------|
| Ancrage | Faits précis ou abstractions ? |
| Clarté | Acteurs nommés ou fausse agentivité ? |
| Voix | Active ou passive/nominalisée ? |
| Confiance | Respecte l'intelligence du lecteur ? |
| Authenticité | Sonne humain ou généré ? |

En dessous de 35/50 : réviser avant publication.

## Exemples

Voir [references/examples-fr.md](references/examples-fr.md) pour des paires avant/après sur du contenu WEnvision réel.
