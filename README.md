# M1 Machine Learning Coursework

This is a project which build an inference pipeline which successfully sums two MNIST digits.

Author: Panos Antonopoulos (University of Cambridge)

## Features

The `report` which goes through all the coursework solutions together with a comprehensive overview of the background and methods used to solve each part of the project.

The `code` folder which contains the Jupyter notebook that performs the hyper-parameter tuning for the neural network, random forest and support vector machine. Also within this folder is the file `notebook.ipynb` which contains the code solutions to the rest of the coursework.

The `data` folder contains the images used in the report, the .csv files storing the validation accuracies of the models and the optimal hyper-parameters found from the hyper-parameter tuning.

The `model` folder which contains the best neural network.

The `weights` folder which contains the weights of the best neural network (as required from question 2).

After cloning the repository, please enter the `environment` folder and run the command `conda env create -f environment.yml` to create the conda environment. After doing so, please activate the environment using `conda activate M1_coursework_conda_environment` and create the Jupyter kernel using `python -m ipykernel install --user --name M1_coursework_conda_environment --display-name "m1condaenv"`. After this, the notebooks will run perfectly!