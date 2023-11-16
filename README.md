# Patient Medical Condition Analysis

## Table of Contents

- [Data Sources](#data-sources) 
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendation](#recommendations)

### Project Overview 

This data analysis project aims to provide insights into understanding patterns in medical conditions across a specified timeframe. By examining the data, we aim to pinpoint the medical condition with the highest occurrence, focusing on the years 2018 to 2023. This particular insight holds significance as it provides a key indicator of the predominant health concern within our population during that period. 

### Data Sources 

Patient data: The primary dataset used for this analysi is the "patient_dataset.csv" file, containing detailed information about each patient and medical condition over a period of time. 

### Tools

- BigQuery Google Cloud SQL- Data Analysis - Data Extraction 
- Excel - Data Cleaning - Reports

  

### Data Cleaning 

In the initial data preparation phase, we performed the following task:
1. Data loading and inspection.
2. Data Extraction.
3. Data cleaning and formatting.


### Exploratory Data Analysis 

EDA involved exploring the patient data to answer key questions, such as:

- Among the patients in our dataset, which specific medical condition had the highest frequency or occurrence between the year of 2018 -2023?
- Which year had the highest Asthma occurrence?


### Data Analysis 

Include some intresting code/features worked with 

```sql
SELECT Name, Medical_condition, Date_of_Admission, Gender 
FROM `my-data-project-01-404320.Healthcare_data_project.Healthcare `
Order by Name ASC
```

### Results

The analysis results are summarized as follows: 
1. After analyzing the data spanning from 2018 to 2023, it is evident that Asthma emerged as the most prevalent medical condition, exhibiting the highest occurrences among the observed cases during this time period.
2. Upon examination, it is apparent that the peak occurrence of Asthma was observed during the period spanning 2019 to 2020, signifying the highest frequency of this medical condition within these specific years.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in research initiatives to better understand the factors contributing to the increased prevalence of asthma, allowing for more targeted and effective prevention and intervention strategies.
- Enhance emergency preparedness protocols in healthcare facilities to efficiently manage asthma-related emergencies during peak occurrence periods.

  ### References
  1.[Chat GPT](https://openai.com)
  
     
