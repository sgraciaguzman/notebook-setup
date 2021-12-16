# Getting Started on Github 
This repository serves as a resource to get familiar with github and how to integrate github to Jupyter Lab.
This repo also outlines steps to export a conda vritual environment for sharing on Github or other platforms.
Finally this repo can be used to test out new techniques or methods to use Github/ jupyter notebooks without affecting any existing repos/projects.


## Jupyter Lab git extension
For most projects requiring Python scripts, JupyterLab is the IDE of choice. Together with the git extension, it is possible to integrate with Github and easily share notebooks and utilize all that Github has to offer. Since there is currently no native integrations with git, an extension galled Jupyter Lab git is used. For complete information see the documentation [here](https://github.com/jupyterlab/jupyterlab-git).

### Vamsi's instructions
Initial Set Up  
Install the Git Widget  
Install Node.js conda install -c conda-forge nodejs  
Install npmconda  
install yarnconda update -n base -c defaults conda  
Install Git Extension  
conda install -c conda-forge jupyterlab jupyterlab-git


### What I did:
```
conda install nodejs
```
install jupyter lab git  
Follow prompt for additional terminal commands

## How to make utilize git extension within jupyter lab
After installation you should see a new git logo tab on the left hand side of the jupyter lab interface. 

Clicking this should show three options:  

*Clone repository ussing HTTPS*
**HAD A LOT OF TROUBLE WITH THIS **
should be able to see all files within repo and make changes
subtmit changes for staging -> commit with comment -> pushed

changes should show up on repo 


## How to make a copy of your virtual conda environment for uploading :
Run anaconda prompt as admin  
Have your desired venv active ex.
```
conda activate myenv
```
*Replace myenv with the name of your env
```
conda env export --from-history > environment.yml
```
It seems that jupyterlab git package might not be compatible with installing a venv this way





