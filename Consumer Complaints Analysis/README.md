Consumer Complaints Analysis & Classification
This project provides a comprehensive analysis of consumer complaint data submitted to the CFPB (Consumer Financial Protection Bureau). It utilizes exploratory data analysis (EDA) to uncover trends in financial disputes and employs machine learning to classify company responses, helping to predict outcomes based on complaint characteristics.

📋 Project Overview
The primary goal of this project is to analyze the relationship between various financial products, the issues raised by consumers, and the subsequent responses from companies. By leveraging a dataset of over 62,000 records, the project identifies key drivers of consumer dissatisfaction and evaluates the efficiency of company resolutions.

📊 Dataset Description
The analysis is performed on a consumer complaints dataset containing several key features:

Complaint ID: Unique identifier for each complaint.

Product & Sub-product: The type of financial service involved (e.g., Mortgage, Credit Reporting).

Issue & Sub-issue: The specific problem identified by the consumer.

Company Response to Consumer: The outcome of the complaint (e.g., "Closed with explanation," "Closed with monetary relief").

Timely Response: Indicates whether the company responded within the required timeframe.

Submitted via: The channel used to submit the complaint (Web, Referral, Phone, etc.).

🛠️ Tech Stack
Language: Python

Libraries: * Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn, plotly

Machine Learning: scikit-learn, XGBoost

🚀 Key Analysis Workflow
Exploratory Data Analysis (EDA): * Visualizing complaint distribution by State and Product.

Analyzing the frequency of specific issues (e.g., "Applying for a mortgage").

Mapping the relationship between issues and sub-issues to identify data gaps.

Data Preprocessing:

Handling missing values in critical columns like Sub-issue.

Encoding categorical variables using LabelEncoder for model readiness.

Machine Learning Modeling:

Splitting data into training and testing sets.

Training an XGBClassifier to predict the Company response to consumer.

Evaluation:

Assessing model performance using Accuracy scores and detailed Classification Reports (Precision, Recall, F1-Score).

📈 Results
The implementation achieves high classification accuracy (approx. 96%), particularly in identifying standard resolutions, though it highlights challenges in predicting minority classes like specific monetary relief outcomes.
