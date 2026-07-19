# BrainScanAI

Projet de Computer Vision consacré à l'exploration d'un jeu de données
d'images cérébrales partiellement étiquetées.

## Contexte

CurelyticsIA souhaite étudier la possibilité d'automatiser la détection
de tumeurs cérébrales à partir d'images médicales.

Le dataset contient :

- des images annotées comme normales ;
- des images annotées comme cancéreuses ;
- un ensemble majoritaire d'images sans label.

## Objectifs

1. Explorer la structure et la qualité des images.
2. Extraire des caractéristiques avec un modèle pré-entraîné.
3. Tester plusieurs méthodes de clustering.
4. Mettre en œuvre une approche semi-supervisée.
5. Évaluer les modèles avec des métriques adaptées au contexte médical.
6. Étudier les conditions nécessaires au passage à l'échelle.

## Dataset

Le dataset contient :

- 100 images annotées ;
- 1 406 images sans label ;
- 1 506 images au total.

Les images annotées sont réparties dans les classes :

- `normal` ;
- `cancer`.

## Technologies

- Python 3.12
- UV
- PyTorch
- torchvision
- NumPy
- pandas
- Pillow
- matplotlib
- Jupyter

## Installation

```bash
uv sync