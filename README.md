---

# 📊 Digital Marketing Campaign Performance Analysis

### Machine Learning–Based Predictive Analytics (Master’s Thesis)

---

## 📌 Project Overview

This repository contains the **machine learning analysis** conducted as part of the Master’s thesis:

**“Analyzing Digital Marketing Campaign Performance Using Data-Driven Analytics and Machine Learning.”**

The study investigates whether **social media campaign engagement rates** can be modelled using historical campaign data and machine learning techniques.
Rather than producing deterministic forecasts, the work focuses on **evaluating predictive feasibility**, **understanding limitations**, and **supporting data-driven decision-making** in digital marketing contexts.

All analysis, modelling, and visualisation are implemented in **Python using a Jupyter Notebook**.

---

## 🎯 Research Objectives

The primary objectives of this study are:

* To analyse patterns and drivers of social media engagement across digital marketing campaigns
* To evaluate whether engagement rate can be predicted using machine learning models
* To compare baseline regression models with more advanced ensemble approaches
* To assess model performance using standard evaluation metrics (R², RMSE, MAE)
* To interpret predictive results cautiously within a **decision-support framework**

---

## 🧠 Machine Learning Methodology

### Models Implemented

The notebook evaluates multiple regression-based models, including:

* Linear Regression (baseline)
* Ridge Regression
* Lasso Regression
* Random Forest Regressor
* Gradient Boosting Regressor

Model selection and comparison are used to assess **relative performance**, not to claim algorithmic novelty.

---

## ⚙️ Data Processing & Evaluation

Key methodological steps include:

* Exploratory Data Analysis (EDA)
* Feature engineering based on marketing theory (e.g., interaction and intensity measures)
* Handling missing values and categorical variables
* Feature scaling and multicollinearity checks
* Model evaluation using:

  * R² Score
  * Root Mean Squared Error (RMSE)
  * Mean Absolute Error (MAE)
* Cross-validation and hyperparameter tuning for model refinement

---

## 📊 Key Findings

The main findings of the study are:

* Social media engagement exhibits **high variability and non-linear behaviour**
* Baseline linear models show limited explanatory power
* Ensemble models (particularly Random Forest) perform better in capturing interaction effects
* Even high-performing models must be interpreted cautiously due to data noise and behavioural uncertainty
* Predictive models are more suitable for **relative comparison and decision support** than precise forecasting

---

## 🗂️ Repository Structure

```
├── digital_marketing_campaign_ml_Raja_Santhosh_Thesis.ipynb
│   └── Complete machine learning analysis and visual outputs
│
├── Social Media Engagement Dataset.csv
│   └── Dataset used for the study
│
├── README.md
│   └── Project documentation
```

---

## 📂 Dataset Information

* **Dataset Name:** Social Media Engagement Dataset
* **Source:** Kaggle
* **Description:**
  The dataset contains synthetic yet realistic records of social media posts across multiple platforms, campaign phases, sentiment types, and engagement metrics. It is designed to support exploratory and predictive analysis in digital marketing research.

---

## 🛠️ Python Libraries Used

The analysis uses the following Python libraries:

```
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
statsmodels
```

These libraries support data manipulation, modelling, statistical diagnostics, and visualisation.

---

## ▶️ How to Run the Analysis

1. Clone the repository:

```bash
git clone https://github.com/Rajarj16/digital_marketing_campaign_ml_Raja_Santhosh_Thesis.git
cd digital_marketing_campaign_ml_Raja_Santhosh_Thesis
```

2. Open the notebook:

```bash
jupyter notebook digital_marketing_campaign_ml_Raja_Santhosh_Thesis.ipynb
```

3. Run all cells sequentially to reproduce the analysis and figures.

---

## 🚀 Future Enhancements

Consistent with the thesis discussion, potential future work includes:

* Validation using real-world social media data
* Time-based modelling of engagement trends
* Exploration of additional non-linear models
* Integration of text-based features from post content
* Further analysis of platform-specific behavioural effects

---

## 🔒 Ethical Considerations

* The dataset is publicly available and synthetic
* No personally identifiable information (PII) is included
* The analysis is conducted solely for academic research purposes

---

## 👤 Authors

**Raja Ramaraj**

**Santhosh Selvan**

Master’s Thesis
MSc Data Science / Digital Analytics

---
