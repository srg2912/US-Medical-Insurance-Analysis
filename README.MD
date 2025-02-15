# US Health Insurance Cost Analysis

## Overview
This project analyzes a dataset of US health insurance costs using exploratory data analysis (EDA). The dataset includes demographic and health-related factors such as age, BMI, number of children, smoking status, and region, along with the corresponding medical charges.

## Dataset
The dataset contains the following columns:
- **age**: Age of the primary beneficiary
- **sex**: Gender of the insurance holder (male/female)
- **bmi**: Body mass index (BMI), an indicator of body weight
- **children**: Number of dependents covered by insurance
- **smoker**: Smoking status (yes/no)
- **region**: Residential area in the US (northeast, southeast, southwest, northwest)
- **charges**: Medical insurance cost

## Exploratory Data Analysis (EDA)
The analysis includes:
1. **Summary Statistics**: Mean, median, mode, variance, and standard deviation for numerical variables.
2. **Correlation Analysis**: Examined relationships between variables, including Pearson correlation.
3. **Visualizations**:
   - Scatter plot of `age` vs `charges`, color-coded by smoking status.
   - Boxplots comparing medical costs across different groups.
   - Histograms and density plots to understand variable distributions.

## Key Findings
- **Smoking has a significant impact on insurance charges**, with smokers generally incurring much higher costs.
- **Age shows a weak-to-moderate positive correlation with charges** but is not the sole determining factor.
- **Distinct linear patterns were observed in the scatter plot**, suggesting subgroup effects (e.g., smokers vs. non-smokers).

## Future Work
- Deeper statistical modeling (e.g., regression analysis) to predict insurance charges.
- Exploring additional factors such as interaction effects between BMI and smoking.

## How to Run
1. Install required libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`.
2. Open and run the Jupyter Notebook (`US Insurance Project.ipynb`).
3. View the visualizations and analysis results.

## Author
Sergio Avalos S.

## Acknowledgments
This project was conducted as part of my Data Science learning journey.

