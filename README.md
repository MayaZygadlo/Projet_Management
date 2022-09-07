# Transmembrane Protein Project

Here is the code to find the most probable localisation of the membrane from a Protein Data Bank file.

To run this code you will need:
* DSSP

## Setup your environment

Clone the repository:

```bash
git clone https://github.com/CNOV0/Projet_Management.git
```

Move to the new directory:

```bash
cd Projet_Management
```

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

Install [mamba](https://github.com/mamba-org/mamba):

```bash
conda install mamba -n base -c conda-forge
```

Create the "Projet_TMP" conda environment:
```
mamba env create -f src/Projet_TMP.yaml
```
or
```
conda env create -f src/Projet_TMP.yaml
```

Load the "Projet_TMP" conda environment:
```
conda activate Projet_TMP
```

Note: you can also update the conda environment with:

```bash
mamba env update -f Projet_TMP.yaml
```

To deactivate an active environment, use

```
conda deactivate
```
