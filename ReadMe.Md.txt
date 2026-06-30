# Multiple Linear Regression – Multi-Channel Marketing Analysis

## 📌 Project Overview
This project applies **Multiple Linear Regression** to a marketing dataset containing spend across **TV, Radio, Social Media, and Influencer channels** to predict **Sales**.  
We use Python and **statsmodels** to build the model, check for multicollinearity, validate regression assumptions, and interpret coefficients for actionable business recommendations.

---

## 🎯 Goals
- Detect and address **multicollinearity** among predictors.  
- Fit a statistically robust **Multiple Linear Regression model**.  
- Justify variable inclusion/exclusion using **p-values** and **Adjusted R²**.  
- Validate regression assumptions with **residual diagnostics**.  
- Provide clear, business-ready recommendations for **marketing budget allocation**.

---

## 🗂 Dataset Description
- **TV**: Categorical (Low, Medium, High)  
- **Radio**: Numeric spend  
- **Social Media**: Numeric spend  
- **Influencer**: Categorical (Micro, Macro, Mega, Nano)  
- **Sales**: Numeric target variable  

---

## ⚙️ Environment Setup
Clone the repository and install dependencies:

```bash
git clone <your-repo-link>
cd <your-repo-folder>
pip install pandas seaborn statsmodels scipy matplotlib
