# Python Projects

## Table of Contents:
1. [BMI Prediction and Visualization Tool](#BMI-Prediction-and-Visualization-Tool)
2. [BMI Calculator](#BMI-Calculator)

# Project Title: BMI Prediction and Visualization Tool

## Project Description:
This Python project provides an in-depth analysis of Body Mass Index (BMI) based on height, weight, and gender. It encompasses various data analysis techniques, including data preprocessing, exploratory data analysis, visualization, machine learning modeling, and prediction. The primary objective of this project is to offer insights into BMI distribution and its implications for health, as well as providing a predictive tool for assessing an individual's health status based on their BMI.

## Analysis Overview:
- **Data Preprocessing**: The project begins with loading and preprocessing the dataset, which involves handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: EDA is performed to understand the distribution of BMI and its relationship with other variables such as height, weight, and gender. Various visualization techniques, including scatter plots, histograms, and pie charts, are used to explore the data.
- **Machine Learning Modeling**: A Random Forest Classifier is trained on the preprocessed data to predict health status based on BMI. The model is evaluated using metrics such as accuracy and confusion matrix.
- **Optimization**: The optimal number of trees for the Random Forest Classifier is determined using a grid search approach to maximize accuracy.
- **Health Status Prediction**: A function is developed to predict an individual's health status based on their gender, height, and weight. This function utilizes the trained machine learning model to provide actionable insights.

## Techniques Used:
- **Data Preprocessing**: Handling missing values, encoding categorical variables using One-Hot Encoding, and scaling numerical features using StandardScaler.
- **Exploratory Data Analysis**: Utilizing seaborn and matplotlib libraries for visualizing data distribution, correlations, and categorical variables.
- **Machine Learning Modeling**: Implementing a Random Forest Classifier using scikit-learn library for predicting health status based on BMI.
- **Optimization**: Conducting a grid search to find the optimal hyperparameters for the Random Forest Classifier.
- **Health Status Prediction**: Developing a function to predict an individual's health status based on their BMI using the trained machine learning model.

## Conclusion:
This project provides a comprehensive analysis of BMI using data science techniques, including data preprocessing, visualization, and machine learning modeling. By leveraging these techniques, the project offers valuable insights into BMI distribution and provides a predictive tool for assessing an individual's health status based on their BMI.

#Project Title: BMI Calculator

## Inspiration Behind the Calculator:
This BMI calculator is inspired by the BMI calculator provided by [Mercer Health](https://mercer-health.com/services/weight-management-center/bmi-calculator#:~:text=Body%20Mass%20Index%2C%20or%20BMI,inches%20x%20height%20in%20inches). Body Mass Index (BMI) is a measure of body fat based on height and weight. It is commonly used to categorize individuals into different weight categories, such as underweight, normal weight, overweight, and obese.

## How to Use:
1. **Enter Your Information**:
   - Enter your name.
   - Enter your weight in pounds.
   - Enter your height in inches.

2. **View Your BMI**:
   - The calculator will compute your BMI based on the provided weight and height.

3. **Interpret Your BMI**:
   - Based on your calculated BMI, the calculator will provide feedback on your weight status.
     - If your BMI falls within a certain range, it will provide personalized feedback to help you understand your weight status better.

## Example:
```
Enter you name: Tinker bella
Enter your weight in pounds: 90
Enter your height in inches: 30

BMI: 70.3

Tinker bella, you are morbidly obese. Please start your weight loss journey as soon as possible and don't forget to believe in yourself! You can do it.
```

## Note:
- This calculator provides an estimate of your BMI and is meant for informational purposes only. It is not a substitute for professional medical advice.
- It uses the formula: BMI = (weight in pounds * 703) / (height in inches * height in inches).
- Please consult with a healthcare professional for personalized advice on managing your weight and health.
