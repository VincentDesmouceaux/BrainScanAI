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
## v0.3.0 — Preprocessing et extraction des features

- Contrôle technique complet des 1 506 images.
- Mise en place du preprocessing associé à ResNet-50.
- Chargement des poids `IMAGENET1K_V2`.
- Gel de l'ensemble des paramètres du modèle.
- Extraction des embeddings `layer3` et `avgpool`.
- Sauvegarde des features en NumPy et Parquet.
- Sauvegarde des métadonnées et de la configuration expérimentale.
- Vérification de l'absence de valeurs NaN, infinies ou de vecteurs nuls.