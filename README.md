# South Africa Crime Statistics Analysis (2005-2015)
## 1. Background and Overview
The South Africa Crime Statistics project analyses the reported crime data across various provinces from the year 2005 to 2015. The objective of this project is to gain insight into crime trends across different regions, crime categories, and police stations. The goal is to use these insights to recommend actionable measures for law enforcement agencies to better allocate resources and address specific types of crimes.

This project was completed using Microsoft Excel for data cleaning, analysis, and visualisation. Key visuals were created to illustrate the distribution and trends of crime reports over time.
![Excel Dashboard](https://github.com/NondumisoStevens/South-Africa-Crime-Statistics-Analysis-2005-2015-/blob/main/dashboard.png)

## 2. Data Structure and Overview
The dataset contains information on crime reports from police stations across all provinces in South Africa for 11 years, from 2005 to 2015. Each record includes the following fields:

- **Province**: The region where the crime was reported.
- **Police Station:** The specific station that logged the crime report.
- **Crime Category:** The type of crime committed (e.g., Assault, Theft, Murder, etc.).
- **Year (2005-2015):** The columns represent the total number of crimes reported in that particular year for each category and region.

  ![Dataset](https://github.com/NondumisoStevens/South-Africa-Crime-Statistics-Analysis-2005-2015-/blob/main/dataset.png)

### Data Cleaning:
- Missing or erroneous entries were handled, with empty cells being filled appropriately.
- Pivot tables were used to summarise the data by year, category, and region.

## 3. Executive Summary
Over the 11-year period, crime statistics in South Africa showed various trends across categories and provinces. Some key findings include:

- **Year with the Most Reported Crimes:** 2014 had the highest total number of reported crimes.
- **Most Affected Province:** Gauteng consistently reported the highest number of crimes, accounting for 29,05% of all reported incidents from 2005 to 2015.
- **Most Common Crime Category:** All theft not mentioned elsewhere were the most commonly reported crime over the entire cycle, followed by Burglary at residential premises from 2005 until 2012.
  
These findings provide crucial insights for policymakers and law enforcement to better allocate resources to crime prevention and intervention programs.

## 4. Insights Deep Dive
### Year-by-Year Crime Trends
 ![Dataset](https://github.com/NondumisoStevens/South-Africa-Crime-Statistics-Analysis-2005-2015-/blob/main/yearDiff.png)
- The yearly increases fluctuate between small positive and negative values. None of the changes are extremely significant, indicating a somewhat stable crime rate over the years.
- The largest increase occurred between **2007-2008 and 2008-2009** (+2.39%).
- The largest decrease occurred between **2006-2007 and 2007-2008** (-3.11%).

While the crime rates do vary slightly year-to-year, none of the increases or decreases are particularly dramatic, meaning the crime rates remained relatively stable, with some fluctuations.

### Provincial Breakdown
Gauteng, Western Cape and KwaZulu-Natal consistently ranked as the provinces with the highest crime rates. This could be attributed to their large population sizes and high urban density, which are often correlated with higher crime rates. On the contrary, the Northern Cape reported fewer crimes.

### Crime Category Insights
- **All theft not mentioned elsewhere:** Across all years, they remained the most frequently reported crime category. This highlights the need for targeted interventions in areas with high theft rates.
- **Drug-Related Crimes:** There was a steep rise in drug-related crimes after 2012, which might be due to intensified law enforcement efforts or an actual increase in drug-related activities.

### Police Station Analysis
Certain police stations within high-density urban areas, such as Johannesburg Central and Durban Central, reported consistently higher crime numbers. These stations could benefit from additional resources to handle the growing crime rates in their jurisdictions.

![Dataset](https://github.com/NondumisoStevens/South-Africa-Crime-Statistics-Analysis-2005-2015-/blob/main/Screenshot%20(263).png)

## 5. Recommendations
Based on the findings from the dataset, here are a few recommendations:
1. **Targeted Law Enforcement in High-Crime Provinces:** Gauteng, Western Cape and KwaZulu-Natal should receive additional resources and personnel to cope with the increasing crime rates. Implementing community outreach and surveillance programs could reduce crime in these hotspots.
2. **Intervention for Theft:** With theft being the top reported crime, dedicated prevention programs focusing on community education and awareness should be prioritised. Law enforcement agencies could also consider deploying more personnel to areas with high incidences of these crimes.
3. **Focus on Drug-Related Crime Prevention:** The rise in drug-related crimes after 2012 indicates a growing problem that may require specific intervention. Law enforcement should focus on targeting drug networks and addressing the root causes of drug-related activities, such as poverty and unemployment.
4. **Predictive Analysis for Crime Prevention:** Further analysis could involve using predictive modelling techniques to forecast future crime trends. This would allow law enforcement agencies to proactively allocate resources where they are most needed.
5. **Resource Allocation for Understaffed Police Stations:** Police stations in high-crime areas, especially in large urban centres, should receive additional personnel and equipment to manage the heavy caseload more effectively.











