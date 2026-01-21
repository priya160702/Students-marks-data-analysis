# Students Marks Analysis and Prediction

This project performs a comprehensive analysis of students' performance in exams based on various demographic and socio-economic factors. It includes an extensive Exploratory Data Analysis (EDA) phase followed by a machine learning model to predict student outcomes.

### Dataset Overview

The dataset consists of 1,000 student records with 8 initial attributes:

Gender: Male/Female.

Race/Ethnicity: Grouped categories (A through E).

Parental Level of Education: Ranging from high school to master's degrees.

Lunch: Type of lunch (Standard or Free/Reduced).

Test Preparation Course: Whether the student completed a prep course.

Scores: Individual scores for Math, Reading, and Writing.

### Analysis and Features

During the EDA phase, a new feature, Mean Score, was engineered by averaging the Math, Reading, and Writing scores to provide a holistic view of student performance.

Key visualizations include:

Distribution of scores across different genders and ethnic groups.

The impact of parental education levels on student performance.

Correlation analysis between different subjects.

### Learning Algorithms

The project utilizes Logistic Regression to predict student performance categories. This model was chosen to identify how various factors influence the probability of a student achieving certain score thresholds.

### Results
The model's performance was evaluated by comparing predicted values against the actual test data.

Accuracy: High predictive capability in identifying performance trends.

Key Finding: Factors like "Test Preparation Course" and "Lunch" type showed significant correlations with the final mean scores.

### Technologies Used

Python 3

Pandas & NumPy: For data cleaning and manipulation.

Seaborn & Matplotlib: For statistical data visualization.

Scikit-learn: For machine learning and preprocessing.

### How To Run
1. Install the required libraries:

   ```Bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```

2. Open and run the students-marks-analysis-and-prediction.ipynb notebook in any Jupyter environment.
