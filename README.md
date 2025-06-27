# Hypothesis testing of a pay gap in a Spark Fortress Inc.
## Project Objective
This Data Science project aims to determine whether a pay gap exists in Spark Fortress Company based on gender and ethnicity, using hypothesis testing.

## Data used
- <a href = "https://github.com/pagonzales/Data_Science_Project_Hypothesis_Testing_Gender_Pay_gap/blob/main/Data%20set.xlsx">Dataset</a>
## Questions
- Does a gender pay gap exist across all age groups in the company?
- Does a gender pay gap exist between employees aged 35 and below and those above 35?
- Does a pay gap exist with respect to employees’ ethnicity?
## Process
- First standardize the given raw data.
- Find the necessary statistical parameters (sample number, mean, population variance, pooled variance, t-score, and p-value).
- Use the commands in MS Excel like nested functions to find these statistical parameters from a given data set.
- Analyze the resulting p-values from a different categories(gender pay gap and ethnicity) in different significance level (5%,2.5%,0.5%)
- Finally, give an insight about the results.
## Image
![image](https://github.com/user-attachments/assets/220b718e-acc2-478b-b1f1-d09881c87f38)

## Project insights
- Given a null hypothesis that there is no gender and ethnicity pay gap in the Spark Fortress Company, we found that;
  - In terms of employees gender across all age, we have,
    - the p value is always greater than the significance level (0.05,0.025,0.0005) which tells us that there is no significance in the result. Thus, we accept the null hypothesis.
  - In terms of employees aged 35 and below, we have,
    - Again, the p value is always greater than the significance level (0.05,0.025,0.0005) which tells us that there is no significance in the result. Thus, we accept the null hypothesis.
  - In terms of employees above 35 y.o, we have,
    - Again, the p value is always greater than the significance level (0.05,0.025,0.0005) which tells us that there is no significance in the result. Thus, we accept the null hypothesis.
  - Finally, in terms of ethnicity, we have
    - the p value is always greater than the significance level (0.05,0.025,0.0005) which tells us that there is no significance in the result. Thus, we accept the null hypothesis.
## Final conclusion
Since the p-values in different categories are always greater than the signifance level, we conclude that THERE IS NO PAY GAP existing in the company in terms of gender and ethnicity.
