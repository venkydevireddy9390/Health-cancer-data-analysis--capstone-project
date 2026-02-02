# 🏥 Healthcare Cancer Data Analysis – Capstone Project

## 📌 Project Overview

This capstone project focuses on **data preprocessing, feature engineering, and exploratory data analysis (EDA)** using a healthcare cancer dataset. The goal of the project is to clean the data, understand patterns and trends related to cancer patients, and prepare a high-quality dataset for future machine learning or predictive analysis.

---

## 📂 Dataset Used

**Dataset Name:** Global Cancer Patients Dataset (2015–2024)

**File Name:** `global_cancer_patients_2015_2024.csv`

**Description:**
The dataset contains patient-level information related to cancer, including:

* Patient demographics (Age, Gender, Country/Region)
* Lifestyle factors (Smoking, Alcohol Use, Air Pollution, Obesity Level)
* Medical information (Cancer Type, Cancer Stage, Genetic Risk)
* Treatment details (Treatment Cost)
* Outcome-related features (Survival Years, Target Severity Score)

This dataset was used to perform real-world healthcare data analysis tasks.

---

## 🛠️ Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Project Workflow (Step-by-Step)

### 1️⃣ Import Required Libraries

Essential Python libraries were imported for data manipulation, visualization, and preprocessing.

### 2️⃣ Data Loading

The cancer dataset was loaded into a Pandas DataFrame using `read_csv()`.

### 3️⃣ Understanding the Dataset

* Displayed column names
* Checked dataset shape
* Reviewed data types and basic structure using `info()`
* Generated statistical summaries using `describe()`

### 4️⃣ Missing Value Analysis

* Identified missing values using `isnull().sum()`
* Separated numerical and categorical columns

### 5️⃣ Handling Missing Values

* **Numerical Features:** Missing values were replaced using the **mean** strategy with `SimpleImputer`
* **Categorical Features:** Missing values were replaced using the **most frequent** strategy

### 6️⃣ Duplicate Records Check

* Checked for duplicate rows in the dataset
* Verified uniqueness of `Patient_ID`

### 7️⃣ Exploratory Data Analysis (EDA)

* Analyzed distributions of age, cancer types, and severity scores
* Visualized categorical and numerical features using bar charts, histograms, and box plots
* Identified patterns and trends related to cancer severity and patient characteristics

### 8️⃣ Data Readiness

After preprocessing and EDA, the dataset became clean, consistent, and ready for:

* Machine learning modeling
* Predictive analysis
* Healthcare insights generation

---

## 📊 Key Insights

* Cancer occurrence varies significantly across age groups and cancer types
* Lifestyle factors such as smoking and alcohol use show influence on severity scores
* Treatment costs and survival years differ across cancer stages

---

## ✅ Conclusion

This project demonstrates a complete data analysis pipeline starting from raw healthcare data to a cleaned and analyzed dataset. By applying data preprocessing, handling missing values, checking data integrity, and performing EDA, meaningful insights were extracted. The final dataset can be effectively used for advanced analytics and machine learning applications in the healthcare domain.

---

## 📌 Future Scope

* Build predictive models for cancer severity
* Perform feature scaling and encoding
* Apply machine learning and deep learning techniques
* Develop healthcare risk prediction systems

