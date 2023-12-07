# IMPACT-OF-COVID-19-IN-NIGERIA

## Table of Content
- [Project Objective](#project-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [DASHBOARD](#dashboard)
- [Result and Findings](#result-and-findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [Reference](#reference)


### Project Objective

The dataset is from the Nigeria Centre for Disease Control (NCDC), and it contains records of confirmed recent COVID-19 cases.

It shows a breakdown of the disease outbreak in all 36 states of Nigeria and FCT.

### Data Source

The dataset is from the Nigeria Centre for Disease Control [(NCDC)](https://www.kaggle.com/datasets/orjiugochukwu/nigeriacovid19-data19072022/) 

### Tools Used

Power BI

### Data Cleaning and Preparation

The dataset has 37 rows and 7 columns which includes confirmed cases, active cases, number of discharged patients, deaths, and Geo-location of the various states.

Meanwhile, the dataset was received clean so there was not much on it.

### Exploratory Data Analysis (EDA)

KPI

- TOTAL STATE = COUNT(naija_data[states])
- TOTAL ACTIVE CASES = SUM(naija_data[active_cases])
- TOTAL CONFIRMED CASES = SUM(naija_data[confirmed_cases]) 
- TOTAL DISCHARGED = SUM(naija_data[discharged])
- TOTAL DEATH = SUM(naija_data[deaths])

INSIGHTS
- Total Active Cases by States
- Total Confirmed Cases by States
- Total Death by States
- Total Discharged by States

### DASHBOARD

![Screenshot_147](https://github.com/Solution92/IMPACT-OF-COVID-19-IN-NIGERIA/assets/144762124/81802515-10f3-4e91-8371-cd01838046bb)

### Result and Findings

- TOTAL ACTIVE CASES was highest for Lagos at 2,852, followed by Kwara and Nasarawa.  Lagos accounted for 53.03% of TOTAL ACTIVE CASES.  Across all 37 states, TOTAL ACTIVE CASES ranged from 0 to 2,852.  
- At 101,683, Lagos had the highest TOTAL CONFIRMED CASES and was 2,033,560.00% higher than Kogi, which had the lowest TOTAL CONFIRMED CASES at 5.  Lagos accounted for 39.26% of TOTAL CONFIRMED CASES.  Across all 37 states, TOTAL CONFIRMED CASES ranged from 5 to 101,683.  
- Additionally, at 769, Lagos had the highest TOTAL DEATH and was 38,350.00% higher than Kogi, which had the lowest TOTAL DEATH at 2.  Lagos had the highest TOTAL DEATH at 769, followed by Edo and FCT. Kogi had the lowest TOTAL DEATH at 2.  Lagos accounted for 24.46% of TOTAL DEATH.  Across all 37 states, TOTAL DEATH ranged from 2 to 769.  
- Finally, at 98,062, Lagos had the highest TOTAL DISCHARGED and was 3,268,633.33% higher than Kogi, which had the lowest TOTAL DISCHARGED at 3. Lagos accounted for 39.15% of TOTAL DISCHARGED.  Across all 37 states, TOTAL DISCHARGED ranged from 3 to 98,062.  

### Recommendation

- Based on the data presented, it is recommended that public health efforts and resources be intensified in Lagos, Kwara, and Nasarawa, which have the highest total active cases.
- Additionally, targeted interventions should be implemented to address the disproportionately high number of confirmed cases and deaths in Lagos, underscoring the need for comprehensive health strategies and preventive measures.
- Moreover, collaboration between states can facilitate knowledge-sharing and resource allocation to effectively manage and control the spread of the virus, especially in regions with limited resources and higher vulnerability.

### Limitations

- The provided table lacks a timestamp, making it challenging to assess the currency of the data and the progression of the pandemic over time.
- The absence of population data for each state hinders a per capita analysis, which could provide a more accurate understanding of the relative impact of COVID-19 across different regions.
- Finally, the table does not include information on testing rates or methodologies, limiting the ability to make inferences about the extent of testing and potential underreporting in certain areas.

### Reference

Refer to [NCDC](https://www.kaggle.com/datasets/orjiugochukwu/nigeriacovid19-data19072022/) link above.


