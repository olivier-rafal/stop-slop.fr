# Structures à éviter

## Contrastes binaires

Le pattern le plus répandu dans la prose LLM française. Nier X pour affirmer Y. Dire Y directement — la négation n'apporte rien.

| Pattern | Problème |
|---------|---------|
| "Ce n'est pas X, c'est Y" | Négation inutile. Dire Y. |
| "X n'est pas une bride, c'est un levier" | Métaphore + contraste = double couche de vide |
| "Certains voient X comme Y. C'est tout l'inverse." | Setup/révélation fabriqué |
| "On ne déploie pas X dans la nature. On déploie X dans…" | Même phrase en négatif puis en positif |
| "Pas X. Y." / "Non pas X, mais Y." | Fragmentation + contraste |
| "X n'est pas un frein, c'est un moteur" | Cliché de la transformation digitale |
| "La question n'est pas X. C'est Y." | Redirection rhétorique |
| "Il ne s'agit pas de X, mais de Y" | Idem |
| "X ne ralentit pas, il accélère" | Idem |
| "X n'est pas une dépense, c'est un investissement" | Usé jusqu'à la corde |

**À la place :** Énoncer Y directement. Supprimer la négation.

---

## La structure en N piliers / N axes / N dimensions

Le LLM adore structurer par listes numérotées avec annonce de la liste. La structure doit découler du contenu, pas être annoncée avant.

| Pattern | Problème |
|---------|---------|
| "repose sur trois dimensions critiques" | Annonce la liste au lieu de la livrer |
| "s'articule autour de quatre axes stratégiques" | Idem |
| "cinq piliers fondamentaux" | La liste va se justifier elle-même |
| "Les X étapes pour…" en titre d'article | Clickbait structurel |
| "Voici les points clés à retenir" en conclusion | Meta-commentary |

**À la place :** Utiliser des titres H2 qui posent la question ou le constat. La structure émerge de la lecture.

---

## Voix passive et nominalisations

Le français LLM évite les acteurs. Il nominalise les verbes et met les actions au passif. Trouver la personne, la nommer.

| Pattern | Correction |
|---------|------------|
| "des efforts sont déployés" | Qui déploie ? L'équipe X a déployé… |
| "une décision a été prise" | Qui a décidé ? Le DSI a décidé… |
| "des résultats ont été obtenus" | Qui a obtenu ? L'équipe a réduit… |
| "il a été décidé de" | Qui a décidé ? |
| "il est prévu de" | Qui prévoit ? Quand ? |
| "la mise en œuvre de la transformation de…" | Transformer (verbe) |
| "l'accompagnement des équipes dans l'adoption de…" | Former les équipes à utiliser… |
| "la valorisation des données" | Exploiter les données pour [objectif précis] |
| "le renforcement des compétences" | Former, recruter, développer |
| "la montée en puissance de l'IA" | Les déploiements d'IA ont doublé en 18 mois |

---

## Tours impersonnels

Ces constructions cachent systématiquement l'acteur. Trouver le sujet, le nommer.

| Pattern | Correction |
|---------|------------|
| "il convient de souligner que" | [Sujet] souligne que |
| "il s'agit de" | C'est / Ce sont |
| "il est à noter que" | Supprimer, noter directement |
| "on peut constater que" | Qui constate ? Les chiffres montrent que |
| "il apparaît que" | Les données indiquent que |
| "il faut noter que" | Supprimer |
| "il est indispensable de" | Nommer qui a besoin de quoi |
| "on ne saurait trop recommander de" | Supprimer le tour, recommander directement |

---

## Fausse agentivité

Donner à des objets inanimés des verbes d'action humaine. L'IA ne "propose" pas. Un outil ne "permet" pas tout seul. Une organisation ne "s'adapte" pas d'elle-même — des personnes décident et agissent.

