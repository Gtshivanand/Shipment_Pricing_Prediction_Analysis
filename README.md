# Shipment_Pricing_Prediction_Analysis

# 📦 Project Overview:
The **Shipment Pricing Prediction** project aims to predict shipment prices based on various factors in the supply chain domain using machine learning techniques. This project addresses the growing need for accurate predictions in the rapidly evolving supply chain analytics market.

# 🔍 Problem Statement:
The supply chain analytics market is projected to grow significantly, with organizations needing to optimize pricing strategies. This project focuses on predicting shipment pricing using available data to help supply chain leaders make informed decisions.

# Approach: 
The classical machine learning tasks like Data Exploration, Data Cleaning,
Feature Engineering, Model Building and Model Testing. Try out different machine
learning algorithms that’s best fit for the above case.

# Key Highlights

* Objective: To analyze and predict shipment costs based on various features such as shipment weight, dimensions, distance, and other logistics-related factors.

* Techniques Used: 
  
  * Data preprocessing and feature engineering.
  
  * Exploratory Data Analysis (EDA) for insights into cost factors.
 
  * Model building and evaluation using machine learning algorithms.

* Tools & Libraries: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,Flask

*  Outcome: A predictive model with optimized performance to accurately estimate shipment pricing.

# Repository Contents:
  
  * Code: Well-documented scripts for data processing, model training, and evaluation.

  * Data: Example datasets (or links to datasets) used for training and testing.
  
  * Notebooks: Interactive Jupyter Notebooks for step-by-step analysis.
  
  * Reports: Insights and results from the project in a structured format.
#   Applications:
    
* Logistics optimization.

* Cost forecasting for shipment companies.
    
* Pricing strategy improvements for logistics and e-commerce businesses.

## 🔄 Architecture & Process Flow:
### Process Flow:
![Screenshot 2024-10-21 192106](https://github.com/Gtshivanand/Shipment_Pricing_Prediction_Analysis/blob/main/Snapshots/ProcessFlow.png)
### Data Validation and Transformation
- **Missing Values**: All missing values were replaced with the mode (most frequent value).
- **Numerical Columns**: Standardized to prevent data leakage using pipelines.
- **Categorical Columns**: Encoded using either label encoding or one-hot encoding.

### Model Training
![Screenshot 2024-10-21 192043](https://github.com/Gtshivanand/Shipment_Pricing_Prediction_Analysis/blob/main/Snapshots/Modelling.png)
  
- Accumulated data was exported to Python and read using Pandas.
- Performed exploratory data analysis (EDA) to identify distributions, outliers, and trends.
- Checked for null values; if present, they were imputed.
- Encoded categorical values into numeric values and scaled numerical features using StandardScaler.
- New features were created to enhance model building based on business insights.

### Prediction
- Optimized the model for accuracy with a training R-squared of 0.998273 and a test R-squared of 0.991598.
- Key features: `Days to Process`, `Line Item Insurance`, `Shipment Mode`, `Freight Cost`.

### Project Output Result
![Screenshot 2024-10-21 192322](https://github.com/user-attachments/assets/5eef75a0-e9b0-4001-b154-20d5e9dddf64)

- Training R²: 0.998273
- Test R²: 0.991598
- Important features identified: `Days to Process`, `Line Item Insurance`, `Shipment Mode`, `Freight Cost`.

---
## 📊 Dataset
- **Dataset Link**: [Click here!](https://www.kaggle.com/datasets/divyeshardeshana/supply-chain-shipment-pricing-data)

---
## 🛠️ Installation
To run this project, you will need Python and the required libraries. Set up a virtual environment and install dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn flask

# Feedback and Suggestions:

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

 **LinkedIn**: [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
 
 **Email**: shivanandnashi97@gmail.com


Looking forward to connecting and exchanging ideas!
