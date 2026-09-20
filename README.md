# 🏥 Healthcare Analytics for Doctor Visits

## 📌 Project Overview

Healthcare data contains valuable information about people's health conditions, demographic characteristics, healthcare access, and healthcare utilization.

However, raw healthcare data does not immediately reveal the patterns behind doctor visits.

This project focuses on the question:

> **"What factors are associated with doctor visits?"**

Using Python-based data analytics, this project explores relationships between doctor visits and factors such as age, gender, income, illness, reduced activity, health condition, healthcare access, and chronic conditions.

The project follows a storytelling approach:

**Raw Data → Data Preparation → Exploration → Health Analysis → Healthcare Access → Statistical Analysis → Insights**

---

## 🎯 Problem Statement

Doctor visits can vary across individuals depending on demographic characteristics, health conditions, and healthcare access.

The challenge is to transform raw healthcare records into meaningful insights that help identify patterns associated with doctor visits.

This project analyzes the available healthcare data to understand:

- Doctor visit patterns
- Demographic differences
- Illness and reduced activity
- Health conditions
- Chronic conditions
- Healthcare access indicators
- Statistical relationships with doctor visits

---

## 🎯 Objectives

The main objectives of this project are:

1. Understand the structure and quality of the healthcare dataset.
2. Analyze the distribution of doctor visits.
3. Explore demographic factors such as age and gender.
4. Examine the relationship between illness and doctor visits.
5. Study reduced activity and healthcare utilization.
6. Analyze chronic-condition indicators.
7. Explore healthcare-access variables.
8. Examine the relationship between income and doctor visits.
9. Apply statistical techniques to identify important associations.
10. Present the findings through clear visualizations and insights.

---

## 📊 Dataset

The dataset contains **5,190 records** and **13 original variables**.

### Main Variables

| Variable | Description |
|---|---|
| `visits` | Number of reported doctor visits |
| `gender` | Gender of the individual |
| `age` | Recorded age value |
| `income` | Recorded income value |
| `illness` | Reported illness level |
| `reduced` | Reduced activity measure |
| `health` | Recorded health value |
| `private` | Private healthcare indicator |
| `freepoor` | Free healthcare indicator |
| `freerepat` | Free/repatriation healthcare indicator |
| `nchronic` | Chronic-condition indicator |
| `lchronic` | Long-term chronic-condition indicator |
| `Unnamed: 0` | Index-like record identifier |

The `Unnamed: 0` column is treated as an index-like identifier and is removed before analysis.

---

## 🔍 Analytical Questions

The project is structured around the following questions:

### 1. What does the doctor-visit distribution look like?

Understanding the overall distribution of visits provides the starting point for the analysis.

### 2. Does age relate to doctor visits?

The recorded age values are examined to identify differences and statistical associations with visits.

### 3. Does illness relate to doctor visits?

The analysis examines whether different illness levels are associated with different visit counts.

### 4. Does reduced activity relate to doctor visits?

Reduced activity is analyzed as a health-related factor associated with healthcare utilization.

### 5. What about the health variable?

The relationship between the recorded health variable and doctor visits is examined.

### 6. Are there differences by gender?

Average and distributional differences in doctor visits are explored across gender groups.

### 7. Do chronic conditions relate to visits?

The `nchronic` and `lchronic` indicators are analyzed against doctor visits.

### 8. Does healthcare access show different patterns?

The variables `private`, `freepoor`, and `freerepat` are compared with doctor visits.

### 9. Is income related to doctor visits?

The statistical association between income and doctor visits is examined.

### 10. Which numerical factors show stronger associations?

Spearman correlation is used to compare the relationships between numerical variables and doctor visits.

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**

### Techniques Used

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Group-Based Analysis
- Data Visualization
- Spearman Correlation
- Mann-Whitney U Test
- Statistical Interpretation

---

## 📈 Data Analysis Workflow

                 Healthcare Dataset
                         ↓
                  Data Understanding
                         ↓
                   Data Cleaning
                         ↓
              Exploratory Data Analysis
                         ↓
              Demographic Analysis
                         ↓
                Health Analysis
                         ↓
           Chronic Condition Analysis
                         ↓
            Healthcare Access Analysis
                         ↓
              Statistical Analysis
                         ↓
                  Visualization
                         ↓
                  Key Insights
                         ↓
                    Conclusion

## 📊 Key Analytical Findings

The analysis identified the following patterns in the healthcare dataset:

- Doctor visits are concentrated around lower visit counts.
- Reduced activity shows a positive association with doctor visits.
- Illness shows a positive association with doctor visits.
- The recorded health variable shows a positive association with visits.
- Age shows a positive statistical association with doctor visits.
- Income shows a weak negative association with visits.
- Differences are observed across gender groups.
- Chronic-condition and healthcare-access indicators show different visit patterns across their respective categories.

### Spearman Associations with Doctor Visits

| Variable | Spearman Correlation |
|---|---:|
| Reduced Activity | **0.336** |
| Illness | **0.263** |
| Health | **0.178** |
| Age | **0.148** |
| Income | **-0.093** |

> **Note:** These values represent statistical associations observed in this dataset. They do not establish causal relationships or provide individual medical conclusions.

---

## 💡 Key Insights

### 🏥 Health-Related Factors

Reduced activity and illness show notable positive associations with doctor visits.

### 👥 Demographic Factors

Age and gender show observable differences in doctor-visit patterns.

### 🩺 Chronic Conditions

Chronic-condition indicators provide additional information for understanding healthcare utilization.

### 🏨 Healthcare Access

Healthcare-access variables show different visit patterns across their respective categories.

### 📈 Statistical Analysis

Spearman correlation was used to compare the strength and direction of relationships between numerical variables and doctor visits.

The Mann-Whitney U test was also used to examine differences between gender groups.

---

## 👥 Potential End Users

This project can be useful for:

- Healthcare Providers
- Healthcare Administrators
- Healthcare Researchers
- Data Analysts
- Healthcare Planning Teams
- Students learning Healthcare Analytics

The results can support exploratory analysis and healthcare-utilization research.

---

## 👩‍💻 Author

**Nisha R**  
B.Tech Artificial Intelligence and Data Science  
Ramco Institute of Technology
