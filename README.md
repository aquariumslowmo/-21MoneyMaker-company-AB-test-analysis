# -21MoneyMaker-company-AB-test-analysis
Project Overview

This project evaluates whether a redesigned checkout page improves conversion rate compared to the original version using A/B testing and statistical analysis.

Business Problem
The company introduced changes to its checkout page and wants to determine whether the new design leads to a higher conversion rate.

Hypothesis

H₀ (Null Hypothesis): There is no statistically significant difference in conversion rates between Group A and Group B.
H₁ (Alternative Hypothesis): The conversion rate of Group B is different from Group A.

Dataset

The dataset contains users assigned to two experimental groups:

Group A: Control group — original checkout page.
Group B: Treatment group — redesigned checkout page.

Key metrics:

Number of users
Number of conversions
Conversion rate
Tools & Technologies
Python
Pandas
NumPy
SciPy
Matplotlib
Statistical Hypothesis Testing
Analysis
Data exploration and validation
Conversion rate calculation
Absolute and relative conversion rate difference
Standard error calculation
Z-test for proportions
Confidence interval calculation
Statistical significance evaluation
Business recommendation

Results:----------------------------------------


Control group conversion rate: 25,6%

Treatment group conversion rate: 25,7%

Absolute difference: 4.4 percentage points

Relative lift: 16%

P-value: 0.8517

95% confidence interval: [0.84 , 6.98]

-------------------------------------------------
Conclusion

#the 4-week experiment could reliably detect a lift of about 4.4 pp or larger
#The p-value is 0.85, which is above 0.05, so we fail to reject H0.
#For SRM test the p-value is 0.99, which is above 0.001. So the split was fair.
#For A/B test The p-value is 0.0127, which is below 0.05, so we reject H0: 
#the new checkout does change conversion, and since B is higher, we should RELEASE a new checkout design.

The analysis determines whether the redesigned checkout page provides sufficient statistical evidence of a change in conversion rate and whether the company should consider implementing the new design.



