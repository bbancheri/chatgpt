# chatgpt

Espace de travail dédié aux documents, schémas, scripts et projets réalisés avec ChatGPT.

## Organisation

| Emplacement | Contenu |
|---|---|
| [documents/](documents/) | Études, spécifications, procédures et documents communs à plusieurs projets. |
| [schemas/](schemas/) | Schémas d’architecture, fichiers draw.io et autres représentations communes. |
| [scripts/](scripts/) | Scripts et automatisations réutilisables. |
| [projets/](projets/) | Un sous-dossier par projet, avec ses objectifs et ses livrables propres. |

Chaque dossier contient un README qui précise son utilisation.

## Classer un nouveau travail

1. Identifier le sujet et le résultat attendu.
2. Placer un livrable transversal dans `documents/`, `schemas/` ou `scripts/`.
3. Pour un ensemble de travaux liés, créer un sous-dossier dans `projets/` avec un README présentant l’objectif, l’état d’avancement et les liens vers les livrables.
4. Référencer les fichiers communs par des liens pour éviter de maintenir plusieurs copies.

## Travailler avec les branches

La branche `main` rassemble les versions validées.

1. Créer une branche `chatgpt/<sujet>` à partir de `main` pour chaque travail, par exemple `chatgpt/organisation-espace`.
2. Réaliser les modifications correspondant à la demande et vérifier les fichiers concernés.
3. Ouvrir une pull request vers `main`, en expliquant le besoin, les changements et les vérifications effectuées.
4. Relire et valider la pull request avant son intégration dans `main`.

## Conventions

- Rédiger les explications en français et conserver les noms techniques utiles.
- Utiliser des noms de fichiers et de dossiers explicites, sans espaces ni accents, avec des tirets entre les mots.
- Conserver les sources modifiables des documents et des schémas, avec leurs exports lorsqu’ils sont utiles.
- Indiquer les sources, les hypothèses et les limites qui permettent de comprendre un livrable.
- Utiliser des liens relatifs pour naviguer entre les fichiers du dépôt.
