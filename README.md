# pyimagej-julab
Playground for testing PyImageJ with Jupyetr Lab

## Setup

Create environmenet and install per [pyimagej](https://github.com/imagej/pyimagej) default setup so we do not need to install OpenJDK and Maven manually.

```
conda install mamba -n base -c conda-forge
mamba create -n jl-pyij -c conda-forge pyimagej openjdk=8
conda activate jl-pyij
```

after activating env, we need to see/have:

**C:\Users\user>set "JAVA_HOME_CONDA_BACKUP=C:\Programy\Eclipse Foundation\jdk-8.0.302.8-hotspot\"**

**C:\Users\user>set "JAVA_HOME=C:\Users\user\Anaconda3\envs\jl-pyij\Library"**

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

# Trubleshooting

  -  [ ] Check that **JAVA_HOME_CONDA_BACKUP** is set
  -  [ ] Check that **JAVA_HOME** is set
