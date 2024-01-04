# SolubilityAssayPaper2023
This is a repository with all data and code used for the article: "A label-free high-throughput protein solubility assay and its application to Aβ40" DOI: [https://doi.org/10.1016/j.bpc.2023.107165](https://doi.org/10.1016/j.bpc.2023.107165) 

## How to run the code
1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://docs.anaconda.com/anaconda/install/index.html)
2. Clone this project to your computer (e.g. by downloading as zip and extracting or cloning via git) and enter the resulting directory.
3. Create and enter a new conda environment with the required python packages by: 
```
conda env create -f environment.yml # to run with tested versions of all packages, use "environment_package-versions.yml" instead.
conda activate solubility-paper-Lindberg_etal-2023
```
4. Start a jupyter lab instance by typing: 
```
jupyter lab
```
5. Now you can open the notebooks Main.ipynb and SI.ipynb and run through the cells to process and plot all the data
