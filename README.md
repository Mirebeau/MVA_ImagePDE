# MVA_ImagePDE

Notes de cours et travaux pratiques pour le cours "EDPs numériques pour le traitement d'image"

## Liens

Salle de cours : https://bbb2.imo.universite-paris-saclay.fr/b/jea-fhp-zcj

Ce dépôt : https://github.com/Mirebeau/MVA_ImagePDE

## Notes de cours

Ces notes seront étendues au fur et a mesure du cours.
Document : [`MVA.pdf`](MVA.pdf)

## Travaux pratiques en langage Python

TP1 : Techniques de différentiation automatique
* Enoncés  
 - Fichiers : Dense_Exo, Sparse_Exo: voir `TP1/`.
  Bonus : [Chaleur 1D](https://drive.google.com/file/d/10s3kP6pAzZTf0DspG3M5j-Pfmu5M6wKc/view?usp=sharing)
 - Liens Colab :
  [Dense_Exo](https://colab.research.google.com/notebook#fileId=1tqdZvmZFA_1lg6gj6q0U5l-Ez7qIeWo8&offline=true&sandboxMode=true),
  [Sparse_Exo](https://colab.research.google.com/notebook#fileId=1ohjV4fXNs5NcrUS3XeFtIHOGYBx8GCMM&offline=true&sandboxMode=true),
  Bonus : [Chaleur 1D](https://colab.research.google.com/notebook#fileId=10s3kP6pAzZTf0DspG3M5j-Pfmu5M6wKc&offline=true&sandboxMode=true)

* Solutions :
 - Fichiers : Dense, Sparse : voir TP1/
 - Liens Colab :
  [Dense](https://colab.research.google.com/notebook#fileId=1cF26zZz8LAbrL7gbbWEtyYdBtlTSBwVL&offline=true&sandboxMode=true)
  [Sparse](https://colab.research.google.com/notebook#fileId=1tifdb1jjVJP9TCUpVWYghiXgOEhbAaHI&offline=true&sandboxMode=true)
  [Chaleur 1D](https://colab.research.google.com/notebook#fileId=12fuUVP1BHfJhWOupAL4wLADSf9VYPyjM&offline=true&sandboxMode=true)

## Environnement

Les travaux pratiques peuvent être exécutés soit:
- en ligne, en utilisant Google Colab (utiliser les liens ci-dessus)
- hors ligne, en utilisant des notebooks jupyter

### Installation pour l'utilisation hors ligne

Etapes préliminaires
- installer miniconda ou anaconda, en suivant les [instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
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
