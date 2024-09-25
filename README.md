### Title:Drug (Cannabis) Consumption Prediction  
### Author: Alpesh Chovatiya

### Problem Statement:
The goal is to analyze patterns of drug consumption based on demographic information and personality traits. The dataset includes individuals from different age groups, genders, and educational backgrounds. Using this data, the objective is to understand how various factors such as personality scores and demographic information correlate with drug use patterns.

### Objective:
To build a machine learning model that predicts the Cannabis consumption based on based on demographic information and personality traits..

### Dataset Overview:
The dataset contains 17 columns and 1,978 rows.   
The dataset contains the following columns:    
**1. ID:** A unique identifier for each individual.  
**2. AgeGroup:** Age range of the individual.   
**3. Gender:** Gender of the individual (Male/Female).   
**4. Education:** Educational attainment level of the individual.   
**5. Country:** The country of residence.   
**6. Ethnicity:** Ethnic background of the individual.   
**7. Nscore:** Neuroticism score.   
**8. Escore:** Extraversion score.   
**9. Oscore:** Openness to experience score.   
**10. Ascore:** Agreeableness score.   
**11. Cscore:** Conscientiousness score.   
**12. Impulsive_Fraction:** A measure of impulsiveness.   
**13. SS_Fraction:** Sensation-seeking score.   
**14. Alcohol, Caffeine, Cannabis, Cocaine:** Drug consumption behavior for each drug (e.g., "Used", "Never Used").       

### Summary of Results:
**Logistic Regression:** 0.85   
**SVM:** 0.83       
**Decision Tree:** 0.78    
**XGB:** 0.82     
**K-Nearest Neighbors:** 0.82    
**Random Forest:** 0.83       
  

#### Best performing model for current dataset is Logistic Regression with accuracy of 85%.
