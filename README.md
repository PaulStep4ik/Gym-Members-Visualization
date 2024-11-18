# Gym Members Visualization Project

## Overview
This project focuses on analyzing gym members' exercise habits and their health-related metrics using a comprehensive dataset. The goal is to provide insights into members' workout types, age distribution, gender ratio, calorie burning, water intake patterns, and weekly workout frequency through interactive visualizations.

## Dataset Source
The dataset for this project was obtained from Kaggle. Below is the link to the dataset:  
[Gym Members Exercise Dataset](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset)  

A screenshot of the dataset page on Kaggle is also included in this repository for reference.

![Dataset Screenshot](./Kaggle%20Dataset%20Overview.JPG)

## Description of the Dataset
The dataset contains detailed information about gym members and their fitness activities. Key columns include:
- **Workout Type:** Type of workout performed (e.g., Strength, Cardio, Yoga, HIIT).
- **Gender:** Gender of the gym member.
- **Age Group:** Age category of the members (e.g., 18-29, 30-39, 40-49, 50+).
- **Calories Burned:** Number of calories burned during sessions.
- **Water Intake:** Amount of water consumed during sessions.
- **Weekly Workouts:** Number of workouts completed weekly.
- **Fat Percentage:** Members' average fat percentage.

## Key Questions Addressed
1. Which workout types are most popular among gym members?
2. What is the age group distribution of gym members?
3. How is the gender ratio distributed among members?
4. What are the trends for calories burned and water intake during sessions?
5. What is the weekly workout frequency, and how does it relate to fat percentage?

## Data Cleaning and Preparation
To prepare the dataset for analysis, the following steps were performed in Power Query:
1. **Data Formatting:** Ensured all columns had consistent data types (e.g., numeric, text, date).
2. **Missing Data Handling:** Removed or imputed missing data where necessary.
3. **Categorization:** Grouped continuous variables into meaningful categories (e.g., age groups).
4. **Data Transformation:** Calculated additional metrics, such as averages and percentages.
5. **Validation:** Verified the data's accuracy and removed duplicates.

## Final Dashboard
The interactive Power BI dashboard showcases the visual analysis and insights derived from the dataset. Below is the final dashboard screenshot:

![Dashboard](./Gym%20Members%20Final%20Dashboard.JPG)

## Insights and Key Findings
1. **Workout Popularity:** Strength and Cardio are the most popular workout types, with over 250 members in each category.
2. **Gender Distribution:** Female members slightly outnumber male members (52.52% vs. 47.48%).
3. **Age Group Insights:** Members are evenly distributed across age groups, with 18-29 being the most prominent.
4. **Calorie and Water Trends:** Average calories burned and water intake show a consistent upward trend during sessions.
5. **Workout Frequency:** Most members workout 3-4 times a week, with those working out 5 times a week having the lowest average fat percentage.
6. **Water Intake at Longer Sessions:** The graph "Burned calories and water intake during session" shows a sharp increase in water intake when the workout duration exceeds 90 minutes.

## Conclusion
This project highlights key trends in gym member activities and health metrics, offering actionable insights for gym management. The findings can be used to tailor gym programs, improve member engagement, and enhance overall fitness outcomes.
