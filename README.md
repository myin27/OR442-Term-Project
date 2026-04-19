# OR442-Term-Project

For setup instructions, please click [here](#setup--installation).

To view our Jupyter Notebook, please click [here](/project.ipynb).


## Background

For our final project for stochastic models class, groups of up to four people were tasked with using Monte-Carlo simulations to figure out how to best invest \$1,000,000 in the folowing four mutual funds.

- Fund A: $Unif[-40\%, 60\%]$
- Fund B: $Unif[-10\%, 24\%]$
- Fund C: $Normal(7\%, (2\%)^2)$
- Fund D: $Unif[5\%, 7\%]$

## Process

We decided to use a Jupyter Notebook in order to let us visualize our distributions with Matplotlib and the help of NumPy. Each section of the notebook investigates a different question and shows an accompanying visual to aid our analysis.

## Setup & Installation

Run the following command on your terminal to install dependences.

```sh
pip install numpy matplotlib
```

Then, make sure you open `project.ipynb` in either Jupyter Lab, Jupyter Notebook, or in VSCode with Microsoft's Jupyter Notebook extensions.

After opening the file, hit "Run all" in order to run all the cells to get the appropriate outputs.
