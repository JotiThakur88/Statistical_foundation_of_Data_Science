# Pandas_Practical1
This project creates a synthetic dataset with ages, incomes, and scores, performs statistical analysis (mean, median, weighted mean, z-scores, outliers, age bins), and demonstrates NumPy operations like array manipulation, broadcasting, dot products, and matrix algebra.
# Synthetic Data & Operations Project

##  Overview
This project demonstrates how to generate synthetic data and perform key data analysis and numerical operations using **Python**, **NumPy**, and **Pandas**.  
It covers descriptive statistics, standardization, grouping, and array/matrix operations.
##  Features
1. **Synthetic Dataset Creation**
   - Generates IDs, ages, incomes (lognormal), and scores (normal).
   - Includes random **NaN values** to simulate missing data.

2. **Statistical Analysis**
   - Mean, median, and age-weighted mean of income.
   - Explanation of when weighted mean is useful.

3. **Standardization & Outlier Detection**
   - Z-score transformation of income.
   - Identifies outliers where |z| > 3.

4. **Grouped Analysis**
   - Bins ages into ranges: [18–25), [25–35), [35–45), [45–60).
   - Aggregates count, mean income, and median score by group.

5. **NumPy Array Operations**
   - Shape, size, transpose, flattening.
   - Negative indexing and error handling.
   - Broadcasting with row vectors.
   - Dot product with another matrix.
   - Determinant and inverse of a matrix.

---

## 🛠️ Technologies Used
- **Python 3**
- **NumPy**
- **Pandas**

---

# Pandas Practical-02

**Overview**

This Jupyter Notebook focuses on analyzing Teachers Rating Data to explore relationships between various instructor attributes and their ratings. The analysis aims to understand patterns in teacher evaluations, including beauty scores, student ratings, gender differences, and tenure distribution.

**Key Objectives**

Identify the type of dataset (Time Series vs Cross-Sectional).

Compute descriptive statistics for teacher ratings.

Visualize the distribution of beauty scores.

Compare average beauty scores by gender.

Analyze tenure percentages across genders.

**Tools and Libraries Used**

pandas – Data manipulation and summary statistics

numpy – Numerical operations

matplotlib – Data visualization

**Main Analytical Steps**

Dataset Classification
The dataset is identified as Cross-Sectional, as it captures information about multiple teachers at a single point in time.

Descriptive Statistics
Summary metrics (mean, median, min, max) are computed for student_rating to understand distribution and central tendency.

Data Visualization
A histogram is generated to illustrate the distribution of the beauty variable among teachers.

Gender-Based Analysis
The notebook examines whether average beauty scores differ between male and female teachers.

Tenure Analysis
Calculates and compares the percentage of tenured professors by gender to identify any disparities.

**Insights**

The data suggests variability in beauty ratings across genders.

Summary statistics provide a clear view of student rating trends.

Visualization aids in understanding the overall distribution and potential biases in the dataset.

**Conclusion**

This notebook provides an introductory exploratory data analysis (EDA) of the Teachers Rating dataset. It demonstrates practical applications of Python’s data analysis libraries to explore academic and demographic patterns.


# Pandas_Practical 03

**Overview**

This Jupyter Notebook performs an exploratory data analysis (EDA) on a professor evaluation dataset, focusing on relationships among instructor characteristics such as age, gender, tenure, and course level.
The goal is to visualize and summarize trends in teaching evaluations using Python’s data analysis and visualization tools.

**Objectives**

Detect Duplicate Entries

Identify professors appearing more than once (professor_name) and compute their age-related statistics.

Compare Evaluation Scores by Course Level

Use a bar chart to visualize average evaluations for lower vs upper division courses.

Analyze Relationship Between Age and Evaluation

Generate a scatter plot to study correlations between professors’ age and their evaluation scores.

Gender-Based Comparison

Create a gender-differentiated scatter plot showing how evaluation scores vary between male and female professors.

Combined Analysis: Age, Gender, and Tenure

Visualize the relationship between age and evaluation, differentiating points by gender and tenure status.

**Tools and Libraries Used**

pandas – Data manipulation and analysis

numpy – Numerical computation

matplotlib – Data visualization and plotting

**Key Insights (Expected Outcomes)**

Identification of duplicate records and their characteristics.

Insights into how course level affects average evaluations.

Understanding whether age correlates with evaluation scores.

Gender-based patterns and how tenure influences evaluation outcomes.

**Conclusion**

practical3.ipynb demonstrates practical applications of data cleaning, descriptive analysis, and visualization using Python. It provides a structured approach to exploring academic evaluation data and uncovering patterns based on demographic and professional factors.



# Pandas_Practical4 
**Student Rating Dataset Analysis**

This repository contains an analysis of a Student Rating Dataset. The dataset includes professor information such as tenure status, age, gender, minority status, and teaching evaluation scores. The purpose of this project is to explore relationships between these variables and visualize the data.

**Project Objectives**

Calculate the percentage of visible minorities who are tenured and evaluate whether tenure status differs based on minority status.

Analyze whether average age differs between tenured and untenured professors, including mean and standard deviation calculations.

Visualize the distribution of professor ages to understand the spread of ages in the dataset.

Compare vertical and horizontal bar charts (bar vs barh) and visualize the distribution of professors by gender.

Calculate the median evaluation score for tenured professors.

**Workflow**
*Step 1: Percentage of visible minorities who are tenured*

Identify all visible minority professors.

Count how many are tenured.

Calculate the percentage.

Compare with overall tenure rate to assess differences.

*Step 2: Average age by tenure*

Separate professors into tenured and untenured groups.

Calculate the mean and standard deviation for each group.

Compare the averages to observe differences in age by tenure.

*Step 3: Graph for age*

Use a histogram to visualize the distribution of professor ages.

Analyze patterns or trends in age distribution.

*Step 4: Bar chart vs Horizontal bar chart*

bar(): vertical bars for categorical comparison.

barh(): horizontal bars for categorical comparison.

Plot gender distribution using both chart types to compare visuals.

*Step 5: Median evaluation score for tenured professors*

Filter dataset for tenured professors.

Arrange evaluation scores in ascending order.

Identify the middle value as the median.

**Dataset**

The dataset contains the following columns:

professor_id – Unique ID for each professor

tenure – Tenure status (Tenured / Untenured)

visible_minority – Minority status (Yes / No)

age – Age of professor

gender – Gender (Male / Female)

evaluation_score – Teaching evaluation score

Note: A synthetic dataset can be generated if the actual dataset is unavailable.

**Visualizations**

Histogram for age distribution

Vertical bar chart for gender distribution

Horizontal bar chart for gender distribution

**Conclusion**

The workflow allows the analysis of tenure and minority status, age differences, gender distribution, and teaching evaluation scores.

Insights can help understand trends in faculty demographics and evaluation patterns.
