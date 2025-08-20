# 💡 Insurance Cost Analysis

This project analyzes an **insurance dataset** to explore factors affecting healthcare costs and to build predictive models for insurance charges.  
The workflow includes **data wrangling, exploratory data analysis (EDA), and machine learning models** (Linear & Ridge Regression).

---

## 📂 Dataset Overview
The dataset includes the following attributes:

| Parameter        | Description                                | Type        |
|------------------|--------------------------------------------|-------------|
| age              | Age in years                               | Integer     |
| gender           | Male or Female (encoded)                   | Integer     |
| bmi              | Body mass index                            | Float       |
| no_of_children   | Number of children                         | Integer     |
| smoker           | Smoking status (0 = No, 1 = Yes)           | Integer     |
| region           | U.S. region (NW, NE, SW, SE → 1–4)         | Integer     |
| charges          | Annual insurance charges (USD)             | Float       |

---

## 🎯 Objectives
- ✅ Load and clean the dataset (handle missing values, fix datatypes, normalize fields).  
- ✅ Perform **exploratory data analysis** (EDA) to identify key cost-driving factors.  
- ✅ Build and evaluate **Linear Regression** models (single-variable & multi-variable).  
- ✅ Apply **Ridge Regression** for better generalization and reduced overfitting.  

---

## 🛠️ Project Workflow
1. **Data Wrangling**  
   - Handle missing entries (`NaN` values).  
   - Impute numerical features with mean, categorical with most frequent value.  
   - Adjust data formats and precision.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of age, BMI, charges, and categorical attributes.  
   - Correlation analysis between features and `charges`.  
   - Visualizations to compare smoking status, BMI, and region against costs.  

3. **Modeling**  
   - **Single-variable Linear Regression** → Predict charges based on one key factor.  
   - **Multi-variable Linear Regression** → Incorporate multiple features for improved accuracy.  
   - **Ridge Regression** → Regularization to refine performance and reduce variance.  

4. **Insights**  
   - Smoking has the strongest effect on charges.  
   - BMI and age also significantly influence costs.  
   - Ridge regression helps prevent overfitting compared to plain linear regression.  

