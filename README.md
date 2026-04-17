# statistical-analysis-python-project
This my second project in the capstone course of Udacity's Master's Degree in AI (https://www.udacity.com/masters-artificial-intelligence). 

## Overview
In this project, we conduct a complete statistical analysis for a dataset on passengers of the Titanic (https://www.kaggle.com/c/titanic/data). 
This dataset contains biometric and economic information on the Titanic's passengers, as well as whether each passenger survived its sinking. 
More precisely, the Kaggle dataset is already split into a training batch (train.csv) and a test batch (test.csv), and we will focus on the training set in this project.

We will analyze some statistical relationships between age, sex, fare price, and survival in the data.
After importing modules and loading the data, we perform some cleaning tasks, explore descriptive statistics and create some visualizations, before delving into hypothesis testing. 
We conclude by a short summary of our findings.

## How to run the project
The main component of the project is the Jupyter notebook 'analysis.ipynb'.
When checking out this repository, the dataset file 'train.csv' is already included.
In addition, the repository contains a 'requirements.txt' file with all required dependencies, which was generated via the command
	
	pip freeze > requirements.txt
	
It can be used e.g. in a virtual Anaconda environement by opening an Anaconda prompt window in the project directory and running the following commands:

	conda create -n env_msai_cap_2 python
	conda activate env_msai_cap_2
	pip install -r requirements.txt
	python -m ipykernel install --user --name=env_msai_cap_2
	jupyter notebook
	
The last command opens a Jupyter GUI, where one needs to click on the notebook 'analysis.ipynb' and then click on Run... -> Run All Cells
