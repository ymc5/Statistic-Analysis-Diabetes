# Statistic-Analysis-Diabetes
Analysis of glucose level data using multiple linear regression to explore correlations with age, blood pressure, and skin thickness in a diabetes dataset

**Glucose Level Data Analysis Using Multiple Linear Regression**


---

### Objective
To analyze a diabetes dataset and evaluate correlations between variables (age, blood pressure, skin thickness) and glucose levels using multiple linear regression.

### About Diabetes and Glucose Levels
Glucose levels are crucial indicators of diabetes. Lifestyle factors such as stress, diet, and exercise can influence glucose levels, potentially serving as confounders.

### Dataset
The dataset contains 2768 entries and 10 variables, including pregnancies, glucose levels, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, age, and outcome.

### Exploratory Data Analysis
1. **Data Distribution:** Descriptive statistics, histograms, and box plots were used to understand the distribution of variables.
2. **Data Analysis:** Two main analyses were conducted:
   - Linear correlation between age, blood pressure, skin thickness, and glucose levels.
   - Comparison of mean glucose levels between diagnosed and undiagnosed groups using a t-test.

### Data Preprocessing
- Null and zero values were filtered and excluded from the analysis.
- Log2 transformation was applied to glucose levels for improved normality.

### Visualization of Individual Variable Relationships
Scatter plots were used to visualize the relationships between age, blood pressure, skin thickness, and log-transformed glucose levels.

### Multiple Linear Regression Analysis
A multiple linear regression model was built with age, blood pressure, and skin thickness as independent variables and log-transformed glucose levels as the outcome.

### Hypothesis Testing
A two-sample t-test was conducted to compare mean glucose levels between diagnosed and non-diagnosed groups.

### Summary & Conclusion
The multiple linear regression analysis revealed associations between age, blood pressure, skin thickness, and glucose levels. Additionally, significant differences in mean glucose levels were observed between diagnosed and non-diagnosed groups. Further research is recommended for a deeper understanding of these factors' influence on glucose levels.

---

