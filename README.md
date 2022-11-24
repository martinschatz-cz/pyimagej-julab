# pyimagej-julab
Playground for testing PyImageJ with Jupyetr Lab

## Setup

Create environmenet and install per [pyimagej](https://github.com/imagej/pyimagej) default setup so we do not need to install OpenJDK and Maven manually.

```
conda install mamba -n base -c conda-forge
mamba create -n jl-pyij -c conda-forge pyimagej openjdk=8
conda activate jl-pyij
```

Install Jupyter lab
```
mamba install -c conda-forge jupyterlab
```

run Jupyter Lab
```
jupyter-lab
```
## notes
 * On Win10 not working from default - java8 problem (?)
