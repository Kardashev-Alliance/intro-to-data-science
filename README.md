# Setting Up Your Data Science Environment

## Introduction
For this course, we will set up a data science environment using Miniconda3. Miniconda is a lightweight distribution of the Conda package manager, which we'll use to manage our Python packages and dependencies.

## Step-by-Step Guide

### 1. Install Miniconda3

#### For Windows:
- Download the Miniconda3 Windows installer [here](https://docs.conda.io/en/latest/miniconda.html).
- Launch the installer and follow the on-screen instructions.

#### For macOS:
- Download the Miniconda3 macOS installer [here](https://docs.conda.io/en/latest/miniconda.html).
- Open a terminal and navigate to the location of the downloaded installer.
- Run the following command: `bash Miniconda3-latest-MacOSX-x86_64.sh`

#### For Linux:
- Download the Miniconda3 Linux installer [here](https://docs.conda.io/en/latest/miniconda.html).
- Open a terminal and navigate to the location of the downloaded installer.
- Run the following command: `bash Miniconda3-latest-Linux-x86_64.sh`

### 2. Create a Custom Conda Environment
Once Miniconda3 is installed, create a new Conda environment for this course. Open a terminal or command prompt and enter the following command:
`conda create --name my_data_env python=3.8`

### 3. Activate the Environment
To use the new environment, you must activate it with:
`conda activate my_data_env`

### 4. Install Data Science Libraries
With the environment activated, we can install the necessary libraries for this course with:
`conda install numpy pandas matplotlib seaborn scikit-learn jupyter`

### 5. Launch Jupyter Notebook (Optional)
To start a Jupyter Notebook session, simply type:
`jupyter notebook`
This will open a new browser window/tab with the Jupyter Notebook interface. From here, you can create new notebooks and begin your data science journey!

## Conclusion
You've now successfully set up your data science environment and are ready to embark on your learning journey!
