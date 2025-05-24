# Healthcare Analysis Project

## Table of Contents

 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Recommendation](recommendations)
 - [Limitation](Limitations)
   
## Healthcare Analysis Dashboard

### Project Overview
---

In this Healthcare analysis project, I developed a in-depth Excel dashboard by integrating insights from a text files:The goal is to uncover meaningful insights into patient demographics, medical conditions, test outcomes, hospital stay durations, billing patterns and healthcare provider performance.After performing thorough data cleaning and transformation, I utilized Pivot Table to build custom measures and KPIs, enabling dynamic analysis of key in Healthcare metrics.

![Healthcare dashbaord project](https://github.com/Analyticope/Healthcare-Analysis-Project/blob/main/Healthcare%20dashboard%20project.jpg)





### Data Sources

Sourced from well-structured CSV files, the data offers a well-rounded insight of the patient demographics, medical conditions and more so to show the outcome of test results and billing patterns and healthcare insurance provider.

### Tools

- Excel
  - [Download here](https://microsoft.com)
- Power Query - data cleaning, automate repetitive task(like fiitering, merging, and formatting).
- Building custom columns to perform specific calculations
- Excel - Developing insightful analytics reports


 ### Data Cleaning/Preparation

In the initial stage of this project, I performed key data structuring to ensure the dataset was clean, consistent, and analysis-ready. This phase included:
  
  1. Loading and inspecting raw data to understand its structure and quality
  
  2. Handling missing values to maintain data integrity
  
  3. Removing blank rows and irrelevant columns to streamline the dataset
  
  4. Cleaning and formatting data for consistency across all fields

### Exploratory Data Analysis

Eda Involved Exploring Healthcare data to answer key question, such as :

7 Key Questions Excel Healthcare Project Answers:

This healthcare dashboard analyzes data from 55,500 patients across various metrics:

- How many Patient are there?

- How many Medical Conditions: Obesity, hypertension, diabetes, and more analyzed by test results (normal, abnormal, inconclusive).

- Test Outcomes: Similar result patterns across genders.

- What is the Average length of stay?

- What is Average Billing & Insurance Provider?

- Interactive Filters: Gender, test results, and admission/discharge years for dynamic exploration.

    
### Data Analysis

Tools & Features Used:

- Pivot Table and excel functions for custom measures and KPIs.

- Power Query for data cleaning and transformation.

- Pivot Table use for Calculated columns and measures.

- Custom columns and “Column by Example”.

- Aggregation functions (SUM, AVERAGE, COUNT etc).

- Interactive slicers and clear filter button for better UX.

### Results/Findings

   The dashboard revealed several key insights across patient demographics, healthcare delivery, and cost metrics:
  - Balanced Gender Representation: The dataset contains an equal distribution of male and female patients, allowing for unbiased gender-based analysis.

- Age Concentration: A significant portion of patients falls within the 40–60 age range, aligning with the increased risk for chronic conditions in mid to late adulthood.

- Test Result Trends: Abnormal and inconclusive results are nearly equal across genders, with a slightly higher count of normal results among female patients. This 
    consistency suggests no major gender disparities in diagnostic outcomes.

- Prevalent Conditions: Hypertension, diabetes, and obesity are the most commonly observed conditions. Test result outcomes for these conditions appear proportionally distributed across categories.

- Hospital Stay Duration: The average length of stay is 15.5 days. A noticeable spike in extended stays (28–30 days) may indicate either complex cases or administrative factors impacting discharge times.

- Billing Insights: The average billing amount per patient is approximately $25,539. While the dataset includes six insurance providers, no major billing discrepancies were observed across test result categories.

- Healthcare Provider Distribution: Abbott-affiliated hospitals have the highest doctor counts. Top doctors are ranked by patient volume, though qualitative metrics like patient outcomes or satisfaction are not included.

     
  ### Recommendation

   Recommendations Based on Insights
   
1.Optimize Patient Length of Stay
  - Investigate the causes of longer hospital stays (e.g., over 25 days) to identify inefficiencies in patient care or discharge 
     processes. Consider implementing early discharge planning and case management strategies to reduce average stay duration. 

  2.Target Chronic Conditions with Preventive Programs 
  - Conditions like Diabetes, Hypertension, and Cancer have high abnormal test results. Implement preventive care programs and chronic disease management initiatives to reduce complications and long-term costs. 

 3. Improve Gender-Specific Health Services
- Since abnormal results are slightly higher among females, consider exploring gender-specific diagnostic or screening programs to improve early detection and care. 

 4. Rebalance Doctor Workloads 
- Doctors like Aaron Baker handle disproportionately high patient volumes. Redistributing patient loads or hiring additional qualified professionals can help maintain quality of care and reduce burnout.

 5. Diversify Insurance Partnerships
-  With only 6 insurance providers, explore partnerships with additional insurers to give patients more flexibility, reduce billing barriers, and potentially improve service access. 
6. Invest in Elderly Care Services
- The majority of patients fall into the 60+ age group. Enhancing geriatric care, home-based treatment options, and specialized support could significantly improve outcomes and satisfaction. 

 7. Monitor Hospital Resource Allocation 
- A few hospitals dominate doctor counts. Assess whether this leads to overcrowding and consider expanding facilities or redistributing services to other locations to ensure equitable access. 

 8. Enhance Data Collection Over Time 
- Leverage the multi-year dataset (2019–2024) to perform trend forecasting, identifying seasonal patterns, post-pandemic shifts, or improvements in care quality over time.
 
   9. Explore Billing Optimization 
- With an average billing amount over $25,000, assess billing components, compare with national averages, and consider cost-containment strategies such as bundled payments or telemedicine options.


### Limitations
- The analysis is based solely on available patient data and does not account for external factors such as lifestyle, location, or socioeconomic status.

- Trends over time and outcomes of treatments are not included, limiting insight into patient progress or healthcare effectiveness.

- Doctor and hospital metrics are based on patient count only, without consideration of quality or specialization.

- Billing and insurance data are summarized and not broken down by specific medical conditions or patient categories.


