##Diabetes Prediction


What is Diabetes?
Diabetes is a chronic disease that occurs when the pancreas is no longer able to make insulin, or when the body cannot make good use of the insulin it produces. Learning how to use Machine Learning can help us predict Diabetes. Let’s get started!

About this project :-
The objective of this project is to classify whether someone has diabetes or not.
Dataset consists of several Medical Variables(Independent) and one Outcome Variable(Dependent)
The independent variables in this data set are :-'Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin','BMI', 'DiabetesPedigreeFunction', 'Age'
The outcome variable value is either 1 or 0 indicating whether a person has diabetes(1) or not(0).


About the Dataset
Pregnancies :- Number of times a woman has been pregnant
Glucose :- Plasma Glucose concentration of 2 hours in an oral glucose tolerance test
BloodPressure :- Diastollic Blood Pressure (mm hg)
SkinThickness :- Triceps skin fold thickness(mm)
Insulin :- 2 hour serum insulin(mu U/ml)
BMI :- Body Mass Index ((weight in kg/height in m)^2)
Age :- Age(years)
DiabetesPedigreeFunction :-scores likelihood of diabetes based on family history)
Outcome :- 0(doesn't have diabetes) or 1 (has diabetes)
INDEX :-
1. Importing Required Libraries

2. Loading the Dataset

3. Exploratory Data Analysis

a. Understanding the dataset

Head of the dataset
Shape of the data set
Types of columns
Information about data set
Summary of the data set
b. Data Cleaning

Dropping duplicate values
Checking NULL values
Checking for 0 value
4. Data Visualization

Here we are going to plot :-
Count Plot :- to see if the dataset is balanced or not
Histograms :- to see if data is normally distributed or skewed
Box Plot :- to analyse the distribution and see the outliers
Scatter plots :- to understand relationship between any two variables
Pair plot :- to create scatter plot between all the variables
5. Feature Selection

6. Handling Outliers

7. Split the Data Frame into X and y

8. TRAIN TEST SPLIT

9. Build the Classification Algorithm

9.1 KNN

9.2 Naive Bayes

9.3 SVM

9.4 Random Forest

9.5 Logistic Regression

The models include the following:-
a. Hyper Parameter Tuning using GridSearch CV

b. Fit Best Model

c. Predict on testing data using that model

d. Performance Metrics :- Confusion Matrix, F1 Score, Precision Score, Recall Score, ROC-AUC score
