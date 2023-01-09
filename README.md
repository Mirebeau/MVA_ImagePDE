# MVA_ImagePDE

Notes de cours et travaux pratiques pour le cours "EDPs numériques pour le traitement d'image"

- Salle de cours : 1Q7.
- Horaire : le mercredi matin de 9h30 à 12h30.
- Dates : 11, 18 et 25 janvier, 1er, 8 et 15 février, 1er mars. (Pas de cours le 22 février.)

Liens :  [Planning du M2 MVA](https://www.master-mva.com/). Ce dépôt : [https://github.com/Mirebeau/MVA_ImagePDE](https://github.com/Mirebeau/MVA_ImagePDE).



<!---
Générer un lien Colab
https://colab.research.google.com/notebook#fileId= (insérer identifiant) &offline=true&sandboxMode=true

alt+m pour ouvrir MarkdownLivePreview sous SublimeText 
--->

## Notes de cours

Les notes seront étendues au fur et a mesure du cours.
Document : [`MVA.pdf`](MVA.pdf)

## Travaux pratiques en langage Python

Notes:

* Dans certains notebooks, pour exécuter sur CPU (et non GPU), il faut commenter la cellule de la section 0.1.
* Les notebooks nécessitent la librarie agd, qui s'installe via la commande `!pip install agd` (notamment sur Google Colab).

TP1 : Techniques de différentiation automatique

* Enoncés  
 - Fichiers : Dense-Exo, Sparse-Exo: voir `TP1/`.
 - Liens Colab :
  [Dense-Exo](https://colab.research.google.com/notebook#fileId=1tqdZvmZFA_1lg6gj6q0U5l-Ez7qIeWo8&offline=true&sandboxMode=true),
  [Sparse-Exo](https://colab.research.google.com/notebook#fileId=1ohjV4fXNs5NcrUS3XeFtIHOGYBx8GCMM&offline=true&sandboxMode=true),

* Solutions :
 - Fichiers : Dense, Sparse : voir TP1/
 - Liens Colab :
  [Dense](https://colab.research.google.com/notebook#fileId=1cF26zZz8LAbrL7gbbWEtyYdBtlTSBwVL&offline=true&sandboxMode=true),
  [Sparse](https://colab.research.google.com/notebook#fileId=1tifdb1jjVJP9TCUpVWYghiXgOEhbAaHI&offline=true&sandboxMode=true)

## Environnement

Les travaux pratiques peuvent être exécutés soit:

- en ligne, en utilisant Google Colab. Utiliser les liens ci-dessus, et exécuter `!pip install agd` dans une cellule.
- hors ligne, en utilisant des notebooks jupyter

### Installation pour l'utilisation hors ligne

Etapes préliminaires:

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
