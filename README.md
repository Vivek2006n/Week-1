# Week 1 - Machine Learning Basics 🚀

This repository contains my Week 1 assignment for the ML Internship program.  
The task was to understand the basics of Machine Learning, explore a given crop dataset, and perform initial data analysis.

## 📁 Files Included

- `crop_recommendation_week1.ipynb`: Colab notebook with data loading, info, and basic EDA.
- `Week1_assignment.docx`: Word document explaining ML, Supervised ML, Regression, and Classification.

## 📊 Tasks Covered

- What is Machine Learning?
- What is Supervised ML Algorithm?
- What is Regression and Classification?
- Importing data using `pandas`
- Displaying basic dataset insights using `.head()`, `.info()`

## 🔗 Dataset

The dataset was provided as part of the internship.

---

# Week 2 - Exploratory Data Analysis & Preprocessing 🔍

This week, I performed detailed exploratory data analysis (EDA) on the crop dataset and prepared it for machine learning.

## 📁 Files Included

- `Crop_Prediction_week2.ipynb`: Notebook containing all visualizations and preprocessing steps.

## 📊 Tasks Covered

- Plotted histograms, scatter plots, and box plots to visualize feature distribution and detect outliers.
- Created a correlation heatmap to understand feature relationships between features.
- Converted crop labels into numeric form using a mapping dictionary.
- Dropped the original `label` column and added a new `crop_no` column.
- Split the dataset into features (`X`) and target (`y`).
- Performed a train-test split using `train_test_split()` from Scikit-learn.

---

# Week 3 - Fertilizer Recommendation System + Feature Scaling 🌱

In the final week, I developed a Fertilizer Recommendation system and enhanced the Crop Recommendation model using feature scaling.

## 📁 Files Included

- `Fertilizer_Recommendation_Final.ipynb`: Rule-based fertilizer recommendation system.
- `Crop_Recommendation_Final.ipynb`: Improved crop prediction model with feature scaling using `StandardScaler`.

## 📊 Tasks Covered

- Performed EDA and preprocessing on fertilizer recommendation dataset.
- Built a logic-based fertilizer recommender using NPK imbalance and crop input.
- Recommended fertilizers such as Urea, DAP, etc. based on the nutrient deficiency.
- Applied `StandardScaler()` for feature scaling to normalize data before training.
- Improved accuracy and consistency of the crop recommendation model after scaling.

---

## ✍️ Author

Vivek Negi  
B.Tech CSE Student | Aspiring Data Scientist
