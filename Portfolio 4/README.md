# 🏋️‍♂️ Exploring Gym Member Exercise Patterns 📊

## Introduction 📚

This repository contains an analysis of gym member exercise patterns, focusing on identifying workout behaviours, trends, and physical performance metrics among gym-goers. In today's health-conscious world, understanding these factors is essential for promoting a healthy lifestyle. This project utilises a dataset that provides detailed insights into gym members' workout habits and physical characteristics.

## Dataset Structure 📋

The **Gym Member Exercise Dataset** contains detailed information on the following key features:

- **MemberID** 🎫: Unique identifier for each gym member
- **Age** 👤: Age of the gym member
- **Gender** 🚻: Gender of the gym member
- **ExperienceLevel** 💪: Workout experience level (Beginner, Intermediate, Advanced)
- **BodyFatPercentage** 📉: Member's body fat percentage
- **BMI** ⚖️: Body Mass Index
- **WorkoutFrequency** 🏋️‍♂️: Number of weekly workouts
- **CardioTime** 🏃‍♀️: Time spent on cardio (in minutes)
- **StrengthTrainingTime** 🏋️: Time spent on strength training (in minutes)

## Explorations & Steps 🔍

### 1. Data Preprocessing 🧹

The dataset was pre-processed to handle any missing values, outliers, and feature scaling. Key pre-processing steps include:

- Standardising numerical variables such as `BMI` and `WorkoutFrequency`
- Encoding categorical variables such as `ExperienceLevel` and `Gender`

### 2. Exploratory Data Analysis 📊

To uncover trends and patterns, a series of visualisations and statistical analyses were conducted. Some key insights include:

- **Calories burned** findings with the level of accuracy
- **Workout Frequency** trends based on **Experience Level**
- **BMI** correlation with workout habits

### 3. Machine Learning Models 🤖

Several machine learning models were applied to classify gym members and predict their workout behaviours:

- **K-Nearest Neighbours (KNN)**: Used to classify members based on their workout frequency and experience level.
- **Linear Regression**: Applied to predict total workout time based on members' age, BMI, and experience level.
- **Cluster with K-mean**: Find different types of groups that displays the members workout intensity.

### 4. Model Evaluation 📈

The models were evaluated using performance metrics such as:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Python Libraries Used 🐍

- `pandas` 🐼
- `numpy` 🔢
- `matplotlib` 📊
- `seaborn` 🎨
- `scikit-learn` 🤖

## Findings ✅

- **Linear Regression** demonstrated a strong correlation between **Calories burned** and other features included, with an **R² score of 0.99**.
- Members with **higher workout frequency** and **more training** are considered **gym rats**.
- **KNN** achieved an accuracy of **29%** when classifying gym members based on their workout types.


## Conclusion 🏁

This project provides valuable insights into gym member workout patterns and physical metrics, allowing gym management and fitness professionals to better understand member behaviour and optimise fitness programmes.

