# Course on neuromorphic computing at RAAI Summer School, Sochi, 2021
http://school.raai.org/

## Installation
### With Anaconda
0. Install Anaconda 3 (https://www.anaconda.com/products/individual)
1. Create conda environment

`conda create --name neuro python=3.6.13`

`conda activate neuro`

2. Install dependencies

`conda install numpy scipy jupyter matplotlib mpmath setuptools setuptools_scm mock nose`

3. Install Brian2, simulator for biological neurons (https://brian2.readthedocs.io/), and OpenAI Gym (https://gym.openai.com/)

`conda install -c conda-forge brian2 gym pybox2d`

4. Install excersises from Neuronal Dynamics book (https://neuronaldynamics-exercises.readthedocs.io/en/latest/setup.html)

`pip install neurodynex3`

### With pip

0. Create working directory `neuro-raai` and set it as a working directory in console
1. Create and activate Python environment `neuro-env` (https://docs.python.org/3/tutorial/venv.html):

`python3 -m venv tutorial-env`

On Linux:

`source neuro-env/bin/activate`

On Windows:

`neuro-env\Scripts\activate.bat`

2. Ensure that pip is installed: https://docs.python.org/3/tutorial/venv.html#managing-packages-with-pip
3. Install setuptools

`pip install "setuptools>=45" setuptools_scm`

5. Install Brian2: 

`pip install brian2`

5. Install examples in neurodynex3: https://github.com/EPFL-LCN/neuronaldynamics-exercises

`pip install neurodynex3`

## Content
### Seminar 1. Introduction to spiking neural networks.
### Seminar 2. Biophysical models. Introduction to OpenAI Gym and neuromorphic control
### Seminar 3. Neuromorphic control. Central pattern generators.
