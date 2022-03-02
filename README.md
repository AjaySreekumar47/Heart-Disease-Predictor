# HeartDiseasePredictor
Creating a classification model to predict whether a patient has heart disease or not based on several health factors monitored in the training dataset.

1. Problem Definition
In a statement,

Given clinical parameters, can we predict whether a patient has heart disease or not?

2. Data
The original data came from Cleveland Data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+disease

The Kaggle version link: https://www.kaggle.com/ronitf/heart-disease-uci

3. Evaluation
If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

4. Features
This is where you'll get different information about each of the features of your data.

Create Data Dictionary

age
sex (1=Male, 0=Female)
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved (thalach in dataset)
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
