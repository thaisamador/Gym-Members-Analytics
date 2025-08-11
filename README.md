# Gym Members Analytics

Exploratory data analysis and member segmentation for a gym, using R, Power BI, and decision tree modeling to personalize fitness plans.

## Introduction
The fitness industry has become increasingly data-driven, with gyms leveraging analytics to understand member behavior, improve engagement, and design personalized training programs.  
This project analyzes historical gym member data to uncover behavioral patterns, segment members based on fitness and engagement metrics, and create a decision tree model to automatically classify new members.

## Dataset
Source: [Kaggle – Gym Members Exercise Dataset](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset)  
The dataset includes:
- **Demographics:** age, gender, experience level.
- **Biometrics:** weight, height, BMI, fat percentage.
- **Workout details:** type of workout, workout frequency, session duration, average & maximum heart rate, calories burned.
- **Hydration habits:** daily water intake.

## Project Objectives
1. Clean and preprocess biometric and workout tracking data.
2. Perform Exploratory Data Analysis (EDA) to identify health and activity trends.
3. Apply K-Means clustering to segment members by performance and engagement.
4. Build a decision tree model to classify new members into clusters.
5. Develop an interactive Power BI dashboard for visualization and decision-making.

## Tools & Technical Approach
- **R:** dplyr, tidyr (data cleaning & transformation), ggplot2 (visualizations), factoextra & cluster (clustering), rpart (decision tree modeling), corrplot (correlation analysis).
- **Power BI:** interactive KPIs, cluster visualizations, and demographic filters.
- **Techniques:** data cleaning, EDA, clustering, predictive modeling.

## Key Steps
1. Converted categorical fields (Gender, Workout_Type) to factors.
2. Validated biometric and workout variable ranges.
3. Generated histograms, boxplots, and correlation matrices for insights.
4. Applied K-Means clustering using demographic, biometric, and workout features.
5. Built a decision tree model using Age, BMI, Calories_Burned, and Workout_Frequency.
6. Designed an interactive Power BI dashboard to display KPIs and behavioral insights.

## Results
- Identified member segments with distinct fitness and engagement patterns.
- Created a predictive model to classify new members accurately.
- Developed an interactive dashboard for data-driven gym management.

📄 **[Full Report (PDF)](https://github.com/thaisamador/Gym-Members-Analytics/blob/main/Report%20Gym%20Member%20Analytics.pdf)**  
📊 **[Power BI Dashboard](https://github.com/thaisamador/Gym-Members-Analytics/blob/main/Dashboard%20Gym%20Member%20Analytics.pbix)**
