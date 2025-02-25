![LOGO](logo_v2.png)

This repo contains materials for the course ErSE328 Advanced Seismic Inversion course taught by Professor Tariq Alkhalifah at King Abdullah University of Science(KAUST).


# Project structure
This repository is organized as follows:

* :open_file_folder: **package**: **Ignore**
* :open_file_folder: **asset**: **Ignore**
* :open_file_folder: **data**: folder containing data for the assignments
* :open_file_folder: **notebooks**: set of Jupyter Notebook-based assignments
* :open_file_folder: **scripts**: **Ignore**
  
# Getting started

Throughout the computational part of the course, we will mainly be utilizing the Deepwave Python library which you can access from their [repository](https://github.com/ar4/deepwave?tab=readme-ov-file). To get yourself started, you can directly learn the Deepwave fundamentals from their [documentations](https://ausargeo.com/deepwave/).

To successfully install the required environment, I highly recommend using a Linux system and ensuring your machine has a GPU. (Ibex would be a great choice)

**Step 1.1** Install Anaconda (if not already installed)

you can find the Linux version of Anaconda in [Anaconda](https://repo.anaconda.com/archive/). Then you can install a suitable Anaconda package by running (for example I use "https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh" )

```
wget https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh
```
**Step 1.2**: Run the installer script
```
chmod +x Anaconda3-2024.10-1-Linux-x86_64.sh
```
```
sh Anaconda3-2024.10-1-Linux-x86_64.sh
```
**Step 1.3**: Initialize Anaconda 
```
source ~/.bashrc
```
After installing the anaconda package, typing 
```
conda -V
```
to testify whether you have installed Anaconda successfully

**Step 2.1**: To install the Deepwave environment, run the following command:
```
sh install_env.sh
```
It will take some time, but if, in the end, you see the word Done! on your terminal, you are ready to go.

**Step 2.2**: Remember to always activate the environment by typing:
```
conda activate erse328asi
```
## Notebooks
The following notebooks are provided:

- :orange_book: ``notebooks/01_marmousi/notebook.ipynb``: First assignment(Deadline: March 6th)
- :orange_book: ``X2.ipynb``: TODO





