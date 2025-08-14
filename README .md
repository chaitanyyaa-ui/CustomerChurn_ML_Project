# Customer Churn Analysis

This project focuses on analyzing telecom customer data to identify patterns and factors contributing to customer churn. 
The notebook demonstrates **data manipulation, filtering, and exploratory data analysis (EDA)** using Python in **Google Colab**.

## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses. 
This analysis helps uncover patterns in customer demographics, account information, and payment behavior that may lead to churn.

## 📊 Key Features
- **Platform:** Google Colab (cloud-based Jupyter environment)
- **Data Source:** `customer_churn.csv` containing customer demographics, account details, and churn status.
- **Libraries Used:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Data Manipulations:**
  - Extracted **senior male citizens** paying via electronic check.
  - Filtered customers with **tenure > 70 months** or **monthly charges > $100**.
  - Isolated customers with **two-year contracts**, payment via mailed check, and churn status **"Yes"**.
  - Random sampling of 333 records for deeper analysis.

## Dashboard
<img width="1376" height="764" alt="image" src="https://github.com/user-attachments/assets/a9b04e8c-430d-4dc5-a2c5-94c5b9be51de" />



## 🎯 Analysis Goals
- Identify customer segments with higher churn risk.
- Understand the relationship between contract type, payment method, and churn rate.
- Provide actionable insights to improve customer retention.

## ⚙️ How to Run in Google Colab
1. Open the notebook in Google Colab:
   - Click this badge once the repo is uploaded:  
     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/Customer-Churn-Analysis/blob/main/Customer_Churn_Analysis.ipynb)
2. Upload the dataset `customer_churn.csv` to the Colab environment when prompted.
3. Run the notebook cells sequentially to reproduce the analysis.

## 🚀 Potential Improvements
- Implement **predictive modeling** for churn classification.
- Enhance **data visualizations** for better storytelling.
- Integrate with **Power BI/Tableau** for interactive dashboards.

## 🏆 Author
**Chaitanya Manoj Bhagat**  
Data Analyst | Python | SQL | Machine Learning | Generative AI
