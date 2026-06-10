# CodeAlpha_Exploratory-Data-Analysis-EDA-

# 📊 Teen Mental Health Analysis

## Project Overview

This project analyzes a Teen Mental Health dataset to identify the factors influencing stress levels among teenagers. The analysis focuses on discovering trends, patterns, correlations, and potential anomalies while applying statistical techniques to validate hypotheses.

## Objective

* Analyze factors affecting teen stress levels.
* Identify trends and behavioral patterns.
* Perform statistical hypothesis testing.
* Detect anomalies and data quality issues.
* Generate actionable insights and recommendations.

## Dataset Information

The dataset contains information about teenagers, including:

* Age
* Gender
* Social Media Usage (Hours/Day)
* Sleep Duration
* Academic Performance
* Physical Activity
* Screen Time Before Sleep
* Social Interaction Level
* Preferred Social Media Platform
* Stress Level

## Data Cleaning

* No missing values detected.
* No duplicate records found.
* Data ranges were validated and found to be realistic.
* Dataset was ready for analysis without major preprocessing.

## Exploratory Data Analysis (EDA)

### Key Findings

### 1. Social Media Usage and Stress

A strong positive relationship was observed between social media usage and stress levels.

**Insight:** Teenagers spending more time on social media tend to experience higher stress.

### 2. Sleep Duration and Stress

A strong negative relationship exists between sleep duration and stress.

**Insight:** Teenagers who sleep longer generally report lower stress levels.

### 3. Academic Performance and Stress

Academic performance decreases as stress levels increase.

**Insight:** High stress negatively impacts academic achievement.

### 4. Physical Activity and Stress

Physical activity shows a moderate negative relationship with stress.

**Insight:** Active teenagers tend to have slightly lower stress levels.

## Statistical Analysis

### Hypothesis 1

**Null Hypothesis (H₀):** Social media usage has no impact on stress levels.

**Result:** Rejected

**Conclusion:** Social media usage significantly influences stress levels.

---

### Hypothesis 2

**Null Hypothesis (H₀):** Sleep duration has no impact on stress levels.

**Result:** Rejected

**Conclusion:** Sleep duration significantly affects stress levels.

---

### Hypothesis 3

**Null Hypothesis (H₀):** Gender has no impact on stress levels.

**Result:** Failed to Reject

**Conclusion:** No statistically significant difference in stress levels between genders.

---

### Hypothesis 4

**Null Hypothesis (H₀):** Preferred social media platform affects stress levels.

**Result:** Failed to Reject

**Conclusion:** Platform preference does not significantly impact stress.

## Anomaly Detection

### Observations

* Extremely strong correlations were observed between:

  * Social Media Usage and Stress
  * Academic Performance and Stress

### Potential Concern

These correlations are unusually high compared to real-world studies and may indicate:

* Synthetic data generation
* Sampling bias
* Feature dependency

## Visualizations Used

* Correlation Heatmap
* Scatter Plot: Social Media Usage vs Stress
* Scatter Plot: Sleep Hours vs Stress
* Box Plot: Gender vs Stress
* Histogram: Stress Distribution
* Bar Chart: Average Stress by Social Media Platform

## Key Insights

| Factor               | Relationship with Stress |
| -------------------- | ------------------------ |
| Social Media Usage   | Strong Positive          |
| Sleep Duration       | Strong Negative          |
| Academic Performance | Strong Negative          |
| Physical Activity    | Moderate Negative        |
| Gender               | No Significant Effect    |
| Platform Preference  | No Significant Effect    |

## Recommendations

### For Teenagers

* Limit excessive social media usage.
* Maintain 7–9 hours of sleep daily.
* Participate in regular physical activities.

### For Schools

* Conduct mental health awareness programs.
* Promote healthy digital habits.
* Provide counseling support for high-stress students.

### For Future Research

* Build predictive machine learning models for stress detection.
* Use clustering techniques to identify high-risk groups.
* Validate findings using real-world datasets.

## Conclusion

The analysis demonstrates that social media usage is a major contributor to increased stress among teenagers, while adequate sleep and better academic performance are associated with lower stress levels. Although the dataset is clean and suitable for analysis, the unusually strong correlations suggest that additional validation may be required before generalizing the findings to real-world populations.

### Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
