# Credit Risk Scorecard – End-to-End PD Modeling Project

## 📌 Project Overview

This repository contains an **end-to-end Credit Risk Scorecard project** that transforms raw customer-level data to a **deployment-ready Probability of Default (PD) scorecard**. The project follows **industry-standard scorecard development practices** used by banks and NBFCs and is intentionally designed to be **interview-ready for entry-level / fresher credit risk roles**.

The complete workflow is implemented across **8 structured Jupyter notebooks**, each representing a logical stage of the credit risk modeling lifecycle.

---

## 🧠 Key Concepts Covered

* Credit Risk Fundamentals (PD modeling)
* Data Cleaning & Feature Engineering
* Vintage Analysis & Sampling
* Variable Segmentation (Binning)
* WOE & IV based Variable Reduction
* Logistic Regression Scorecard Model
* Score Calibration & Scaling
* Model Validation (AUC, KS, Stability)

---

## 📂 Project Structure & Workflow

### **1️⃣ Merging & Raw Data Preparation**

**Notebook:** `1_Merging_Data.ipynb`

**Objective:**

* Merge multiple raw data sources into a single modeling dataset
* Perform initial sanity checks

**Key Steps:**

* Dataset joins / merges
* Basic data validation
* Removal of obvious inconsistencies

📌 *This step ensures a clean and unified base table for downstream analysis.*

---

### **2️⃣ Vintage Analysis & Sampling**

**Notebook:** `2_VintageAnalysis&Sampling.ipynb`

**Objective:**

* Understand portfolio performance over time
* Create a stable modeling sample

**Key Steps:**

* Vintage-level default trend analysis
* Identification of bad-rate stability
* Train/test sampling strategy

📌 *Vintage analysis is critical to ensure time-consistent PD modeling.*

---

### **3️⃣ Data Preparation**

**Notebook:** `3_Data_Prepration.ipynb`

**Objective:**

* Clean and prepare variables for segmentation and modeling

**Key Steps:**

* Missing value treatment
* Outlier handling
* Data type corrections
* Leakage variable removal

📌 *Focus is on data quality and modeling reliability.*

---

### **4️⃣ Variable Segmentation (Binning)**

**Notebook:** `4_Segmentation.ipynb`

**Objective:**

* Convert raw variables into risk-meaningful bins

**Key Steps:**

* Numerical variable binning
* Categorical grouping
* Bad-rate trend analysis
* Ensuring monotonic risk behavior

📌 *Binning improves interpretability and scorecard stability.*

---

### **5️⃣ Variable Reduction using WOE & IV**

**Notebook:** `5_variable_reduction.ipynb`

**Objective:**

* Select the most predictive and stable variables

**Key Steps:**

* WOE (Weight of Evidence) calculation
* IV (Information Value) computation
* Removal of weak and redundant variables

📌 *This step transforms raw features into model-ready predictors.*

---

### **6️⃣ Model Creation (PD Model)**

**Notebook:** `6_Model_Creation.ipynb`

**Objective:**

* Build the Probability of Default model

**Key Steps:**

* Logistic Regression model training
* Coefficient interpretation
* Initial performance evaluation

📌 *Logistic regression is used due to its regulatory acceptance and interpretability.*

---

### **7️⃣ Score Calibration & Scaling**

**Notebook:** `7_score_calibration.ipynb`

**Objective:**

* Convert the PD model into a business-ready scorecard

**Key Steps:**

* PD calibration
* Score scaling (PDO, base score, base odds)
* Customer-level score generation

📌 *This step bridges analytics and business decision-making.*

---

### **8️⃣ Model Validation**

**Notebook:** `8_Model Validation.ipynb`

**Objective:**

* Validate model performance and robustness

**Key Metrics:**

* AUC / Gini
* KS Statistic
* Calibration assessment
* Model stability checks

📌 *Ensures the model is reliable, discriminatory, and production-ready.*

---

## 📊 Final Deliverables

* Probability of Default (PD) model
* Credit Risk Scorecard
* Interpretable risk drivers
* Model validation metrics
* Scoring-ready pipeline

---

## 🎯 Intended Audience

* Credit Risk Analyst (Fresher / Entry-level)
* Risk Analytics Interns
* Students' learning scorecard development

---

## 🗣️ How to Explain This Project in Interviews

> "I developed an end-to-end credit risk scorecard starting from raw data merging and vintage analysis, performed variable binning and WOE-IV based feature selection, built a logistic regression PD model, calibrated and scaled it into a scorecard, and validated it using AUC, KS, and calibration metrics."

---

## 🚀 Future Enhancements

* Roll-rate analysis
* 30+/60+/90+ DPD tracking
* Early Warning Indicators (EWS)
* Population Stability Index (PSI)

---

## 📌 Author

**Chirag Sadhwani**
Aspiring Credit Risk Analyst | Data Science & Risk Analytics

---

⭐ *If you find this project useful, feel free to star the repository.*
