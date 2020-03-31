[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/)

# Study of symmetric and asymmetric fission of Copernicium-284

## Running the Jupyter-Notebook

For COMPUTE course project please check GEANT4_FissionFragments.ipynb notebook.

You can run it in the web browser on mybinder (without installing anything) by clicking the link [here](https://mybinder.org/) (ignore the following in that case). 

It is possible to run the notebook on your local computer as follows:

1. Install [miniconda3](https://conda.io/miniconda.html) alternatively the full [anaconda3](https://www.anaconda.com/download) environment on your laptop (the latter is **much** larger).
2. [Download](https://gitlab.com/lund-nsg/deadlayer-determination/-/archive/master/deadlayer-determination-master.zip) this repository.
3. Install and activate the `fission` environment described by the file [`environment.yml`](/environment.yml)  by running the following in a terminal:

```bash
conda env create -f environment.yml
source activate fission
./postBuild
```
4. Run the notebook via `jupyter-lab`

It is preferable to further configure _nbstripout_ for the git repo. If active, this program strips the notebook from the outputs and makes it easier for collaboration and merging. It is performed as follows: 

```bash
nbstripout --install
```

Note: it is however placed in the `postBuild` file.