| Pattern | Problème |
|---------|---------|
| "l'IA propose, l'humain dispose" | L'IA ne propose rien. Un développeur a défini une interface. |
| "l'outil permet de réduire les coûts" | L'outil ne fait rien seul. Qui l'utilise ? Comment ? |
| "le harnais offre une sécurité" | Le harnais est un concept. Qui l'implémente ? |
| "la donnée dit que" | La donnée ne dit rien. Qui l'analyse ? |
| "le marché récompense" | Les acheteurs paient pour quelque chose. |
| "la culture évolue" | Des personnes changent de comportement. |
| "l'organisation s'adapte" | Qui a changé quoi ? |
| "la transformation s'accélère" | Qui accélère quoi ? En combien de temps ? |

**À la place :** Nommer la personne ou l'équipe. Si personne ne peut être nommé, utiliser "vous" pour mettre le lecteur dans la scène.

---

## Questions rhétoriques auto-réponses

Le LLM pose une question pour l'occuper lui-même immédiatement après.

| Pattern | Problème |
|---------|---------|
| "Pourquoi est-ce important ? Parce que…" | La question ne sert à rien |
| "Qu'est-ce que cela signifie ? Cela signifie que…" | Idem |
| "Comment y parvenir ? En…" | Idem |
| "Qu'est-ce qu'un harnais ? C'est…" | Redéfinition de l'évident |

**À la place :** Les titres H2 posent la vraie question du lecteur. Le paragraphe y répond. Pas besoin de répéter la question dans le corps.

---

## Relatives et subordonnées empilées

Une phrase qui contient plus de deux "qui", "que", "dont", "lequel" consécutifs est à découper.

**Avant :**
> "un dispositif stratégique, technique et éthique conçu pour transformer une IA imprévisible en un levier de croissance fiable qui nécessite une structure qui encadre les sorties qui sont produites par le modèle"

**Après :**
> "Un guardrail filtre les sorties du modèle. Sans lui, l'IA produit des réponses hors cadre ou toxiques."

---

## Séquence annonce → liste → conclusion

Le schéma complet du LLM français :

1. Paragraph de contexte généraliste
2. "Voici les X points essentiels" / "Trois dimensions critiques"
3. Liste numérotée avec sous-titres en gras
4. "En conclusion / En somme, il est essentiel de…"

Ce schéma signal un article généré. Le briser par :
- Ouverture sur un fait ou anecdote concrète
- Questions H2 qui reformulent ce que le lecteur se pose vraiment
- Conclusion sur un fait, une tension ouverte ou une action — pas sur une synthèse molle

---

## Conclusions-aphorismes

Terminer sur une formule qui sonne profond mais ne dit rien.

| Pattern | Problème |
|---------|---------|
| "L'IA de demain sera harnachée ou ne sera pas" | Paraphrase de Malraux. Vide. |
| "Construire un harnais, c'est s'offrir le luxe de la sérénité technique" | Abstraction habillée |
| "L'avenir appartient à ceux qui…" | Cliché |
| "Le futur sera [X] ou ne sera pas" | Même structure |
| "X n'est plus une option, c'est une nécessité" | Usé |

**À la place :** Terminer sur un fait, un chiffre, une tension non résolue, ou une question qui ouvre vers l'article suivant. Le lecteur n'a pas besoin qu'on lui dise ce qu'il vient de lire.

---

## Starters de phrases à restructurer

| Pattern | Correction |
|---------|------------|
| "C'est ici que…" | Trouver le sujet, le mettre en tête |
| "C'est pourquoi…" | Trouver l'acteur |
| "C'est dans ce contexte que…" | Couper, aller au fait |
| "C'est ce que…" | Reformuler avec le sujet réel |
| "Ainsi, …" (en début de paragraphe) | Couper |
| "Par ailleurs, …" (filler) | Couper ou réécrire |
| "En effet, …" (souvent redondant) | Couper dans la plupart des cas |
| "Dès lors, …" | Souvent vide, couper |
