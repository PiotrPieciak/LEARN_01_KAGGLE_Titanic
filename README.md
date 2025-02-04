# Titanic Survival Prediction
## Description of project
This project, conducted during the Codilla bootcamp, focuses on predicting passenger survival from the Titanic dataset. Guided by course materials and my mentor, I improve the analysis with my own ideas and insights.

The project include multiple stages of data processing, beginning with thorough exploratory data analysis (EDA) to understand the dataset's structure and identify significant patterns. I then performed feature engineering to create meaningful variables that could improve model performance.

Three classification models were developed and compared:

1. Logistic Regression
2. Random Forest Classifier
3. Deep Learning Model

First two models are using gridsearch for hyperparameter tuning based on data processes in pipeline. Deep Learning required bit different approach however data are also processes in pipeline.

The primary evaluation metric was the F1 score, particularly for the class representing survivors. This focus ensured a robust understanding of model performance in identifying those who survived the disaster.

While this project is rooted in educational materials, it also reflects my contributions, including custom feature engineering techniques and customized evaluation strategies.

By blending theoretical learning with practical application, this project demonstrates foundational skills in data analysis, machine learning, and model optimization.

## Dataset 
The dataset is publicly available on Kaggle under an open license

**Source:** [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
## Installation & Setup
To run this project, you need **Python** and **Jupyter Notebook** installed and the required libraries. Follow these steps using **Anaconda Prompt**:

1. Download the repository
Click on the **Code** button and select **Download ZIP** or clone the repository using Git:	
 	```
	git clone https://github.com/PiotrPieciak/LEARN_01_KAGGLE_Titanic.git
	cd LEARN_01_KAGGLE_Titanic
 	```
  
3. Create and activate a Conda environment (optional but recommended)
	```
	conda create --name titanic_env python=3.10
	conda activate titanic_env
	```
 
4. Instal required dependencies:
	```
	pip install -r requirements.txt
 	```
 
5. Open Jupyter Notebook:
	```
 	jupyter notebook
  	```
 
6. Run the project
* Open LEARN_01_KAGGLE_Titanic_dataset.ipynb in Jupyter Notebook.
* Run all cells to execute the analysis.

**Note:**  The dataset (Titanic-Dataset.csv) must be in the same folder as the notebook for the code to work correctly.

## Dependencies
* imbalanced-learn==0.12.4
* matplotlib==3.9.2
* numpy==1.26.4
* pandas==2.2.2
* scikit-learn==1.5.1
* seaborn==0.13.2
* tensorflow==2.18.0
