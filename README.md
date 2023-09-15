# AQI_Statistical Data Analysis Project

## Introduction

The Air Quality Index (AQI) is a crucial metric used by the Environmental Protection Agency (EPA) to assess and communicate air quality levels. This report aims to analyze AQI data to provide insights for policy recommendations regarding renewable energy subsidies in select U.S. states.

## Data Overview

The dataset comprises 260 entries, including parameters like date, state, county, city, local site, AQI, and more. The mean AQI stands at approximately 6.76, reflecting generally good air quality.

## States' AQI Summary

- California: 66 entries
- Arizona: 14 entries
- Ohio: 12 entries
- Florida: 12 entries
- Texas: 10 entries
- New York: 10 entries
- Pennsylvania: 10 entries
- Michigan: 9 entries
- ...

## Mean AQI by RRE States

- California: 8.70
- Florida: 8.03
- Michigan: 8.17
- Ohio: 8.83
- Pennsylvania: 8.70
- Texas: 8.50

## Evaluation

Based on the data and boxplot visualization, Ohio shows the highest mean AQI, potentially making it the most affected state if the policy is enacted.

## Confidence Interval

For Ohio, the 95% confidence interval is calculated as [5.09, 9.39]. This implies a 95% confidence that the true population mean falls within this range.

## Hypotheses and Recommendations

### Hypothesis 1

- **Objective**: Determine if the mean AQI in Los Angeles County differs significantly from the rest of California.
- **Result**: With a p-value of 0.049, rejecting the null hypothesis. A metropolitan-focused approach in Los Angeles County is recommended.

### Hypothesis 2

- **Objective**: Choose between New York and Ohio for the next regional office based on lower AQI.
- **Result**: With a p-value of 0.030 and t-statistic < 0, rejecting the null hypothesis. Recommend choosing New York for the regional office.

### Hypothesis 3

- **Objective**: Assess if Michigan's mean AQI is greater than 10, impacting the new policy.
- **Result**: With a p-value of 0.940 and t-statistic < 0, fail to reject the null hypothesis. It is unlikely that Michigan will be affected by the new policy.

## Key Takeaways

- Sampling with replacement leads to duplicate rows and is a crucial consideration.
- Sample means often differ from population means due to inherent sampling variability.
- The Central Limit Theorem (CLT) proves invaluable in characterizing the sampling distribution of the sample mean across diverse datasets.

## Recommendations

- The mean AQI is below 100, indicating satisfactory air quality.
- Further analysis is needed for AQI values outside the "satisfactory" range, focusing on regions with potentially unhealthy air quality.
- Allocate funding for initiatives to improve air quality in regions with suboptimal AQI levels.

## Conclusion

This analysis offers valuable insights into air quality data, emphasizing the importance of the central limit theorem and the implications of random sampling. The findings provide a solid foundation for informed decision-making and targeted interventions to enhance air quality in affected regions.


