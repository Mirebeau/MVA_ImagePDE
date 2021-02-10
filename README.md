# MVA_ImagePDE

Notes de cours et travaux pratiques pour le cours "EDPs numériques pour le traitement d'image"

## Liens

Salle de cours : https://bbb2.imo.universite-paris-saclay.fr/b/jea-fhp-zcj

Ce dépôt : https://github.com/Mirebeau/MVA_ImagePDE

## Notes de cours

Ces notes seront étendues au fur et a mesure du cours.
Document : [`MVA.pdf`](MVA.pdf)

## Travaux pratiques en langage Python

Note: 
 - Dans certains notebooks, pour exécuter sur CPU (et non GPU), il faut commenter la cellule de la section 0.1.
 - Les notebooks nécessitent la librarie agd, qui s'installe via !pip install agd (notamment sur Google Colab).

<!---
	Générer un lien Colab
	https://colab.research.google.com/notebook#fileId= (insérer identifiant) &offline=true&sandboxMode=true
--->

TP1 : Techniques de différentiation automatique
* Enoncés  
 - Fichiers : Dense_Exo, Sparse_Exo: voir `TP1/`.
 - Liens Colab :
  [Dense_Exo](https://colab.research.google.com/notebook#fileId=1tqdZvmZFA_1lg6gj6q0U5l-Ez7qIeWo8&offline=true&sandboxMode=true),
  [Sparse_Exo](https://colab.research.google.com/notebook#fileId=1ohjV4fXNs5NcrUS3XeFtIHOGYBx8GCMM&offline=true&sandboxMode=true),

* Solutions :
 - Fichiers : Dense, Sparse : voir TP1/
 - Liens Colab :
  [Dense](https://colab.research.google.com/notebook#fileId=1cF26zZz8LAbrL7gbbWEtyYdBtlTSBwVL&offline=true&sandboxMode=true),
  [Sparse](https://colab.research.google.com/notebook#fileId=1tifdb1jjVJP9TCUpVWYghiXgOEhbAaHI&offline=true&sandboxMode=true)

TP2 : Diffusion anisotrope

* Enoncés 
 - Fichers : 
 [Algorithme de Selling](https://drive.google.com/file/d/1adPejCBWfUmBnn8A_3XaW0W_PuAZI9MU/view?usp=sharing),
 [Diffusion anisotrope](https://drive.google.com/file/d/1CY3v6gyhRVgPbsuzwfgt-kGfXzEMZWWL/view?usp=sharing)
 - Liens Colab : 
 [Algorithme de Selling](https://colab.research.google.com/notebook#fileId=1adPejCBWfUmBnn8A_3XaW0W_PuAZI9MU&offline=true&sandboxMode=true),
 [Diffusion anisotrope](https://colab.research.google.com/notebook#fileId=1CY3v6gyhRVgPbsuzwfgt-kGfXzEMZWWL&offline=true&sandboxMode=true)

* Solutions
 - Fichiers 
 [Algorithme de Selling](https://drive.google.com/open?id=1dMHXDYJoQBI_EtvQTcR15pbJaiP03S0p),
 [Diffusion anisotrope](https://drive.google.com/open?id=1u6_XthpxwycWYIusJoP26x37n2Fvbevh),

 - Liens Colab
 [Algorithme de Selling](https://colab.research.google.com/notebook#fileId=1dMHXDYJoQBI_EtvQTcR15pbJaiP03S0p&offline=true&sandboxMode=true),
 [Diffusion anisotrope](https://colab.research.google.com/notebook#fileId=1u6_XthpxwycWYIusJoP26x37n2Fvbevh&offline=true&sandboxMode=true)

TP3 : chaleur et géodésiques

* Enoncés
 - Fichiers
 Diffusion anisotrope - à terminer - dans TP3/,
 Formule de Varadhan : voir TP3/,
 [Chaleur et ondes 1D](https://drive.google.com/file/d/10s3kP6pAzZTf0DspG3M5j-Pfmu5M6wKc/view?usp=sharing)
 - Liens Colab : 
 ,
 [Chaleur et ondes 1D](https://colab.research.google.com/notebook#fileId=10s3kP6pAzZTf0DspG3M5j-Pfmu5M6wKc&offline=true&sandboxMode=true)

* Solutions
 - Fichiers 
  [Diffusion anisotrope](https://drive.google.com/open?id=1u6_XthpxwycWYIusJoP26x37n2Fvbevh),
  Formule de Varadhan : voir TP3/Solutions
  [Chaleur et ondes 1D](https://drive.google.com/open?id=12fuUVP1BHfJhWOupAL4wLADSf9VYPyjM)
 - Liens Colab
 [Diffusion anisotrope](https://colab.research.google.com/notebook#fileId=1u6_XthpxwycWYIusJoP26x37n2Fvbevh&offline=true&sandboxMode=true),
 [Chaleur et ondes 1D](https://colab.research.google.com/notebook#fileId=12fuUVP1BHfJhWOupAL4wLADSf9VYPyjM&offline=true&sandboxMode=true)

TP4 : transport optimal entropique

* Enoncés
- Fichiers
 Formule de Varadhan - à terminer - dans TP4/
 [transport entropique](https://dl.dropbox.com/s/xiwt6y76vkf0ypr/Sinkhorn_Exo.ipynb?dl=0)

* Solutions
 [transport entropique](https://dl.dropbox.com/s/a150x3ib3zd3gx4/Sinkhorn.ipynb?dl=0)

TP5 : Résolution numérique de l'équation eikonale
* Enoncés
[Eikonal GPU](https://colab.research.google.com/notebook#fileId=182TnSY0Glaabm-LLuoooScIVQNIcuT4n&offline=true&sandboxMode=true)

* Solutions
[Eikonal GPU](https://colab.research.google.com/notebook#fileId=1Y7mJ3SdD3GRm0QCtV1bRgHShzBzeLk-j&offline=true&sandboxMode=true)

## Environnement

Les travaux pratiques peuvent être exécutés soit:
- en ligne, en utilisant Google Colab. Utiliser les liens ci-dessus, et exécuter `!pip install agd` dans une cellule.
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
