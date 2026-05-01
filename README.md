# OR442-Term-Project

Group members: Thanh Nguyen, Madison Yin, Leena Koussa, Rose Alvarado

For setup instructions, please click [here](#setup--installation).

To view our Jupyter Notebook, please click [here](./project.ipynb).

You can also view the HTML file for a static screenshot of our final notebook [here](./project.html).

## Background

For our final project for stochastic models class, groups of up to four people were tasked with using Monte-Carlo simulations to figure out how to best invest \$1,000,000 in the following four mutual funds.

- Fund A: $Unif[-40\\%, 60\\%]$
- Fund B: $Unif[-10\\%, 24\\%]$
- Fund C: $Normal(7\\%, (2\\%)^2)$
- Fund D: $Unif[5\\%, 7\\%]$

## Process

We decided to use a Jupyter Notebook in order to let us visualize our distributions with Matplotlib and the help of NumPy. Each section of the notebook investigates a different question and shows an accompanying visual to aid our analysis.

## Setup & Installation

Ensure that you have Python installed. If not, you can visit the official website for Python, [https://www.python.org/downloads](https://www.python.org/downloads), to download the latest version of Python for your system.

Run the following command on your terminal to install dependencies.

```sh
pip install numpy matplotlib
```

Then, make sure you open `project.ipynb` in either Jupyter Lab, Jupyter Notebook, or in VSCode with Microsoft's Jupyter Notebook extensions so you can properly view the Jupyter Notebook. If you open `project.ipynb` using a basic text editor (Notepad++, BBEdit, VIM), you will only be able to see the underlying JSON data since Jupyter Notebooks are simply rendered JSON files.

After opening the file, hit "Run all" in order to run all the cells to get the appropriate outputs. If prompted to pick a kernel, pick the version of Python you have downloaded.
