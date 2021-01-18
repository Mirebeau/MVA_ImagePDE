# MVA_ImagePDE
Course notes, and practical works for the "Numerical PDEs for image processing" course

## Course notes (French)

The course notes will be expanded as the course proceeds.

File : [`MVA.pdf`](https://dl.dropbox.com/s/8yykzip9y69fwkk/MVA.pdf)

## Practical works

Practical works will be added as the cours proceeds.

TP1 : Automatic differentiation techniques

## Environnement

The practical works can be executed either:
- online using Google Colab (see above links, required for GPU)
- offline using a dedicated *conda* environment

In the offline case, please
- install miniconda or anaconda, following the [instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
- create a dedicated *conda* environment, by typing in a terminal
```
conda env create -f MVA_ImagePDE.yaml
```

Then to run the practical works notebooks
```
cd MVA_ImagePDE
conda activate MVA_ImagePDE
jupyter notebook
```
