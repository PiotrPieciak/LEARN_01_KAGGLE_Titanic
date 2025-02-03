# Titanic Survival Prediction
## Description of project
This project analyzes the famous Titanic dataset to predict passengers survival using three different machine learning algorithms: RandomForest, LogisticRegression and Neural Network. It includes data processing, exploratory data analysis (EDA), feature engineering and model trainings.
## Dataset 
The dataset is publicly available on Kaggle under an open license

**Source:** [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
## Installation & Setup
To run this project, you need **Python** and **Jupyter Notebook** installed.

1. Download 3 files from this repository:
* data/Titanic-Dataset.csv
* notebooks/LEARN_01_KAGGLE_Titanic_datase.ipynb
* requirements.txt

2. Create and activate virtual enviroment (optional but recommended).

	python -m venv venv  
	source venv/bin/activate  # On Windows: venv\Scripts\activate

4. Instal required dependencies:

	pip install -r requirements.txt

5. Open Jupyter Notebook:

 	jupyter notebook
  
6. Navigate to notebooks/LEARN_01_KAGGLE_Titanic_datase.ipynb and run all cells
## Dependencies
* imbalanced-learn==0.12.4
* matplotlib==3.9.2
* numpy==1.26.4
* pandas==2.2.2
* scikit-learn==1.5.1
* seaborn==0.13.2
* tensorflow==2.18.0
