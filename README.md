**Breakout Activity: Exercise Recommendation Prediction**

This repository contains code and resources to predict an individual’s exercise recommendation plan based on features such as weight, height, BMI, age, and gender. The project follows a data-driven approach, using Python and popular machine learning libraries.

**Table of Contents**

1. Project Overview

2. Dataset

3. Code

4. Reflection

1. Project Overview
The objective of this project is to develop a machine learning model that predicts the optimal exercise recommendation plan based on personal fitness data. The dataset includes features like:

  * Weight

  * Height

  * BMI

  * Gender

  * Age

I used a Linear Regression model to predict the Exercise Recommendation Plan, a continuous target variable.

**2. Dataset**

The dataset used in this project is fitness_exercises.csv, which contains the following features:

* **Weight:** Weight of the individual

* **Height:** Height of the individual

* **BMI:** Body Mass Index

* **Age:** Age of the individual
  
* **Gender:** Gender of the individual (converted to numerical format)

* **Exercise Recommendation Plan:** The target variable indicating the recommended plan.

**3. Code**
Code has been provided in the attached pdf document

**4. Reflection**
The aim of the project is to predict an individual’s exercise recommendation plan based on
features such as weight, height, BMI, age, and gender. This prediction helps in providing
tailored fitness plans.
The first we need to perform pre-processing steps, including converting the categorical Gender
feature into numerical values (using one-hot encoding) and standardizing the features to ensure
consistency across different scales.
2
Chose Linear Regression as the model due to the continuous nature of the target variable,
Exercise Recommendation Plan. This model is a good starting point, as it is simple and
interpretable.
The Mean Squared Error (MSE) of the model was 0.31, which indicates how far the predicted
values are from the actual values on average. The lower the MSE, the better the model fits
the data. The performance seems reasonable, but improvements could be explored.
