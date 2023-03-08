# MVA_ImagePDE

Notes de cours et travaux pratiques pour le cours "EDPs numériques pour le traitement d'image"

- Salle de cours : 1Q7.
- Horaire : le mercredi matin de 9h30 à 12h30.
- Dates : 11, 18 et 25 janvier, 1er, 8 et 15 février, 1er mars. (Pas de cours le 22 février.)

Liens :  [Planning du M2 MVA](https://www.master-mva.com/). Ce dépôt : [https://github.com/Mirebeau/MVA_ImagePDE](https://github.com/Mirebeau/MVA_ImagePDE).


# Examen

[Sujet écrit](https://dl.dropbox.com/s/785ngwp7z253cxn/ExamMVA_Shared.pdf),  [Sujet numérique](https://dl.dropbox.com/s/73yicgke3qjoq3y/TVflow_Exo.ipynb)


<!---
Générer un lien Colab
https://colab.research.google.com/notebook#fileId= (insérer identifiant) &offline=true&sandboxMode=true

Sinon, simplement mettre le lien drive, l'exexution via Colab est proposée automatiquement.

alt+m pour ouvrir MarkdownLivePreview sous SublimeText 
--->

## Notes de cours

Les notes seront étendues au fur et a mesure du cours.
Document : [`MVA.pdf`](MVA.pdf)

## Devoir maison

Les devoirs maison sont facultatifs, et comptent dans la note finale seulement si favorable.

- Devoir maison sur le thème des opérateurs proximaux.
[Partie théorique](https://dl.dropbox.com/s/w0gjlq2yzmj23f8/DM_MVA_Shared.pdf)
[Partie numérique](https://dl.dropbox.com/s/9ln7wtufxlzn7zx/MVA_2023_DM_Lasso_Exo.ipynb)
[Corrigé](https://www.dropbox.com/s/ui2gnc679n4yeat/DM_MVA_Corrige_Shared.pdf?dl=1)
- Devoir maison sur le thème de l'équation eikonale.
[Partie théorique](https://dl.dropbox.com/s/y3c523rcggyuq0x/DM2_MVA_Shared.pdf?dl=0)
[Partie numérique](https://dl.dropbox.com/s/e34pvk3l4cbrj3b/MVA_2022_DM2_Exo.ipynb?dl=0)


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


TP2 : Algorithme de Selling

Finir la différentiation automatique creuse, voir TP1.

* Enoncés
 - Fichers :
 [Algorithme de Selling](https://drive.google.com/file/d/1adPejCBWfUmBnn8A_3XaW0W_PuAZI9MU/view?usp=sharing)
 - Liens Colab :
 [Algorithme de Selling](https://colab.research.google.com/notebook#fileId=1adPejCBWfUmBnn8A_3XaW0W_PuAZI9MU&offline=true&sandboxMode=true)

* Solutions
 - Fichiers
 [Algorithme de Selling](https://drive.google.com/open?id=1dMHXDYJoQBI_EtvQTcR15pbJaiP03S0p)
 - Liens Colab
 [Algorithme de Selling](https://colab.research.google.com/notebook#fileId=1dMHXDYJoQBI_EtvQTcR15pbJaiP03S0p&offline=true&sandboxMode=true)


TP3 : Diffusion anisotrope
* Enoncés
 - Fichiers :
 [Diffusion anisotrope](https://drive.google.com/file/d/1CY3v6gyhRVgPbsuzwfgt-kGfXzEMZWWL/view?usp=sharing)
 - Liens Colab
 [Diffusion anisotrope](https://colab.research.google.com/notebook#fileId=1CY3v6gyhRVgPbsuzwfgt-kGfXzEMZWWL&offline=true&sandboxMode=true)

* Solutions
 - Fichiers
  [Diffusion anisotrope](https://drive.google.com/open?id=1u6_XthpxwycWYIusJoP26x37n2Fvbevh)
 - Liens Colab
  [Diffusion anisotrope](https://colab.research.google.com/notebook#fileId=1u6_XthpxwycWYIusJoP26x37n2Fvbevh&offline=true&sandboxMode=true)

TP4 : Fin de la diffusion anisotrope

TP5 : Formule de Varadhan

* [Formule de Varadhan, énoncé](https://drive.google.com/file/d/1-00l_6sysNFuUNWuvTvGkQYsVObJ9Jzz/view?usp=sharing)
* [Formule de Varadhan, solution](https://drive.google.com/file/d/1-9kTVi4rRhDaaFdUwn0R3PJi3fTfIuZn/view?usp=sharing)

TP6 : Résolution numérique de l'équation eikonale
* Enoncé
[Eikonal GPU](https://colab.research.google.com/notebook#fileId=182TnSY0Glaabm-LLuoooScIVQNIcuT4n&offline=true&sandboxMode=true).
* Solution
[Eikonal GPU](https://colab.research.google.com/notebook#fileId=1Y7mJ3SdD3GRm0QCtV1bRgHShzBzeLk-j&offline=true&sandboxMode=true),


TP7 : Applications de l'équation eikonale
* Enoncés [Tubular structure segmentation](https://www.dropbox.com/s/xs2xmywbyi7rct7/Tubular_Exo.ipynb?dl=0),
[Curvature penalization](https://www.dropbox.com/s/mkvnw4735ux65qt/DeviationHorizontality_Exo.ipynb?dl=0).
* Solutions [Tubular structure segmentation](https://www.dropbox.com/s/dtzc3q2vjazyocc/Tubular.ipynb?dl=0),
[Curvature penalization](https://www.dropbox.com/s/xt7stg05oqcnwk4/DeviationHorizontality.ipynb?dl=0).

* Enoncés, version Colab.
[Tubular structure segmentation](https://colab.research.google.com/notebook#fileId=1pLHYt0UocFeHbjOp5SkS7NvB6XT2ALgx&offline=true&sandboxMode=true),
[Curvature penalization](https://colab.research.google.com/notebook#fileId=1m1362Cskq8PVUbOZqMiUcYgez9IZHXqG&offline=true&sandboxMode=true).

* Solutions, version Colab.
[Tubular structure segmentation](https://colab.research.google.com/notebook#fileId=1AMLRDrNQVXLnOdsracx4ZSwPR7bgi3J9&offline=true&sandboxMode=true),
[Curvature penalization](https://colab.research.google.com/notebook#fileId=1x309yEmht-G8sy9dxJN2LGeOE4INdnmW&offline=true&sandboxMode=true).


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
