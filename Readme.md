**create environment for this project and packages to maintain clean repo**
## conda create -n sem_env python=3.8
**Activate the environment**
## conda activate sem_env
**Integrate conda environment Jupyter notebook**
## conda install ipykernel   
## python -m ipykernel install --user --name myenv --display-name "sem_env"
**Install faiss in the conda environment**
## To install this package run one of the following:
## conda install -c conda-forge faiss
## conda install -c "conda-forge/label/broken" faiss
**Install sea born**
## pip3 install seaborn
