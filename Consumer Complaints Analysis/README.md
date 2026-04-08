# Consumer Complaints Analysis & Classification

## Overview

This project presents a comprehensive analysis of consumer complaint data provided by the Consumer Financial Protection Bureau (CFPB). It combines exploratory data analysis (EDA) and machine learning techniques to uncover patterns in financial disputes and predict company responses based on complaint characteristics.

---

## Objectives

* Analyze relationships between financial products and reported issues
* Identify key drivers of customer dissatisfaction
* Evaluate company response efficiency
* Build a predictive model for complaint outcomes

---

## Dataset Description

The dataset contains over 62,000 records of consumer complaints with the following features:

* **Complaint ID** – Unique identifier for each record
* **Product / Sub-product** – Financial service category
* **Issue / Sub-issue** – Reported problem details
* **Company Response to Consumer** – Resolution outcome
* **Timely Response** – Indicates if response met SLA
* **Submitted via** – Submission channel (Web, Phone, Referral, etc.)

---

## Technology Stack

**Programming Language**

* Python

**Libraries**

* Data Processing: `pandas`, `numpy`
* Visualization: `matplotlib`, `seaborn`, `plotly`
* Machine Learning: `scikit-learn`, `xgboost`

---

## Methodology

### 1. Exploratory Data Analysis (EDA)

* Distribution analysis by product and state
* Frequency analysis of complaint issues
* Relationship mapping between issues and sub-issues

### 2. Data Preprocessing

* Handling missing values (notably in *Sub-issue*)
* Encoding categorical variables using `LabelEncoder`
* Preparing features for modeling

### 3. Model Development

* Train-test split
* Model training using **XGBoost Classifier (XGBClassifier)**
* Prediction of company responses

### 4. Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score

---

## Results

* Achieved approximately **96% accuracy**
* Strong performance on majority classes
* Reduced performance on minority classes (e.g., monetary relief cases)

---

## Project Structure

```
├── Complaints_Analysis.ipynb   # Main analysis notebook
├── data/                       # Dataset files
└── README.md                   # Project documentation
```

---

## Installation & Usage

### 1. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
```

### 2. Run the Project

```bash
jupyter notebook Complaints_Analysis.ipynb
```

---

## Future Work

* Improve model performance using hyperparameter tuning
* Address class imbalance techniques (SMOTE, weighting)
* Deploy model as an API service
* Develop interactive dashboards using Power BI or Tableau

---

## Author

**Ahmed Saber**

---
