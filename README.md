# Titanic Survival Prediction
## Description of project
This project analyzes the famous Titanic dataset to predict passengers survival using three different machine learning algorithms: RandomForest, LogisticRegression and Neural Network. It includes data processing, exploratory data analysis (EDA), feature engineering and model trainings.
## Dataset 
The dataset is publicly available on Kaggle under an open license

**Source:** [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
## Installation & Setup
To run this project, you need **Python** and **Jupyter Notebook** installed and the required libraries. Follow these steps using **Anaconda Prompt**:

1. Download the repository

Click on the **Code** button and select **Download ZIP** or clone the repository using Git:  
 	
  	```
	git clone https://github.com/PiotrPieciak/LEARN_01_KAGGLE_Titanic.git
	cd titanic-ml-project
2. Create and activate a Conda environment (optional but recommended)

	```
	conda create --name titanic_env python=3.10
	conda activate titanic_env
3. Instal required dependencies:

 	```
	pip install -r requirements.txt
4. Open Jupyter Notebook:

 	```
 	jupyter notebook
5. Run the project
* Open titanic_analysis.ipynb in Jupyter Notebook.
* Run all cells to execute the analysis.

**Note:**  The dataset (titanic_dataset.csv) must be in the same folder as the notebook for the code to work correctly.
5. Navigate to notebooks/LEARN_01_KAGGLE_Titanic_datase.ipynb and run all cells
## Dependencies
* imbalanced-learn==0.12.4
* matplotlib==3.9.2
* numpy==1.26.4
* pandas==2.2.2
* scikit-learn==1.5.1
* seaborn==0.13.2
* tensorflow==2.18.0
