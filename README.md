![LOGO](https://github.com/DeepWave-Kaust/Project-Template/blob/main/asset/logo.png)

This repo contains materials for the course ErSE328 Advanced Seismic Inversion course taught by Professor Tariq Alkhalifah at King Abdullah University of Science(KAUST).


# Project structure
This repository is organized as follows:

* :open_file_folder: **package**: python library containing routines for ....;
* :open_file_folder: **asset**: folder containing logo;
* :open_file_folder: **data**: folder containing data 
* :open_file_folder: **notebooks**: set of jupyter notebooks reproducing the experiments in the paper (see below for more details);
* :open_file_folder: **scripts**: set of python scripts used to run multiple experiments ...
  
# Getting started

Throughout the computational part of the course, we will mainly be utilizing the Deepwave Python library which you can access from their [repository]((https://github.com/ar4/deepwave?tab=readme-ov-file)). To get yourself started, you can directly learn the Deepwave fundamentals from their [documentations](https://ausargeo.com/deepwave/)

To install the environment, run the following command:
```
sh install_env.sh
```
It will take some time, but if, in the end, you see the word `Done!` on your terminal, you are ready to go. 

Remember to always activate the environment by typing:
```
conda activate erse328asi
```
## Notebooks
The following notebooks are provided:

- :orange_book: ``X1.ipynb``: notebook performing ...;
- :orange_book: ``X2.ipynb``: notebook performing ...


## Getting started :space_invader: :robot:
To ensure reproducibility of the results, we suggest using the `environment.yml` file when creating an environment.

Simply run:
```
./install_env.sh
```
It will take some time, if at the end you see the word `Done!` on your terminal you are ready to go. 

Remember to always activate the environment by typing:
```
conda activate my_env
```

**Disclaimer:** All experiments have been carried on a Intel(R) Xeon(R) CPU @ 2.10GHz equipped with a single NVIDIA GEForce RTX 3090 GPU. Different environment 
configurations may be required for different combinations of workstation and GPU.

## Cite us 
DWXXX - Author1 et al. (2022) Report title.

