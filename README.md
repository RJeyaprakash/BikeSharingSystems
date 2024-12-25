# Bike Sharing Systems
Modeling the demand for shared bikes using available independent variables

A bike-sharing system allows individuals to borrow bikes for a short term, either for a fee or free. Users typically access bikes from computer-controlled docks by entering payment information, then return them to another dock in the same system.
BoomBikes, a US bike-sharing provider, has faced revenue declines due to the COVID-19 pandemic and is planning a business strategy to boost revenue post-lockdown. They aim to understand the demand for shared bikes once quarantine ends to cater to needs and outperform competitors.
To achieve this, BoomBikes hired a consulting firm to analyze factors influencing shared bike demand in the American market. They want to identify significant variables impacting this demand and measure their predictive power. The company has collected extensive data on daily bike usage based on various factors.

## Table of Contents
[Objectives]
[Conclusion]
[Technologies used]

### Objectives:
The project involves modeling the demand for shared bikes using available independent variables. 
This model will assist management in understanding how demand fluctuates with different features, enabling them to adjust business strategies accordingly to meet demand levels and customer expectations. 
Additionally, this model will provide insights into the demand dynamics of a new market.

### Conclusion:
•	**Seasonal Variation**: The positive coefficient for season (0.1352, p-value: 0.000) shows significant bike demand changes across seasons, guiding management to plan for higher demand in favorable seasons.

•	**Yearly Trend**: The positive coefficient for yr (0.2356, p-value: 0.000) indicates increasing bike demand over time, suggesting growing popularity and informing long-term strategic planning.
•	**Weather Conditions**: The negative coefficient for weathersit (-0.1830, p-value: 0.000) shows that adverse weather reduces bike demand, helping adjust operations during such conditions.
•	**Temperature Impact**: The strong positive coefficient for temp (0.4895, p-value: 0.000) shows warmer temperatures significantly boost bike demand, ensuring adequate bike availability during warmer periods.

### Technologies used:
•	Python
•	Matplotlib
•	Pandas
•	Seaborn
•	Sklearn
•	statsmodels


 


