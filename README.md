# MVA_ImagePDE

Notes de cours et travaux pratiques pour le cours "EDPs numériques pour le traitement d'image"

## Salle de cours 

https://bbb2.imo.universite-paris-saclay.fr/b/jea-fhp-zcj

## Notes de cours

Ces notes seront étendues au fur et a mesure du cours.
Document : [`MVA.pdf`](https://dl.dropbox.com/s/8yykzip9y69fwkk/MVA.pdf)

## Travaux pratiques en langage Python

TP1 : Techniques de différentiation automatique

## Environnement

Les travaux pratiques peuvent être exécutés soit:
- en ligne, en utilisant Google Colab (utiliser les liens ci-dessus)
- hors ligne, en utilisant des notebooks jupyter 

### Installation pour l'utilisation hors ligne

Etapes préliminaires
- installer miniconda ou anaconda, en suivant les instructions [instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
- creer un environnement *conda* dédié, par la commande du terminal
```
conda env create -f MVA_ImagePDE.yaml
```

A chaque TP, pour lancer les notebooks
```
cd MVA_ImagePDE
conda activate MVA_ImagePDE
jupyter notebook
```
