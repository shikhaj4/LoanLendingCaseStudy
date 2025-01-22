# Loan Landing Case Study

## Overview
The aim of this case study is to identify patterns which indicate if a person is likely to default. The analysis includes data understanding, cleaning, deriving new features , metrics and insights to make actionable recommendations.

## Dataset
- **Source:** loans.csv (Upgrade case study)
- **Size:** [39717, 111]
- **Variables:**
  - Meanings are given in jupyter notebook
 
## Process
1. **Data Understanding**
   - Explored data quality and variable meanings.
2. **Data Cleaning**
   - Addressed missing values, outliers, and redundancies.
   - Derived relevant metrics and features
   - Addressed datatypes of few columns
3. **Data Analysis**
   - Conducted univariate, segmented univariate, and bivariate analysis.
   - Identified important variables.
4. **Recommendations**
   - Scenario: Univariate analysis of loan_amnt: Use log transformation to reduce skewness for machine learning purposes
   - Scenario: Univariate analysis of dti: Create categories (e.g., low, medium, high DTI) to better understand borrower risk

## Results
Key findings include:
- Loan Amount: Larger loans → higher default rates 
- Issue Year: Economic downturns increase default risk.
- Purpose: Debt consolidation & small business loans → higher defaults

## Repository Structure
├── lending_case_study.ipynb       # Jupyter Notebook
├── README.md              # Project description
├── data/
    ├── loans.csv       # Raw dataset
    ├──
├── Loan Case Study.pptx     # PPT


## How to Run
1. Clone the repository.
2. Install NumPy, Pandas, Seaborn, and Matplotlib
3. Open lending_case_study.ipynb in Jupyter Notebook.

---------------


---

## **3. PPT Template**

### **Slide 1: Title Slide**
- Project Title
- Author(s)
- Date

### **Slide 2: Agenda**
- Objective
- Approach
- Results
- Recommendations

### **Slide 3: Data Understanding**
- Dataset overview (rows, columns, variable descriptions).
- Key data quality issues (e.g., missing values, outliers).
- Example visualization (e.g., bar chart of missing values).

### **Slide 4: Data Cleaning**
- Methods:
  - Missing value imputation.
  - Outlier treatment.
  - Derived metrics.
- Example before/after visualizations.

### **Slide 3-19: Data Analysis**
- **Univariate Analysis**
  - Insights from individual variables (loan_amnt, dti, int_rate, issue_year, home_ownership, emp_length_num, revol_util).
- **Bivariate Analysis**
  - Insights from relationships between variables (loan_amnt v/s loan_status, issue_year v/s default_rate, purpose v/s loan_status)

### **Slide 20-21: Results**
- Summary of findings

### **Slide 22: Recommendations**

Assumptions

- In the presentation, each analysis includes a plot on the first page, followed by subsequent page providing insights or statistics related to the plot.
