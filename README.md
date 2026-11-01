CT4101 Machine Learning Portfolio Project

Project Overview

Github Link: https://github.com/OCarolan2/CT4101-Machine-Learning-Portfolio-Project

Title: Predicting Netflix Subscriber Churn

This project uses machine learning to predict whether a Netflix customer will churn based on demographic, subscription and engagement data. It is a binary classification problem where churned = 0 means retained and churned = 1 means churned.

Dataset

Name: Netflix Customer Churn & Engagement Analytics
Source: Kaggle Dataset

The dataset contains 5,000 records and 14 variables, with churned as the target variable.

Project Structure

CT4101-Netflix-Churn/
├── data/
│   └── netflix_customer_churn.csv
├── notebooks/
│   └── Milestone 2.ipynb
├── README.md
├── environment.yml
└── assistance_declaration.md

Setup and Run Instructions

Install Anaconda or Miniconda.

Download the dataset from the Kaggle link and place netflix_customer_churn.csv in the data folder if it is not already included.

Open Anaconda Prompt and navigate to the project folder.

Create and activate the environment:

conda env create -f environment.yml
conda activate ct4101project

Launch Jupyter Notebook:

jupyter notebook

Open notebooks/milestone2_data_baseline.ipynb, select the project environment's Python kernel and run all cells.

Milestone 2

The notebook contains a data audit, preprocessing pipeline, stratified 70/20/10 training/validation/test split, and a Dummy Classifier baseline evaluated using accuracy, precision, recall, F1-score and ROC-AUC.

