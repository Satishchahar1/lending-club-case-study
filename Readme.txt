# Lending Club Loan Default Analysis

This repository contains the Exploratory Data Analysis (EDA) performed on Lending Club's loan dataset. The primary objective of the project is to identify patterns and factors that drive loan defaults, enabling the company to minimize credit losses and make informed decisions during the loan approval process.

## Table of Contents
- [General Information](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

---

## General Information

### Objectives:
The goal of this project is to analyze Lending Club's dataset and identify the variables that contribute to loan defaults. These insights can help Lending Club:
1. **Reduce Credit Losses**: Identify high-risk applicants to minimize defaults.
2. **Optimize Loan Approvals**: Avoid rejecting creditworthy applicants, ensuring sustained business growth.

The analysis focuses on:
- Understanding the drivers of defaults through visualizations.
- Evaluating the relationship between customer demographics, loan attributes, and loan outcomes.

---

## Conclusions

The analysis uncovered several key insights and actionable recommendations:

1. **Loan Amount Distribution**:
   - Most loans range between $5,000 and $15,000, with a peak around $10,000.
   - **Recommendation**: Focus on risk assessment for loan amounts exceeding $15,000 as they show higher variance in outcomes.

2. **Loan Status Count**:
   - A significant portion of loans is "Charged Off," emphasizing the need for improved risk evaluation.
   - **Recommendation**: Strengthen underwriting processes to reduce "Charged Off" loans.

3. **Interest Rate Analysis**:
   - Interest rates between 15%-20% correlate with higher default rates.
   - **Recommendation**: Adjust interest rate determination policies based on borrower risk profiles.

4. **Loan Purpose Insights**:
   - Loans for "Debt Consolidation" dominate the portfolio but have a high default rate.
   - **Recommendation**: Reassess criteria for debt consolidation loans or offer financial counseling for such applicants.

5. **Default Rate by Employment Length**:
   - Applicants with 10+ years of experience are not necessarily safer borrowers.
   - **Recommendation**: Avoid over-reliance on employment length for risk assessment.

6. **Correlation Heatmap**:
   - Strong relationships exist between `loan_amnt`, `funded_amnt`, and `installment`.
   - **Recommendation**: Optimize feature selection in predictive models to avoid redundancy.

7. **Income and DTI Analysis**:
   - High Debt-to-Income (DTI) ratios and low annual incomes (< $40,000) are associated with higher defaults.
   - **Recommendation**: Set stricter loan limits for borrowers with high DTI ratios and low incomes.

8. **Geographic Risk**:
   - States like California (CA), Florida (FL), and New York (NY) show higher default trends.
   - **Recommendation**: Adjust lending policies regionally to mitigate geographic risks.

---

## Technologies Used

The following technologies were used for data analysis and visualization:
- **Python**: Version 3.11.4
- **Matplotlib**: Version 3.7.1
- **Numpy**: Version 1.24.3
- **Pandas**: Version 1.5.3
- **Seaborn**: Version 0.12.2
- **PowerPoint**: For creating presentations of findings

---

## Acknowledgements

This project was inspired by:

- UpGrad tutorials on Exploratory Data Analysis (EDA).

---

## Collaborators

This project was developed by:
- @Satishchahar1 (https://github.com/Satishchahar1) 
- 

Feel free to contribute, raise issues, or suggest improvements for this project.
