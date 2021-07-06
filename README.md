# Course on neuromorphic computing at RAAI Summer School, Sochi, 2021
http://school.raai.org/

## Installation
0. Install Anaconda 3 (https://www.anaconda.com/products/individual)
1. Create conda environment
`conda create --name neuro python=3.6.13`
2. Install dependencies
`conda install numpy scipy jupyter matplotlib mpmath setuptools setuptools_scm mock nose`
3. Install Brian2 - simulator for biological neurons (brian2.readthedocs.io/)
`conda install -c conda-forge brian2`
4. Install excersises from Neuronal Dynamics book (https://neuronaldynamics-exercises.readthedocs.io/en/latest/setup.html)
`pip install neurodynex3`
5. Install OpenAI Gym (https://gym.openai.com/)
`conda install -c conda-forge gym
conda install -c conda-forge pybox2d`
## Content
### Seminar 1. Introduction to spiking neural networks.
### Seminar 2. Biophysical models. Introduction to OpenAI Gym and neuromorphic control
### Seminar 3. Neuromorphic control. Central pattern generators.
