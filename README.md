# Titanic Survival Prediction - End-to-End Data Science Project

## About the Project

This project was completed as part of my Data Science Internship at Synent Technologies.

The goal of this project was to build an end-to-end machine learning solution using the Titanic dataset. The project covers the complete Data Science workflow, starting from data cleaning and exploratory analysis to model building and performance evaluation.

The objective was to predict whether a passenger would survive the Titanic disaster based on features such as passenger class, gender, age, fare, and embarkation point.

## Dataset

Titanic Dataset

Source:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

## Project Workflow

### 1. Data Loading
- Loaded the Titanic dataset using Pandas.
- Explored the structure of the dataset.

### 2. Data Cleaning
- Filled missing values in the Age column using the median.
- Filled missing values in the Embarked column using the mode.
- Removed the Cabin column due to a large number of missing values.

### 3. Exploratory Data Analysis (EDA)
Created visualizations to understand the data:

- Survival Distribution
- Gender vs Survival
- Passenger Class vs Survival

### 4. Feature Engineering
- Selected relevant features for prediction.
- Converted categorical variables into numerical format using one-hot encoding.

### 5. Model Building
- Split the dataset into training and testing sets.
- Trained a Logistic Regression model.

### 6. Model Evaluation
- Generated predictions on test data.
- Evaluated model performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Tools Used

- Python
- Google Colab
- GitHub

## Visualizations Included

- survival_distribution.png
- gender_vs_survival.png
- class_vs_survival.png
- confusion_matrix.png

## Key Findings

- Female passengers had a higher survival rate than male passengers.
- First-class passengers were more likely to survive than passengers in lower classes.
- Passenger age and fare had an impact on survival probability.
- Logistic Regression provided a reliable baseline model for prediction.

## Model Performance

The Logistic Regression model achieved approximately 75%–85% accuracy on the test dataset, demonstrating its effectiveness in predicting passenger survival.

## Files Included

- Titanic_End_to_End_Project.ipynb
- README.md
- survival_distribution.png
- gender_vs_survival.png
- class_vs_survival.png
- confusion_matrix.png

## What I Learned

Through this project, I learned:

- Data cleaning and preprocessing techniques
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model training
- Model evaluation and interpretation
- End-to-end Data Science project workflow
- Project documentation and GitHub management

## Conclusion

This project provided hands-on experience in building a complete machine learning pipeline. It demonstrated how data preprocessing, visualization, and predictive modeling work together to solve real-world problems. The project strengthened my understanding of the end-to-end Data Science process and machine learning fundamentals.

## Author

Tharun
