# 🎯 Student Data Opportunity Analysis

## 📖 Overview

This project analyzes **user engagement** and **opportunity participation** on **Excelerate**, a platform designed to connect learners with skill-building opportunities.

Over **27,000+ user records** and **20,000+ opportunity records** were processed using **Python for data cleaning, AI for predictive modeling, and Power BI for interactive dashboards**.

The result? A **99% accurate ML model** for predicting opportunity categories, combined with rich dashboards that empower stakeholders to optimize **engagement, rewards, and participation**.

---

## 🥅 Key Objectives

✔️ **Data Cleaning & Validation** – Ensure integrity by fixing missing values, duplicates, and outliers
✔️ **AI Model Training** – Predict opportunity categories and analyze engagement patterns
✔️ **Dashboard Creation** – Build interactive Power BI dashboards for real-time insights
✔️ **Actionable Insights** – Provide data-driven recommendations for retention & participation

---

## 📂 Dataset Details

### 👤 User Data

* **Records**: 27,000+
* **Attributes**: demographics, location (city, country, zip code), sponsorship preferences, engagement metrics

### 🎓 Opportunity Data

* **Records**: 20,000+
* **Attributes**: participation rates, rewards, skill points, completion metrics

---

## 🔬 Methodology

### 1️⃣ Data Cleaning & Validation

* 🧹 **Missing Data** → Imputed with default values ("no") or dropped irrelevant entries
* 📏 **Outliers** → Removed using z-score thresholds (z > 3 or < -3)
* 🔄 **Normalization & Encoding** → Standardized numericals + one-hot encoding for categorical data
* 🗑️ **Duplicates** → Eliminated duplicate rows for accuracy

### 2️⃣ AI Model Training

* 🎯 **Objective**: Predict opportunity categories
* 🤖 **Algorithms Tested**:

  * Random Forest → 🏆 **Best model with 99% accuracy**
  * Logistic Regression → Effective for binary engagement classification
* ⭐ **Key Predictors**: Skill points, gender, country, critical thinking score
* 📊 **Evaluation Metrics**: Precision, Recall, F1-score, Confusion Matrix

### 3️⃣ Dashboard Creation

Built in **Power BI** with data preprocessed in Python:

* **User Dashboard** → demographics, sign-up trends, geo-distribution
* **Opportunity Dashboard 1** → completion rates, rewards, student participation
* **Opportunity Dashboard 2** → geographic reach, opportunity performance, reward flow

---

## 💡 Key Insights

### 👤 User Engagement

* 🌍 **Top Countries**: India (7.7k), Nigeria (2.8k), USA (0.9k)
* ⚖️ **Gender Split**: 61.56% male vs. 38.44% female
* 🎓 **Education**: Majority = undergrad (6.5k) + graduate (6.0k) students

### 🎓 Opportunities

* 📉 **Completion Rates**: Dropped from **33% (Jan 2023)** to **8% (Oct 2023)**
* 🏆 **Most Popular**: DIFI AI L (5.7k participants)
* 💰 **Reward Leaders**: India (\$1.5M), USA, Malaysia

---

## 🛠 Tools & Technologies

* **Languages**: Python (`Pandas`, `NumPy`, `Scikit-learn`)
* **Visualization**: Power BI
* **Machine Learning**: Random Forest, Logistic Regression
* **Data Processing**: Outlier detection, one-hot encoding, normalization

---

## 📁 Repository Structure

```plaintext
excelerate-data-analysis/
├── Week 1/
│   ├── Opportunity Wise Data.csv
│   ├── UserData(2).csv
│   ├── Week 1 Code.ipynb
│   └── Week 1 Report.pdf
├── Week 2/
│   ├── opportunity_info.csv
│   ├── user_data.csv
│   ├── Week 2 Code.ipynb
│   └── Week 2 Report.pdf
├── Week 3/
│   ├── opportunity_info_week2.csv
│   ├── user_data_week2.csv
│   ├── Week 3 Code.ipynb
│   └── Week 3 Report.pdf
├── Week 4/
│   ├── Dashboard.pbix
│   ├── opportunity_info_week3.csv
│   ├── user_data_week3.csv
│   └── Week 4 Code.ipynb
```

---

## 👥 Team Members

* **Team Lead**: Abdullah Imran ([@poetabdullah](https://github.com/poetabdullah))
* **Team Members**:

  * Akshaya Cheruku
  * Nwabueze Victor
  * Chirag Pawaskar
  * Omootemi Modupe

---

## 🚀 Conclusion

This project demonstrates how **clean data + machine learning + dashboards** can:

* ✅ Predict opportunities with **99% accuracy**
* ✅ Track and optimize **student engagement**
* ✅ Provide **actionable insights** for stakeholders

> With these insights, Excelerate can strategically improve **user retention**, **reward allocation**, and **completion rates**—helping learners maximize their growth potential.
