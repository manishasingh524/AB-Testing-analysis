# A/B Testing – Advertisement Conversion Analysis
A/B testing analysis to evaluate the impact of advertisements on user conversion using statistical testing and business insights.

## Project Overview
This project analyzes an A/B test conducted to determine whether displaying advertisements increases user conversion compared to a control group (PSA). The analysis focuses on conversion rate comparison, statistical significance testing, and business decision-making.

## Objective
To evaluate if advertisements have a statistically significant positive impact on user conversion rates.

## Dataset Description
- *test_group*: Indicates whether the user was shown an advertisement (ad) or PSA (psa)
- *converted*: Binary variable indicating conversion (1 = converted, 0 = not converted)

## Methodology
- Calculated conversion rates for both groups
- Performed Chi-square test to check statistical significance
- Computed 95% confidence interval for the difference in conversion rates
- Visualized conversion rate distribution between groups
  
## Key Results
- The ad group showed a higher conversion rate than the control group
- The Chi-square test produced a statistically significant p-value (p < 0.05)
- The 95% confidence interval for the difference in conversion rates did not include zero
  
## Business Insight
Advertisements significantly improve user conversion rates compared to the control group.

## Recommendation
The business should continue running advertisements and consider increasing investment in ad campaigns. Further experiments can be conducted to optimize ad creatives and targeting strategies.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

---
