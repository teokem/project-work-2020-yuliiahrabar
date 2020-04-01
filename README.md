# Study of symmetric and asymmetric fission of Copernicium-284

## Running the Jupyter-Notebook

For _COMPUTE course_ project please check **GEANT4_FissionFragments.ipynb** notebook.

It is possible to run the notebook on your local computer as follows:

1. Install [miniconda3](https://conda.io/miniconda.html) alternatively the full [anaconda3](https://www.anaconda.com/download) environment on your laptop (the latter is **much** larger).
2. 2. Download ZIP folder from [repository link](https://github.com/teokem/project-work-2020-yuliiahrabar.git) or clone this repository by running the following in a terminal:
```bash
git clone https://github.com/teokem/project-work-2020-yuliiahrabar.git
```
3. Install and activate the `fission` environment described by the file [`environment.yml`](/environment.yml)  by running the following in a terminal:

```bash
conda env create -f environment.yml
conda activate fission
```
4. Run **GEANT4_FissionFragments.ipynb** notebook:

```bash
jupyter notebook GEANT4_FissionFragments.ipynb
```
