# ESS_Game

This repository contains some example code for how to run the ESS game environment. The current implementation of the ESS game environment relies on modified versions of OpenAI Baselines and OpenAI Gym.

## Requirements and Setup
The code is designed to run on Python 3, and Tensorflow, and also uses a Jupyter Notebook.

The modified OpenAI Gym and Baselines can be found below, which we recommend installing in a virtual environment.

https://github.com/rubai5/gym

https://github.com/rubai5/baselines

To get the jupyter kernel to work with the packages in the virtual environment, you can set up according to e.g.:

https://anbasile.github.io/programming/2017/06/25/jupyter-venv/

### Step by step commands for Setup
Here's a step by step example of how to setup the code to run

1) Create a virtual environment. (E.g. with Python 3, can use: https://docs.python.org/3/tutorial/venv.html )

2) Activate the virtual environment: e.g. source path/to/virtualenv/bin/activate

3) Install modified gym and baselines, e.g. (i) git clone <path to module> (ii) cd to directory it got installed in (iii) pip3 install -e . 
  
4) Install other packages: Numpy, Tensorflow, Matplotlib (optional), mpi4py 
  
5) Set up a jupyter kernel following instructions e.g. https://anbasile.github.io/programming/2017/06/25/jupyter-venv/

