# Workflow Git du projet BrainScanAI

## Branches

- `main` : versions validées et stables.
- `develop` : développement courant.

## Format des commits

Chaque commit contient :

1. un titre court ;
2. une explication de la modification ;
3. la raison de la modification ;
4. les vérifications effectuées.

Exemple :

```text
feat(exploration): inventorier les images du dataset

Ajoute le comptage des images annotées et non annotées ainsi que
l'analyse de leur répartition.

Cette étape permet de vérifier le volume réel du dataset avant le
préprocessing.

Vérification : le notebook s'exécute sans erreur.