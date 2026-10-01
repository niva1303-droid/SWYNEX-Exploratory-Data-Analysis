# SWYNEX-Internship

# 🏋️‍♂️ Gym Membership Dataset – Exploratory Data Analysis

## 📌 Project Overview

This project is an **Exploratory Data Analysis (EDA)** of the cleaned Gym Membership Dataset completed as part of my Data Analyst Internship.

The dataset used in this analysis is: **Gym Membership Dataset - Exploring Membership Trends**

The objective of this project was to explore member demographics, membership patterns, gym attendance, service usage, and workout behavior using descriptive statistics and data visualizations.

The analysis was performed using **Python, Pandas, and Matplotlib in Google Colab**.

---

## 📓 Dataset Overview

The cleaned dataset contains:

* **1,000 gym members**
* **17 original attributes**
* No missing values
* No duplicate records
* Standardized categorical values

The dataset includes information related to:

* Age and gender
* Membership type
* Weekly gym visits
* Average time spent in the gym
* Group lesson participation
* Personal training
* Sauna usage
* Favorite group lessons and drinks
* Average check-in and check-out times

An additional **Age Group** feature was created during EDA to support demographic analysis.

---

## 🧰 Tools & Technologies

* Python
* Pandas
* Matplotlib
* Google Colab
* Microsoft Excel

---

## 📚 Exploratory Data Analysis

### 1. Descriptive Statistics

Summary statistics were calculated for:

* Age
* Weekly gym visits
* Average time spent in the gym

Key statistics:

* **Average Age:** 30.60 years
* **Median Age:** 30 years
* **Average Weekly Visits:** 2.68
* **Average Time in Gym:** 105.26 minutes
* **Minimum Age:** 12 years
* **Maximum Age:** 49 years

---

### 2. Membership Type Distribution

Membership distribution was analyzed using a bar chart.

* Standard: **507 members (50.7%)**
* Premium: **493 members (49.3%)**

The two membership types are almost evenly distributed.

---

### 3. Age Distribution

A histogram was used to understand the age distribution of gym members.

Members were also grouped into the following categories:

| Age Group | Percentage |
| --------- | ---------: |
| Under 18  |      14.5% |
| 18–25     |      21.5% |
| 26–35     |      26.8% |
| 36–45     |      27.0% |
| 46+       |      10.2% |

Members aged **26–45 account for 53.8%** of the dataset.

---

### 4. Membership Type vs Average Weekly Visits

Average weekly gym visits were compared across membership types.

* Premium: **2.684 visits/week**
* Standard: **2.680 visits/week**

Weekly visit frequency is nearly identical between Premium and Standard members.

---

### 5. Membership Type vs Average Time in Gym

Average workout duration was compared between membership types.

* Standard: **105.60 minutes**
* Premium: **104.91 minutes**

The difference is less than one minute, indicating very similar workout durations across the two membership types.

---

### 6. Additional Service Usage

The analysis examined participation in additional gym services.

* Personal Training: **51.8%**
* Group Lessons: **50.3%**
* Sauna: **49.3%**

Usage of all three services is relatively balanced.

---

### 7. Age vs Average Time in Gym

A scatter plot and Pearson correlation were used to examine the relationship between age and average time spent in the gym.

**Correlation: -0.041**

The correlation is very close to zero, indicating virtually no linear relationship between age and workout duration in this dataset.

---

## Anomaly / Outlier Analysis

Boxplots and the **Interquartile Range (IQR) method** were used to identify potential numerical outliers.

### Results

* **Age:** 0 outliers
* **Average Time in Gym:** 0 outliers
* **Weekly Visits:** 124 statistical outliers

For weekly visits, the calculated IQR upper bound was **4.5 visits per week**. Members visiting the gym **5 times per week** were therefore statistically classified as outliers.

However, five gym visits per week is a realistic attendance pattern. Therefore, these observations were retained and were not treated as data-quality errors.

This demonstrates the importance of applying **domain reasoning alongside statistical outlier detection**.

---

## Key Insights

1. **Balanced Membership Mix:** Standard members represent 50.7% of the dataset and Premium members represent 49.3%.

2. **Similar Visit Frequency:** Premium and Standard members average approximately 2.68 visits per week, showing almost no difference between membership types.

3. **Similar Workout Duration:** Standard members average 105.60 minutes in the gym compared with 104.91 minutes for Premium members.

4. **Balanced Service Usage:** Personal training, group lessons, and sauna usage are all close to 50%.

5. **Largest Age Segment:** Members aged 26–45 represent 53.8% of all members.

6. **Age vs Gym Duration:** The correlation of -0.041 indicates virtually no linear association between age and average time spent in the gym.

---

## 📊💹 Visualizations

The project includes:

* Membership Type Distribution – Bar Chart
* Age Distribution – Histogram
* Membership Type vs Average Weekly Visits – Bar Chart
* Membership Type vs Average Time in Gym – Bar Chart
* Additional Service Usage – Bar Chart
* Age vs Average Time in Gym – Scatter Plot
* Age Outlier Detection – Boxplot
* Weekly Visits Outlier Detection – Boxplot
* Average Gym Time Outlier Detection – Boxplot

---

## ∴ Conclusion

The exploratory data analysis identified useful patterns in member demographics, membership types, gym attendance, service usage, and workout behavior.

Standard and Premium memberships showed very similar attendance and workout-duration patterns. Members aged 26–45 formed the largest demographic segment, while additional gym services showed relatively balanced participation.

The analysis also demonstrated that statistical outliers should be interpreted within the context of the data. Although members visiting five times per week were identified as IQR outliers, these observations represented realistic gym behavior and were therefore retained.

Overall, this project strengthened my practical understanding of **Exploratory Data Analysis, descriptive statistics, data visualization, correlation analysis, outlier detection, and data-driven interpretation using Python**.
