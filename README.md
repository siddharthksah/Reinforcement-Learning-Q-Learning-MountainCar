# Reinforcement-Learning-Q-Learning-MountainCar
Easy to use RL on a Mountain Car - trained on GPU!

Below are instructions to implement in in your local system using a separate development environment using the [Conda](http://conda.pydata.org/docs/index.html) package management system which comes bundled with the Anaconda Python distribution provided by Continuum Analytics.

### Step 1:
[Fork and clone](https://github.com/siddharthksah/Reinforcement-Learning-Q-Learning-MountainCar) a copy of this repository on to your local machine.

### Step 2:
Create a `conda` environment called `reinforcement-learning` and install all the necessary dependencies, the environment.yml file is uploaded in the repo for ease:

    $ conda env create --file environment.yml
    
### Step 3:
Install the extra dependencies, it is not required but helps in making sure the jupyter notebook is running in the right conda env:

    $ conda install nb_conda

### Step 4:
Activate the `reinforcement-learning' environment:

    $ source activate reinforcement-learning

To confirm that everything has installed correctly, type

    $ which pip

at the terminal prompt. You should see something like the following:

    $ ~/anaconda/envs/reinforcement-learning/bin/pip

which indicates that you are using the version of `pip` that is installed inside the `reinforcement-learning` Conda environment and not the system-wide version of `pip` that you would normally use to install Python packages.

### Step 5:
Change into your local copy of the this repo:

    $ cd Reinforcement-Learning-Q-Learning-MountainCar

### Step 6:
Start the notebook:

    $ jupyter notebook
    
Inspired from this awesome [work](https://github.com/Rafael1s/Deep-Reinforcement-Learning-Algorithms)
