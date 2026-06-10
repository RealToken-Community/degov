# Documentation DeGov (français)

Ce dossier documente le **sous-module DeGov** situé à la racine du dépôt `vendor/degov` (application web Next.js, indexer, configuration YAML). Il ne couvre pas l’outillage devcontainer ni le template du dépôt parent.

## Contenu

| Document | Description |
|----------|-------------|
| [Référence `degov.yml`](reference-degov-yml.md) | Description détaillée de chaque section du fichier de configuration, avec consommateurs dans le code (web / indexer), valeurs attendues et pièges connus. |

## Convention

La documentation est **vivante** : elle doit être mise à jour lorsque le schéma YAML ou son utilisation dans `packages/web` ou `packages/indexer` évolue. Les chemins de fichiers sont relatifs au répertoire `vendor/degov/`.

## Fichier de configuration canonique

Le fichier d’exemple et de référence pour une instance DAO est [`../../degov.yml`](../../degov.yml) (à la racine du sous-module DeGov).
