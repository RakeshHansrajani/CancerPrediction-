# Breast Cancer Prediction model
### Abstract
Breast cancer is a significant cause of mortality, accounting for a high number of deaths worldwide each year. Classification and data mining methods play a crucial role in diagnosing and analyzing diseases, including breast cancer. This project focuses on predicting breast cancer using various machine-learning algorithms based on details of cell nuclei taken from breast masses. Exploratory data analysis will be performed to understand the data before building the model, and the model's performance will be evaluated using metrics other than just accuracy.

### Problem Statement
The objective of this project is to predict whether a patient has breast cancer or not based on cell nuclei details. Multiple classification algorithms will be employed to accomplish this task. Before building the model, exploratory data analysis will be conducted to gain insights into the data. The performance of the model will be evaluated using various performance metrics beyond accuracy.

### Dataset Information

1. radius: Mean of distances from the center to points on the perimeter
2. texture: Standard deviation of gray-scale values
3. perimeter: Observed perimeter of the lump
4. area: Observed area of the lump
5. smoothness: Local variation in radius lengths
6. compactness: (perimeter^2) / area - 1.0
7. concavity: Severity of concave portions of the contour
8. concave points: Number of concave portions of the contour
9. symmetry: Lump symmetry
10. fractal dimension: "coastline approximation" - 1
11. Diagnosis: Whether the patient has cancer or not ('Malignant', 'Benign')
<br>The dataset includes the mean, standard error, and "worst" (mean of the three largest values) of these features for each image, resulting in a total of 30 features. For example, field 3 represents the mean radius, field 13 represents the radius standard error, and field 23 represents the worst radius.

### Scope
This project will involve the following steps:<br>
**Data Pre-processing**: We will understand the basic structure and perform necessary data cleaning, handling missing values, handling duplicate values.<br>
**Exploratory Data Analysis (EDA)**: We will conduct an initial exploration of the dataset to perform Univariate, Bivariate, Multivariate Analysis and find patterns in the data. Also, we will treat outliers. <br>
**Training Models**: We have created user-defined functions which will ease our process of training datasets. We will train multiple Machine learning algorithms like Logistic Regression, Decision Tree, Random Forest, Bagging, AdaBoost, XGBoost, Naive Bayes, KNN, SVM with different tuning parameters to predict breast cancer prediction based on the provided features.<br>
**Model Evaluation**: We will tabulate and evaluate the performance of all trained models using appropriate evaluation metrics and assess their predictive capabilities.<br>
**Learning Outcome**: Through this project, you will gain a better understanding of exploratory data analysis, data preprocessing, and knowledge of various machine learning algorithms. You will also develop skills in model evaluation, and drawing insights from the results.<br>

### Conclusion
By completing this project, you will gain practical experience in analyzing medical data, building classification models for breast cancer prediction, and evaluating the performance of all algorithms using various metrics. You will also learn about hyperparameter tuning techniques to improve the model's accuracy and effectiveness. This project will enhance your understanding of the relationships among variables and enable you to apply similar techniques in future predictive tasks.
