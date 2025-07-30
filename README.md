[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-2-Airbnb-Data-Preparation/blob/main/notebooks/Lab2.ipynb)

# Lab 2: Data Understanding and Preparation

This lab focuses on the second and third stages of the machine learning life cycle: data understanding and data preparation.  
Using the Airbnb NYC listings dataset, we practice transforming the data to prepare it for regression modeling.

---

## Dataset Used

| Dataset | Description |
|---------|-------------|
| **Airbnb Listings NYC (Dec 2021)** | The same modified NYC Airbnb listings dataset used in Lab 1, focusing on feature transformation and cleaning. |

---

## Objectives

- Load and inspect the Airbnb dataset  
- Define the regression label and convert its data type  
- Identify features for modeling  
- Handle outliers by winsorizing the label  
- Handle missing data with mean imputation  
- Apply one-hot encoding to categorical features  
- Explore feature-label correlations with bivariate plots  
- Analyze relationships and brainstorm next steps for modeling  

---

## Methodology

The following steps were performed:

- Data loading and inspection  
- Label definition and type conversion  
- Outlier handling through winsorization  
- Missing value imputation with mean values  
- Feature transformation using one-hot encoding  
- Correlation analysis and visualization of key features  

---

## Key Findings and Next Steps

- Winsorization helped reduce label outlier impact for better model stability  
- Mean imputation effectively handled missing data without drastic bias  
- Top correlated features were [Feature1] and [Feature2] (update with your actual findings)  
- Further feature engineering and scaling will be required before modeling  

---

## Setup Instructions

### Option 1: Open in Google Colab  
Click the badge above.

### Option 2: Run Locally  
```bash
git clone https://github.com/rileybarka/Lab-2-Airbnb-Data-Preparation.git
cd Lab-2-Airbnb-Data-Preparation/notebooks
jupyter notebook Lab2_Data_Preparation.ipynb

