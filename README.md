# Predicting Protein Function by Characterizing the Interlocking Ligands

This project uses Machine Learning in order to classify enzymes according to the ligands that are bound to them.


## Prerequisites

In order to run this project, you will need:

- Anaconda 3 (or the smaller [Miniconda 3](https://conda.io/miniconda.html))
- RDKit (follow the instructions [here](http://www.rdkit.org/docs/Install.html))

After creating an RDKit environment, install the following packages:
`scikit-learn, scipy, matplotlib, imbalanced-learn`
by running:
```
conda install scikit-learn
conda install -c anaconda scipy
conda install -c conda-forge matplotlib
conda install -c conda-forge imbalanced-learn
```

Finally, open the Jupyter Notebook:
```
jupyter notebook
```


## Usage

This project consists of 8 notebooks. All of them are independent from one another and can be run in the Jupyter Notebook environment.

There are html versions of the notebooks in the html folder for better readability.


## Data

The database (CSV file) can be downloaded from the Ligand section of the [RCSB Protein Data Bank](http://www.rcsb.org/pdb/search/smart.do?smartSearchSubtype_0=NoLigandQuery&haveLigands_0=yes&target=Ligand).

The enzyme classes can be found in the [Enzyme Classification Browser](https://www.rcsb.org/pdb/browse/jbrowse.do?t=3&useMenu=no).
