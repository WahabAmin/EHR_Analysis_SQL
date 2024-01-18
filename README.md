# EHR_Analysis_SQL

Dear GitHub Community,

I am excited to share my latest project, a comprehensive healthcare data analysis project, which I have developed to explore and analyze diverse healthcare datasets. This project encompasses a range of SQL queries that delve into patient information, conditions, immunizations, and encounters, offering valuable insights for data-driven decision-making in the healthcare domain.

Key Features:

Data Exploration: Utilizes SQL queries to explore and analyze various aspects of healthcare data, including patient demographics, medical conditions, immunization records, and encounter details.

Statistical Insights: Provides statistical insights such as the most common medical conditions, distribution of encounters, and analysis of patient demographics.

Complex Queries: Includes complex queries to identify patterns, calculate averages, and determine the timing of critical healthcare events, contributing to a comprehensive understanding of the dataset.


PROJECT CONTENT

-- Connect to dataset

-- Dataset
  
-- Exploratory Data Analysis (EDA)

-- Analysis

-- Insight

-- Recommendation



----------------------------------------------------------- DATASET 


Dataset was downloaded from synthea - https://synthea.mitre.org/

Synthea is an open source program that was developed by the MITRE corporation. It is programmed to randomly generate patient data.
In other words, it is a simulation modeled after the data that a hospital might generate into an electronic medical record system.
The data that gets generated includes: patient demopgraphics, encounters, drugs administered, lab values, equipment and supplies, providers, claims data, among other things.

What is most impressive about Synthea is the way that the data is simulated. Many aspects of Synthea are modeled after real life epedemiological trends and patterns.



---------------------------------------------- KEY INSIGHTS 

1-- 24,534 patients received multiple vaccines in a single encounter


2-- The average days between first and last immunization is 2,964 days


3-- 4,031 of patients are pregnant women


4-- White and Nonhispanic are the most commom race and ethnicity respectively


5-- 8 patients had encountert but did'nt immunized


6-- Average income is $116717.4


7-- Average healthcre expenses $386439.7


8-- There is 174 unique condition


9-- Most common condition is "Other psychological or physical stress, not elsewhere classified


10-- 66.1% of patients were diagnosed of condition related to stress more than once


11-- 1.5% of patients have pregnanacy related conditions.


12-- 99.4% of pregnant patients women were immunized


13-- City of Boston recorded the highest diagnoses of all cases.


14-- Top most reason for encounter  is Hospital Encounter with Problem


15-- 10,385 patients received easonal Flu Vaccine one month post encounter


16-- The average number of days between initial encounter and first imminization is 1,021 days


17-- The most common condition among patients is "Other psychological or physical stress, not elsewhere classified"


18-- Seasonal Flu Vaccine is the most used vaccine in the facility


19-- The month of March recorded the highest encounter, whiles the octoberf recorded the least.






----------------------------------------- RECOMMENDATIONS


1.  - Given the high number of patients that received multiple vaccines in a single encounter, it's important to ensure that vaccine administration processes are streamlined and efficient.
      

2. - Encourage healthcare providers to educate patients on the importance of timely vaccinations and work towards reducing the gap between first and last immunization.


3. - Given that 4,031 patients are pregnant women, there should be a focus on maternal health programs.


4. - Identify and address the reasons why 8 patients had encounters but did not receive immunizations. 


5. - Consider implementing programs to address stress management, mental health, and wellness. 


6. - Collaborate with local health agencies and healthcare providers in Boston to understand the specific health challenges and implement targeted interventions to address them.


7. - Continue to promote flu vaccination campaigns, especially during the month of October when the encounter rate is lowest.


8. - Ensure accurate and comprehensive record-keeping for patient encounters, immunizations, and diagnoses. This will aid in better analysis and decision-making for future healthcare initiatives.

