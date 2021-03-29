# SETUP
Install `miniconda3`. After installation follow below given instructions:
```
conda env create --prefix ./env --file environment.yml
```
To activate env
```
conda activate ./env
```
To update env (after changing some dependencies):
```
conda env create --prefix ./env --file environment.yml --force
```
If you changed (added/removed) dependencies using `conda install` then update `environment.yml` file  accordingly.