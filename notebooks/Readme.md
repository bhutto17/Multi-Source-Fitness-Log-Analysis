# **Sports Logging Data Analysis**

## **Objective**

The goal of this project is to **analyze and visualize sports logging data** collected from participants to gain insights into their physical activity, calorie expenditure, sleep patterns, and overall health metrics. The analysis aims to help participants understand their activity levels and identify potential areas for improvement in their fitness and sleep routines.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Machine Learning Models](#machine-learning-models)
6. [Key Insights](#key-insights)
7. [Recommendations](#recommendations)
8. [Technologies Used](#technologies-used)
9. [How to Run the Project](#how-to-run-the-project)
10. [Author](#author)

---

## **Project Overview**

This project involves the analysis of a dataset containing sports logging data collected from 16 individuals using **Fitbit**, **PMSys App**, and **Google Forms**. The data spans from November 2019 to March 2020 and includes various fitness and sleep metrics. The analysis focuses on identifying patterns in physical activity, calorie expenditure, and sleep quality, providing recommendations for a healthier lifestyle.

The analysis includes:
- Exploratory Data Analysis (EDA)
- Clustering and Predictive Modeling
- Visualization of activity, calorie expenditure, and sleep patterns
- Recommendations based on insights

---

## **Dataset Description**

The dataset contains various metrics related to participants' daily activities and health.

### **Key Components:**
- **User Data**: Basic demographic details like age, height, and gender.
- **Calories Data**: Detailed logs of calories burned throughout the reporting period.
- **Exercise Data**: Data on various exercises, duration, steps, heart rate, and calories burned.
- **Sleep Data**: Information on sleep patterns, duration, and sleep stages.

### **Data Sources:**
1. **Fitbit Versa 2**: Used to track physical activities and health metrics.
2. **PMSys App**: Captures detailed exercise and sports-related information.
3. **Google Forms**: Additional participant self-reports and input.

---

## **Data Preprocessing**

1. **Mounting Google Drive**: Set up Google Drive to access and store data.
2. **Installing Kaggle API**: Download the dataset using Kaggle API.
3. **Setting Up Directories**: Organize directories and folders for data.
4. **Data Cleaning**: Handle missing values, format datetime, and organize relevant columns.
5. **Feature Engineering**: Extract key features like heart rate zones, activity levels, and sleep stages for analysis.

---

## **Exploratory Data Analysis (EDA)**

Exploratory Data Analysis (EDA) was conducted on each dataset component:
1. **Activity Patterns**: Analyzed popular activities, calorie expenditure, and intensity across various exercises.
2. **Calorie Expenditure**: Identified high-calorie activities and examined calorie burn rates per minute.
3. **Sleep Patterns**: Explored sleep duration, efficiency, and the distribution of different sleep stages (REM, deep sleep, light sleep).

**Visualizations**:
- Heatmaps, bar charts, and histograms were used to illustrate relationships between activity, calories burned, and sleep quality.

---

## **Machine Learning Models**

1. **Unsupervised Clustering**: Applied K-means clustering on exercise and sleep data to group similar activity and sleep patterns.
2. **Predictive Modeling**: Trained regression models to predict the overall sleep score based on activity and sleep metrics.

**Models Used**:
- Random Forest Regressor
- Gradient Boosting Regressor
- Linear Regression

---

## **Key Insights**

1. **Exercise Patterns**: Running and outdoor activities resulted in higher calorie burns, especially among male participants who were most active on weekends.
2. **Calorie Expenditure**: High-impact activities like treadmill and outdoor biking burned the most calories per session.
3. **Sleep Quality**: Participants slept an average of 7.5 hours, with light sleep comprising over 54% of the total duration, indicating potential room for improvement in sleep quality.
4. **Gender Differences in Activity and Sleep**: Male and female participants displayed unique patterns in exercise intensity and sleep quality.

---

## **Recommendations**

- **Optimize Exercise Routines**: Focus on activities that allow participants to maintain high activity levels for extended durations to maximize calorie burn.
- **Improve Sleep Quality**: Encourage better sleep hygiene to increase time spent in deep and REM sleep stages for optimal recovery.
- **Variety in Activities**: Diversify types of exercises to reduce data skew from excessive walking and improve insights across various physical activities.
- **Use of Journals for Sleep Tracking**: Maintain a sleep journal to identify external factors impacting sleep quality.

---

## **Technologies Used**

- **Python**: Data preprocessing, analysis, and modeling
- **Pandas**: Data manipulation
- **Seaborn & Matplotlib**: Visualization
- **Scikit-Learn**: Machine learning and clustering

---

## **How to Run the Project**

1. **Mount Google Drive**: 
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
2. **Set Up Kaggle API and Download Dataset**:
    ```bash
    !mkdir -p ~/.kaggle
    !cp "/content/drive/MyDrive/kaggle.json" ~/.kaggle/kaggle.json
    !chmod 600 ~/.kaggle/kaggle.json
    ```
3. **Run Jupyter Notebook**: Open the Jupyter notebook and follow the steps in the notebook for data analysis and visualization.

---

## **Author**
**Faizan Bhutto**  
[LinkedIn](https://www.linkedin.com/in/faizanbhutto) | [GitHub](https://github.com/bhutto17)

Feel free to reach out if you have any questions or feedback regarding this project.
