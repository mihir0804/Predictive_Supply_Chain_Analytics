# Predictive Supply Chain Analytics using Machine Learning

## Overview
This repository applies advanced machine learning techniques to Supply Chain Management (SCM), focusing on demand forecasting, inventory optimization, and supplier risk analysis. It demonstrates the full data science workflow — from exploratory data analysis and preprocessing to model development, evaluation, and actionable business insights.  
The goal is to build data-driven solutions that enhance efficiency, reduce costs, and enable smarter decision-making in supply chain operations.

---
predictive-supply-chain-analytics/
│
├── data/                     # Raw and processed datasets
│   └── scm_dataset.csv
│
├── notebooks/                # Jupyter notebooks for each project stage
│   ├── 1_EDA.ipynb
│   ├── 2_Preprocessing.ipynb
│   ├── 3_Modeling.ipynb
│   ├── 4_Model_Evaluation.ipynb
│   └── 5_Insights.ipynb
│
├── models/                   # Saved trained models
│   └── scm_best_model.joblib
│
├── reports/                  # Generated reports (PDF, markdown, etc.)
│   └── scm_analysis_report.pdf
│
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── LICENSE                   # Apache 2.0 License


## Project Workflow
The project is structured into modular Jupyter notebooks that represent different stages of the pipeline:

1. **Exploratory Data Analysis (EDA):** Understanding supply chain datasets, visualizing trends, and identifying inefficiencies.  
2. **Preprocessing:** Data cleaning, handling missing values, feature engineering, encoding categorical variables, and scaling numerical features.  
3. **Modeling:** Training baseline and advanced models for demand forecasting, inventory optimization, and risk prediction.  
4. **Evaluation:** Assessing models with appropriate metrics, confusion matrices, ROC curves, and error analysis.  
5. **Insights:** Extracting business-relevant findings to guide operational improvements and strategic decisions.  

---

## Key Features
- End-to-end machine learning pipeline tailored for supply chain data.  
- Predictive models for **demand forecasting**, **inventory optimization**, and **supplier performance analysis**.  
- Integration of explainability techniques (e.g., SHAP) to highlight key drivers.  
- Business-focused insights for **cost reduction**, **risk mitigation**, and **efficiency improvements**.  
- Reproducible workflows with saved models and preprocessing pipelines.  

---

## Results
The project delivers:  
- Reliable demand forecasts to anticipate market fluctuations.  
- Inventory optimization strategies to reduce holding and shortage costs.  
- Risk analysis tools to identify vulnerable suppliers and logistics bottlenecks.  
- Data-driven insights that directly support operational excellence in SCM.  

---

## How to Run
Clone the repository and install dependencies:  

```bash
git clone <repository_url>
cd predictive-supply-chain-analytics
pip install -r requirements.txt
jupyter notebook
