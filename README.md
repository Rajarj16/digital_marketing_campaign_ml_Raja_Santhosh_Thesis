# 📊 Digital Marketing Campaign Engagement Prediction

### Machine Learning Analysis (Master’s Thesis)

---

## 📌 Project Overview

This repository contains the **machine learning implementation** developed as part of the Master’s Thesis:

**“Analyzing Digital Marketing Campaign Performance Using Data-Driven Analytics and Machine Learning.”**

The project investigates whether **social media campaign engagement rates** can be analysed and predicted using historical digital marketing data.
All analysis, modelling, and visualisation are performed **entirely in Python using a Jupyter Notebook**.

The aim of this work is to demonstrate a **data-driven, predictive analytics workflow** suitable for academic research in digital marketing analytics.

---

## 🎯 Research Objectives

* Analyse historical digital marketing campaign data
* Predict **engagement rate** using machine learning models
* Compare baseline, linear, and non-linear models
* Evaluate model performance and limitations
* Generate analytical and diagnostic visualisations to support findings

---

## 📂 Dataset

**Social Media Engagement Dataset**
Source: Kaggle – Social Media / Digital Marketing Engagement Dataset

* File used in this project:
  `social_media_engagement_data_cleaned.csv`
* The dataset contains campaign, platform, sentiment, and engagement-related features
* Data is provided in cleaned form and loaded directly into the notebook

---

## 🧠 Machine Learning Approach

### Models Implemented

* **Baseline Model:** Dummy Regressor (mean strategy)
* **Linear Model:** Ridge Regression
* **Non-Linear Models:**

  * Random Forest Regressor
  * Gradient Boosting Regressor

Models are evaluated to assess **predictive feasibility** rather than to produce deterministic forecasts.

---

## ⚙️ Methodology

### Data Preprocessing

* Handling missing values using **SimpleImputer**
* Feature scaling using **StandardScaler**
* Encoding categorical variables using **OneHotEncoder**
* End-to-end preprocessing using **Pipeline** and **ColumnTransformer**

### Target Variable

* `engagement_rate`
* Normalised to a **0–1 range** prior to model training

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Cross-validation and hyperparameter tuning are applied to demonstrate **pipeline improvement attempts**.

---

## 📊 Machine Learning Outputs

All results and figures are generated **directly within the notebook** when executed.

Key outputs include:

* Feature distribution analysis
* Correlation analysis
* Sentiment and emotion-based engagement analysis
* Model performance comparison
* Actual vs predicted engagement rate plots
* Regression diagnostics
* Exploratory feature importance analysis

These figures support the **Results and Discussion** section of the thesis.

---

## 🗂️ Repository Structure

```
├── digital_marketing_campaign_ml_Raja_Santhosh.ipynb   # Machine learning implementation
├── social_media_engagement_data_cleaned.csv            # Dataset used for analysis
├── README.md                                           # Project documentation
```

---

## 🛠️ Requirements

* Python 3.8+
* Jupyter Notebook or Google Colab

### Key Libraries

* numpy
* pandas
* scikit-learn
* matplotlib
* seaborn

---

## ▶️ Steps to Run the Project

### 1. Clone this repository

```bash
git clone https://github.com/Rajarj16/digital_marketing_campaign_ml_Raja_Santhosh_Thesis.git
cd digital_marketing_campaign_ml_Raja_Santhosh_Thesis
```

---

### 2. Open the notebook

```bash
jupyter notebook digital_marketing_campaign_ml_Raja_Santhosh.ipynb
```

---

### 3. Run the notebook

* Run all cells **sequentially from top to bottom**
* The notebook will:

  * Load and preprocess the dataset
  * Train and evaluate multiple ML models
  * Generate analytical and diagnostic visualisations

> All figures are produced dynamically within the notebook.

---

## 📈 Key Findings (Summary)

* Engagement-rate prediction is challenging due to behavioural variability
* Non-linear models outperform linear baselines on this dataset
* Predictive analytics can support **decision-making**, but not exact forecasting
* Model diagnostics highlight limitations and assumptions of regression-based approaches

---

## 🔒 Ethical Considerations

* Dataset does not contain personally identifiable information (PII)
* Data is used strictly for academic research purposes
* Analysis complies with academic integrity requirements

---

## 🚀 Future Work

* Incorporate richer feature engineering
* Explore time-series based engagement prediction
* Evaluate deployment-oriented machine learning pipelines

---

## 👤 Author

**Raja Ramaraj and Santhosh Selvan**
Master’s Thesis – Digital Marketing Analytics / Data Analytics

---
