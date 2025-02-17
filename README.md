## Overview  
This project focuses on analyzing user and opportunity-wise data for Excelerate, a platform aimed at enhancing user engagement and opportunity participation. The project involved **data cleaning, AI model training, and dashboard creation** to provide actionable insights for stakeholders. The team processed over **27,000 user records** and **20,000 opportunity records**, leveraging Python for data cleaning and Power BI for visualization.  

---

## Key Objectives  
1. **Data Cleaning & Validation**: Ensure data integrity by handling missing values, duplicates, and outliers.  
2. **AI Model Training**: Train machine learning models to predict opportunity categories and analyze user engagement patterns.  
3. **Dashboard Creation**: Develop interactive dashboards to visualize key metrics for stakeholders.  
4. **Actionable Insights**: Provide data-driven recommendations to improve user engagement, reduce churn, and optimize opportunity participation.  

---

## Dataset Details  
### 1. **User Data**  
- **Records**: 27,000+  
- **Attributes**: User demographics, sponsorship preferences, geographic data (city, country, zip code), and engagement metrics.  

### 2. **Opportunity Data**  
- **Records**: 20,000+  
- **Attributes**: Opportunity participation, reward amounts, skill points, and completion rates.  

---

## Methodology  
### 1. **Data Cleaning & Validation**  
- **Handling Missing Data**: Filled missing values with "no" or dropped irrelevant entries.  
- **Outlier Detection**: Removed outliers using z-score thresholds (z > 3 or z < -3).  
- **Data Normalization**: Normalized numerical data and applied one-hot encoding for categorical variables (e.g., gender, country).  
- **Duplicates**: Dropped duplicated records to ensure data accuracy.  

### 2. **AI Model Training**  
- **Objective**: Predict opportunity categories based on user engagement and demographic data.  
- **Algorithms Used**:  
  - **Random Forest**: Achieved **99% accuracy** in predicting opportunity categories.  
  - **Logistic Regression**: Tested for binary classification tasks.  
- **Key Features**: Skill points, gender, location, and critical thinking (top predictive feature).  
- **Evaluation Metrics**: Precision, recall, F1-score, and confusion matrix.  

### 3. **Dashboard Creation**  
- **Tools Used**: Power BI for visualization, Python for data preprocessing.  
- **Dashboards Created**:  
  - **User Data Dashboard**: Visualized user demographics, sign-up trends, and geographic distribution.  
  - **Opportunity Dashboard 1**: Analyzed opportunity completion rates, reward distribution, and student demographics.  
  - **Opportunity Dashboard 2**: Focused on geographic reach, opportunity performance, and reward structure.  

---

## Key Insights  
1. **User Data Insights**:  
   - **Top Countries**: India (7.7K users), Nigeria (2.8K), and the United States (0.9K).  
   - **Gender Distribution**: 61.56% male, 38.44% female.  
   - **Education Background**: Majority are undergraduate (6.5K) and graduate students (6.0K).  

2. **Opportunity Data Insights**:  
   - **Completion Rates**: Peaked at 33% in early 2023 but declined to 8% by October 2023.  
   - **Top Opportunity**: DIFI AI L (5.7K participants).  
   - **Reward Distribution**: India received the highest rewards (1.5M), followed by the United States and Malaysia.  

---

## Tools & Technologies  
- **Programming Languages**: Python (Pandas, NumPy, Scikit-learn)  
- **Visualization Tools**: Power BI  
- **Machine Learning**: Random Forest, Logistic Regression  
- **Data Cleaning**: Handling missing values, outlier detection, one-hot encoding  

---

## Repository Structure  
The repository is organized into four weekly folders, each containing reports, updated datasets, and code. The final week also includes the presentation and dashboards.  

```
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

## Team Members  
- **Team Lead**: [Abdullah Imran (Me)]  
- **Members**:
  - Akshaya Cheruku  
  - Nwabueze Victor  
  - Chirag Pawaskar  
  - Omootemi Modupe  
