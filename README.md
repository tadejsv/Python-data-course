# Python data course
A short course focusing on data analysis in python. 

## Plan
In this course I plan to teach

1. Basic Jupyter Lab (and Markdown) and Git
2. Bais Terminal (shell) commands, creating environments with Conda, using AWS servers
3. Python basics
4. OOP and IO in Python
5. Numpy and plotting (Matplotlib)
6. Pandas IO, selecting data, basic manipulations
7. Pandas groupby/pivot
8. Basic SQL (Postgres) - maybe

## How to start

To start, you will need to
0. Have a conda environemnt called `data`, which has jupyter lab installed. If you don't even have conda installed, just type these commands one-by-one in the command line (you will learn later what they do)
```
curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda.sh
chmod +x miniconda.sh
./miniconda.sh -b -p ~/miniconda3
rm ./miniconda.sh
echo ". ~/miniconda3/etc/profile.d/conda.sh" >> ~/.bashrc
. ~/.bashrc
conda create -n data jupyterlab
```
1. Fork this repository
2. Clone the forked repository to your computer. To do this, 
    - go to the github page of your fork, click on the "Clone or download" button and copy the link
    - Open your terminal (with <kbd>ALT</kbd>+<kbd>CTRL</kbd>+<kbd>T</kbd>), navigate to `Documents` directory and clone the repository using the link:
```
    cd ~/Documents
    git clone LINK-YOU-COPIED-FROM-GITHUB
```
3. Activate the `data` conda environment (which should have Jupyter lab installed), and run Jupyter lab
```
conda activate data
jupyter-lab
```
4. Now select the first notebook (`0-Introduction.ipynb`) in Jupyter Lab and you can start working!

## How to submit exercises

You will submit all exercises here on GitHub by issuing pull requests (to your branch on the original repository). The details are all explained in the first lecture.

