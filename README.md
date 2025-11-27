# Churn Prediction (KKBox Dataset)

## Overview
This project delivers a full churn-prediction pipeline built on the KKBox dataset.
The notebook covers data ingestion, memory-efficient processing, exploratory analysis, custom feature engineering, model training with XGBoost, and performance evaluation — all structured for a real business-oriented retention scenario.

## Key Results
- Recall (retention-oriented): **71%**
- Precision: optimized for cost–benefit strategy  
- Final Model: **Gradient Boosting with custom feature engineering**

## Repository Structure

````text
notebooks/
├── vFinal_case_datamaster.ipynb

data/                          # Download the datasets in the link below
├── members.csv
├── transactions.csv
├── user_logs.csv

reports/
└── figures/                   # Generated charts and outputs

README.md
LICENSE

````

## How to Run

This project is designed to run on **Google Colab** due to the size of the KKBox datasets (several GB).

### 1. Download the dataset from Kaggle
KKBox dataset:
https://www.kaggle.com/datasets/gcenachi/case-data-master-2024

### 2. Upload the dataset to your Google Drive
Create a folder in your Drive, for example:
Place the parquet files inside the `data/` folder.

### 3. Open the notebook on Google Colab
Upload or open:
```bash
notebooks/vFinal_case_datamaster.ipynb
```
### 4. The notebook will automatically:
- mount your Google Drive  
- create the folder structure  
- read the KKBox parquet files  
- run preprocessing, feature engineering, and modeling  

No manual folder creation or local setup is required.

## Objective
Demonstrate a complete end-to-end workflow for churn prediction using supervised machine learning, with emphasis on:
- High recall for customer retention
- Interpretability of the main behavioral drivers
- Practical feature engineering
- Modeling aligned with business KPIs

## Notebook Contents
## Notebook Contents
- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Behavioral and temporal feature engineering
- Gradient Boosting model training
- Cross-validation and hyperparameter tuning
- Evaluation metrics (recall, precision, cost-impact)
- Final insights and business recommendations 

## License
MIT License.
