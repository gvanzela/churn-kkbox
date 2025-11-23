# Churn Prediction (Banking Variation – KKBox Dataset)

## Overview
This project implements a complete churn-prediction workflow using the public KKBox dataset.  
It includes preprocessing, feature engineering, modeling, evaluation, and visual analysis in a single Jupyter Notebook.

## Key Results
- Recall (retention-oriented): **71%**
- Precision: optimized for cost–benefit strategy  
- Final Model: **Gradient Boosting with custom feature engineering**

## Repository Structure

````text
project/
│
├── notebooks/
│   └── vFinal_case_datamaster.ipynb     # Full notebook with analysis and modeling
│
├── data/                                # Place KKBox datasets here (not included in the repo)
│   ├── members.csv
│   ├── transactions.csv
│   ├── user_logs.csv
│   └── sample_submission.csv
│
├── reports/
│   └── figures/                         # Generated charts and outputs
│
├── README.md
└── LICENSE
````

## How to Run
1. Download the KKBox datasets and place them in the folder `data/`.  
2. Open the notebook:

```bash
notebooks/vFinal_case_datamaster.ipynb
```

3. Run all notebook cells sequentially (Google Colab recommended).

## Dataset Source
KKBox Churn Dataset:  
https://www.kaggle.com/datasets/gcenachi/case-data-master-2024

## Objective
Demonstrate a complete workflow for churn prediction with emphasis on:
- High recall for retention  
- Interpretability of main drivers  
- Practical feature engineering  
- Realistic modeling aligned with business KPIs  

## Notebook Contents
- Data loading and cleaning  
- Exploratory data analysis  
- Custom feature engineering  
- Gradient Boosting modeling  
- Cross-validation  
- Evaluation metrics  
- Final insights and recommendations  

## License
MIT License.
