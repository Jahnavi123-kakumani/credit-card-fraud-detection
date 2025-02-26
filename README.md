# Credit Card Fraud Detection  

## Overview  

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Credit Card Fraud Detection** dataset from Kaggle. The objective is to uncover patterns, trends, and anomalies in the data and gain insights into fraudulent and non-fraudulent transactions using descriptive analytics and visualization techniques.  

---

## Dataset  

**Source**: [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)  

### Key Features:  
- **Time**: Time elapsed between each transaction and the first transaction.  
- **V1-V28**: Principal components obtained using PCA (due to confidentiality, original features are not provided).  
- **Amount**: Transaction amount.  
- **Class**: Target variable (0 for non-fraud, 1 for fraud).  

---

## Objectives  

1. Perform **Exploratory Data Analysis** to:  
   - Understand the structure and distribution of the dataset.  
   - Identify patterns in fraudulent vs. non-fraudulent transactions.  
2. Use **descriptive analytics techniques** to summarize the dataset.  
3. Visualize the data using charts and graphs to highlight:  
   - Class imbalance between fraudulent and non-fraudulent transactions.  
   - Distribution of transaction amounts and time.  
   - Correlations between features.  
4. Detect anomalies, outliers, and missing values in the data.  
5. Summarize insights in a clear and concise report.  

---

## Tools & Libraries  

- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` for data manipulation  
  - `numpy` for numerical operations  
  - `matplotlib` and `seaborn` for data visualization  
  - `scikit-learn` for data preprocessing  
  - `kagglehub` for downloading the dataset directly from Kaggle  

---

## Methodology  

1. **Data Loading and Cleaning**:  
   - Loaded the dataset from Kaggle.  
   - Checked for missing values, outliers, and anomalies.  

2. **Exploratory Data Analysis (EDA)**:  
   - Performed statistical analysis to understand the dataset’s structure and distribution.  
   - Visualized data distributions, feature correlations, and class imbalance.  

3. **Key Insights**:  
   - Identified patterns and trends in fraudulent and non-fraudulent transactions.  
   - Highlighted the imbalance in the dataset, with fraudulent transactions being rare.  
   - Detected outliers in transaction amounts.  

---

## Results  

- **Class Imbalance**: Fraudulent transactions constitute a very small percentage of the dataset.  
- **Transaction Amounts**: Fraudulent transactions often involve smaller amounts compared to non-fraudulent transactions.  
- **Feature Correlations**: Identified features that are strongly correlated with fraudulent transactions.  
- **Anomalies**: Detected outliers in transaction amounts, requiring further investigation or preprocessing.  

---


 Install dependencies:  

   ```bash  
   pip install pandas numpy matplotlib seaborn scikit-learn kagglehub  
   ```  

3. Download the dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud):  

   ```python  
   import kagglehub  

   # Download latest version
   path = kagglehub.dataset_download("mlg-ulb/creditcardfraud")

   print("Path to dataset files:", path)  
   ```  

---

## Usage  

1. Open the Jupyter Notebook:  

   ```bash  
   jupyter notebook EDA_Credit_Card_Fraud_Detection.ipynb  
   ```  

2. Follow the notebook to:  
   - Clean and preprocess the data.  
   - Perform exploratory data analysis (EDA).  
   - Visualize data trends and patterns.  

---

## Deliverables  

1. **Jupyter Notebook**: Full implementation of data preprocessing, analysis, and visualization.  
2. **Report**:  
   - Summary of insights from EDA.  
   - Visualizations of key findings.  
