# Airline Passenger Satisfaction Prediction

## Dataset Overview
- Dataset Name: Airline Passenger Satisfaction  
- Dataset Description:  
  This dataset comprises feedback from over 120,000 airline passengers. Each record includes demographic details, flight information, and evaluations of various aspects of the travel experience, such as cleanliness, comfort, service quality, and overall satisfaction. The dataset aims to provide insights into passenger satisfaction and dissatisfaction, enabling airlines to enhance service quality and optimize customer experiences.  

- Dataset URL:  
  [Airline Passenger Satisfaction Dataset](https://mavenanalytics.io/data-playground?page=6&pageSize=5)  

## Problem Statement
The objective is to develop a machine-learning model capable of accurately predicting whether passengers are satisfied or dissatisfied based on their demographic details, flight information, and ratings for various aspects of their travel experience. The solution will help airlines:  
- Identify key factors influencing passenger satisfaction.  
- Strategize targeted improvements to enhance service quality.  
- Provide a data-driven approach to optimizing customer experience.  

## Methodology
1. Data Exploration and Visualization:  
   - Assessed feature distributions, class imbalances, and missing values.  
   - Conducted exploratory data analysis (EDA) to identify correlations and trends.  

2. Data Preprocessing:  
   - Handled missing values and imbalances.  
   - Encoded categorical variables and scaled numerical features.  

3. Feature Engineering:  
   - Selected and engineered features to optimize model performance.  

4. Model Training and Evaluation:  
   - Trained and evaluated three machine-learning models.  
   - Performed hyperparameter tuning using GridSearchCV.  

5. Model Selection:  
   - RandomForestClassifier was identified as the best-performing model with:  
     - Test Accuracy: 95%  
     - Cross-Validation Accuracy: 95%  

## Key Findings
- The RandomForestClassifier demonstrated strong predictive performance, indicating no signs of overfitting or data leakage.  
- Important Features Identified:  
  - Flight comfort and cleanliness ratings.  
  - Service quality and punctuality.  
  - Demographic details like age and travel purpose.  

These insights provide actionable recommendations for airlines to enhance passenger satisfaction and deliver superior service quality.  


## Conclusion
The RandomForestClassifier's consistent accuracy highlights its reliability for predicting passenger satisfaction. This project offers airlines a robust framework to identify satisfaction drivers and guide strategic decisions to improve overall customer experiences.  


