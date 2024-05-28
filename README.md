# JMPAnalysis-AirBnb
Analysis of AirBnb Prices using JMP Software

Andrew Peterson
Managerial Statistics
Dataset: AirBnb
Date: Summer A 2024

Project Abstract:
This project aims to present a statistical analysis of AirBnb prices across different cities. Findings planned to be shared in a digital artifact on Github. 

 

Note on Data Quality: 
The original data had 141 observations with price below $10 (1 in New York, 65 in Chicago, and 75 in Boston). For the purposes of this analysis, the price values below $10 were deemed bad data and excluded from this analysis. This is because prices below $10 appear unrealistic for an AirBnb and indicate that data may not be accurately reflect the actual market prices. 

Task 1: Compare AirBnb Price Distribution in New York and Boston

Shape
New York: New York data is right skewed, with a long right tail.  
Boston: The shape of the Boston distribution appears bimodal. There is a main peak of prices is between $25 and $50, with a slightly less dramatic peak between $75 and $100. 

Outliers
New York: New York has a significant number of outliers, as observed in the right side of the box and whisker plot. This represents several units with higher prices.  
Boston: Boston does not have any outliers. 
Comparison: The maximum price recorded in Boston is $150, which is below the Third Quartile of the NY data ($185). The max price in NY ($1500) is 10 times the max for Boston.

Center
New York: Mean of $160.75. Median of $111.00. High price outliers influence the relatively higher Mean than Median.
Boston: Mean of $52.41. Median of $32.
Comparison: The mean and median for the NY prices are both over 3 times that in Boston.  

Spread
New York: Range of 1,477. IQR of 110. Standard Deviation is 33.71.
Boston: Range of 140. IQR of 62. Standard Deviation is 161.88.
Comparison: The overall range for NY prices is 10 times that in Boston. However, the IQR difference is much less pronounced due to the exclusion of outliers in the NY data. Boston has relatively less fluctuation in pricing as their standard deviation is 4 times less than New York.

NEW YORK
 
BOSTON
 

Task 2A: Estimating New York Population Mean – Confidence Interval

Problem
What is the population mean price for an AirBnb in New York?

Plan
Data was randomly sampled from AirBnbs available for rent in December 2021. This data was compiled and aggregated from the website insideairbnb.com/get-the-data/. 

Data
The data in this section is filtered to exclusively contain observations from NY. The main variable analyzed in this section is Price in USD (continuous numeric, price of renting the listed unit for 1 night). Parameter: μ = population mean price of an AirBnb in NY in December 2021.

Analysis
Conduct a Confidence Interval for One Mean to estimate the population mean price for an AirBnb in NY in December 2021. 
Assumptions Met: Random sample. Sample Size 375 is greater than minimum of 30.

JMP Calculation – Confidence Interval for One Mean 
  

Conclusion
We are 95% confident that the true population mean price for an AirBnb in NY in December 2021 is between $144.31 and $177.18.

Task 2B: New York Population Mean – Hypothesis Test

Problem
Is the population mean price for an AirBnb in New York in December 2021 greater than $150?

Plan
Data was randomly sampled from AirBnbs available for rent in December 2021. This data was compiled and aggregated from the website insideairbnb.com/get-the-data/. 

Data
The data in this section is filtered to exclusively contain observations from NY. The main variable analyzed in this section is Price in USD (continuous numeric, price of renting the listed unit for 1 night). Parameter: μ = population mean price of an AirBnb in NY in December 2021.

Analysis
Conduct a Hypothesis Test for One Mean to see if the population mean price for an AirBnb in NY in December 2021 is greater than $150. 
Null Hypothesis: μ = 150
Alternative Hypothesis: μ > 150
Assumptions Met: Random sample. Sample Size 375 is greater than minimum of 30.

JMP Calculation – Hypothesis Test for One Mean 
 

Conclusion
With an observed p-value of 0.0997 and t* Critical value of 1.6489, there is not enough evidence to reject the Null Hypothesis at alpha = 0.05. Therefore, there is not enough statistical evidence that the true population mean of AirBnbs in NY in December 2021 is greater than $150. Note however that if alpha = 0.10, this observed p-value would lead us to reject the Null Hypothesis, in favor of the Alternative Hypothesis. This indicates some evidence against the Null Hypothesis.
