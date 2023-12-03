# Pima-Tribe-Diabetes-Exploration-A-Data-Analysis-Repository


Project Overview:

This project delves into the analysis of diabetes within the Pima tribe, focusing specifically on females aged 21 and above. Diabetes, a widespread global health issue, is characterized by an increasing number of patients, and while its precise origin remains elusive, researchers posit that genetic factors and lifestyle play pivotal roles. The exploration centers around Exploratory Data Analysis (EDA) to glean insights into the prevalence and factors associated with diabetes in the specified demographic.

Data Dictionary:

The dataset comprises the following features:
Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Likelihood of diabetes based on family history
Age: Age in years
Outcome: Class variable (0: person is not diabetic, 1: person is diabetic)

Libraries Used

Pandas: Data manipulation and analysis
NumPy: Numerical operations
Seaborn and Matplotlib: Data visualization
StandardScaler, LogisticRegression, RandomForestClassifier: Machine learning models
Warnings: Handling warnings

Loading and Inspecting Data

Data is loaded using pandas.read_csv.
Overview of the dataset with tail() and head().
Checking the shape, size, data types, and presence of null values.

Descriptive Statistics

Displaying descriptive statistics for numerical features.
Utilizing KDE plot for 'BloodPressure' and extracting information for the maximum 'Glucose' level.

Central Tendency Analysis

Calculating mean, median, and mode for the 'BMI' column.
Checking if mean, median, and mode are equal.

Statistical Analysis

Counting instances where 'Glucose' is higher than its mean.
Creating a pair plot and scatter plot for visual exploration.

Boxplot Visualization

Visualizing the distribution of 'Age' using a boxplot.

Correlation Matrix

Calculating and displaying the correlation matrix.
Heatmap visualization for better understanding.

Machine Learning Models

Logistic Regression Model

Standardizing features and splitting data into train and test sets.
Training a Logistic Regression model and evaluating accuracy.
Displaying the confusion matrix.

Random Forest Model

Importing and training a Random Forest model.
Evaluating accuracy and displaying the confusion matrix.

Conclusion

After comparing the two models, it is observed that the Random Forest model outperforms the Logistic Regression model on the test set with an accuracy of 78% compared to 75%. The Random Forest model is chosen as it demonstrates better predictive performance for diabetes within the Pima tribe based on the provided dataset.
