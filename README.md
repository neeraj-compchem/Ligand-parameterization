# Ligand parameterization
This is a data and code repository for the following manuscript:<br>
"Development and Parametrization of <i>κ</i><sup>2</sup>-N,O-Oxazolines Preligands for Enantioselective Cobaltaelectro-catalyzed C–H Activations".


Last updated on July 10, 2024

## Overview
All files should be located in a single directory. If necessary, use the environment file for relevant programs; the input files (Excel) and code (as Jupyter Notebooks) needed to reproduce this study are briefly summarized here:

- small-molecule-partitioning.yml: Environment file for code used in this study
- QikProp_UMAP_input.xlsx: Excel file containing the small molecule QikProp descriptors for constructing chemical space and conducting clustering analysis 
- QikProp_modeling_input.xlsx: Excel file containing the small molecule QikProp descriptors for statistical modeling
- UMAP_clustering.ipynb: Code for uniform manifold and approximation (UMAP) dimensionality reduction and chemical space with associated clustering analysis
- modeling.ipynb: Code for all statistical models used in this study

# Packages requirements
The following packages were used with their mentioned versions.
```
python = 3.10.12
numpy = 1.25.2  
pandas = 2.0.3 
matplotlib = 3.7.1
morfeus = 0.5.5 
scipy = 1.11.4 
seaborn = 0.13.1 
sklearn = 1.2.2  
```

## How to cite
The code provided here is released under the MIT license. Commercial use, modification, and private use are all permitted. Please use the following citation to acknowledge this workflow:

The manuscript is under submission. The final reference will be updated here.

## Contact details
Email: neerajkumar.pandit@uni-goettingen.de; Lutz.Ackermann@chemie.uni-goettingen.de
