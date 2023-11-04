# Monte-Carlo-Proyect
This is a repository for the computational astronomy course
## Necessary libraries
To run this code we need:

import numpy as np

import matplotlib.pyplot as plt

import random

import pandas as pd


## Monte Carlo Code
In order to run the Monte Carlo code, with the number of stars you want, you must change the cell:

test = monte_carlo(10000000)

Note: Very low numbers may return empty lists since the generated-masses have not passed the test

The output is a dataframe with the name "output.csv" in the folder where you copy this repository

## Analysis Code
For the analysis code you must change the following line to your needs

df = pd.read_csv("/home/astrotomi/Downloads/10M.csv")



