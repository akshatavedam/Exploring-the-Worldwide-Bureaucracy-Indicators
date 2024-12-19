# Exploring-the-Worldwide-Bureaucracy-Indicators

Project for NUS DSA2101

## Introduction to the Dataset
The Worldwide Bureaucracy Indicators (WWBI) database is a unique cross-national dataset on public sector employment and wages that aims to fill an information gap, thereby helping researchers, development practitioners, and policymakers gain a better understanding of the personnel dimensions of state capability, the footprint of the public sector within the overall labor market, and the fiscal implications of the public sector wage bill. The dataset is derived from administrative data and household surveys, thereby complementing existing, expert perception-based approaches.

It is classified into 3 different datasets: <br /> 
`wwbi_data` : dataset containing measurements of bureaucratic indicators. <br />
`wwbi_series` : Contains additional information about specific indicators, such as indicator_code, which describes the unique metrics.<br />
`wwbi_country` : Contains country-level information, identified by country_code, which helps in enriching the dataset with country-specific attributes.<br />

In this report, we will be exploring the primary question of:

**How do public sector wage structures differ across regions and gender groups?**

To further divide the main question we will be visualizing the following sub-questions:
1. How does the wage structure vary over time across regions?<br />
   Visualisation used : Heat Map
2. Are there noticeable trends or divergences in male versus female wage premiums within each region?<br />
   Visualisation used : time series line chart
3. How does the system of trade influence the wage bill as a percentage of public expenditure across regions?<br />
   Visualisation used : bar chart

The `wwbi_full` dataset is a refined and comprehensive version of the Worldwide Bureaucracy Indicators (WWBI) data, created by merging and cleaning data from multiple tables within the WWBI database.
