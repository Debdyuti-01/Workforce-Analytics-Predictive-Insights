# Workforce Analytics Predictive Insights
Workforce Analytics: Predictive Insights" is a data-driven project focused on forecasting workforce dynamics. Leveraging advanced analytics techniques, it predicts employee attrition and performance factors, providing valuable insights for strategic decision-making and talent management

<p align="center">
<img src="https://cdni.iconscout.com/illustration/premium/thumb/data-analysis-by-employee-4550598-3773917.png?f=webp" width="00" height="400">

### Workforce Analytics
Workforce analytics is like having a magnifying glass for understanding your organization's people dynamics. It involves diving into Human Resource (HR) data to enhance workforce performance. Think of it as a talent radar, where HR data is examined closely and linked to organizational goals, showing how HR strategies impact overall success

### Objective
Workforce attrition is all about how many people leave a company and why. We're crunching the numbers to predict who might leave next and why they'd do it.

### Motivation
The project aims to boost employee satisfaction, cut costs, improve performance, and foster a positive workplace culture. Using data and analytics, it's an opportunity to make meaningful changes benefiting both employees and the organization.

#### The methodology for IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction is as follows:-
```
- Load the Dataset: The IBM HR Analytics Attrition Dataset is loaded using the pd.read_csv() function. The head() and info() methods are used to display the first few rows and get information about the dataset, respectively

- Knowing the Dataset: Basic Information about the dataset is generated; numerical and categorical attributes are enlisted.
- Data Cleaning: Any missing values in the dataset are dropped using the dropna() method

- Data Visualization: Matplotlib and Seaborn libraries are used to visualize the data

- Statistical Analysis: The ANOVA Test is performed to analyze the Numerical Features' Importance in Employee Attrition, while the Chi-Square Test to Analyze the Categorical Feature Importance in Employee Attrition

- Data Preprocessing: The target variable 'Attrition' is mapped to binary values (1 for 'Yes' and 0 for 'No'). Selected features are extracted from the dataset and one-hot encoded using the get_dummies() function

- Splitting the Dataset: The dataset is split into training and testing sets using the train_test_split() method from scikit-learn.
- Implementing Machine Learning Algorithms: Logistic Regression, XGBoost, CatBoost, AdaBoost, LightGBM, Decision Tree, and Random Forest classifiers are initialized and trained using the training data

- Model Evaluation: The accuracy score and confusion matrix are computed to evaluate the performance of each algorithm on the testing data

- Results: The results, including the accuracy and confusion matrix, are printed for each algorithm

- Model Performance Comparison: The hvPlot library is used to visualize the ROC curve diagram comparing the performance of all models used
```

### Dataset
This is a hypothetical dataset created by IBM data scientists. The dataset has (1470R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics, and labeled with whether they are still in the company or whether they have gone to work somewhere else
[Dataset Link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

#### Dataset Attributes
```
01] Age
02] Attrition
03] BusinessTravel
04] DailyRate
05] Department
06] DistanceFromHome
07] Education
08] EducationField
09] EmployeeCount
10] EmployeeNumber
11] EnvironmentSatisfaction
12] Gender
13] HourlyRate
14] JobInvolvement
15] JobLevel
16] JobRole
17] JobSatisfaction
18] MaritalStatus
19] MonthlyIncome
20] MonthlyRate
21] NumCompaniesWorked
22] Over18
23] OverTime
24] PercentSalaryHike
25] PerformanceRating
26] RelationshipSatisfaction
27] StandardHours
28] StockOptionLevel
29] TotalWorkingYears
30] TrainingTimesLastYear
31] WorkLifeBalance
32] YearsAtCompany
33] YearsInCurrentRole
34] YearsSinceLastPromotion
35] YearsWithCurrManager
```
#### Libraries Used:
```
- Pandas
- NumPy
- Matplotlib
- Seaborn
- HvPlot
- SciPy
- Sklearn
- XGBoost
- LightGBM
- CatBoost
- Warnings
```

### Conclusion
In summary, we conducted a thorough analysis of the IBM HR Analytics Attrition Dataset, covering data loading to model evaluation. Through diverse machine learning algorithms, we identified effective predictors of employee attrition. Our results and visualizations offer actionable insights for decision-makers and HR teams aiming to tackle attrition
