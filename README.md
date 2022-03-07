# Heart-Attack-Prediction
To predict the risk of a heart attack based on a patient's health condition.


# Objectives
We have data on patients seen by a cardiologist.The main goal is to exploit machine learning techniques on medical data set to assist in identifying the major factors influencing heart attack and that will be able to predict the risk of  heart attack based on a patient's health condition.

# Dataset
The dataset is taken from kaggle, https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

Here we have the description of the features:

age - age in years

sex - sex (0 = female; 1 = male)

cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 0 = asymptomatic)

trtbps - resting blood pressure (in mm Hg on admission to the hospital)

chol - serum cholestoral in mg/dl

fbs - fasting blood sugar > 120 mg/dl (0 = false; 1 = true)

restecg - resting electrocardiographic results (0 = normal; 1 = hypertrophy; 2 = having ST-T wave abnormality)

thalachh - maximum heart rate achieved

exng - exercise induced angina (0 = no; 1 = yes)

oldpeak - ST depression induced by exercise relative to rest

slp - the slope of the peak exercise ST segment (0 = downsloping; 1 = flat; 2 = upsloping)

caa - number of major vessels (0-4)

thall - thallium stress test (1 = fixed defect; 2 = reversable defect; 3 = normal)

output - 0 = less chance of heart attack; 1 = more chance of heart attack

# Methodologies

1.Dataset collection

2.Performed EDA : Handled Outliers , Deleted duplicate rows, visualization and Feature scaling.

3.Created 7 different Classification Models : Logistic Regression, KNN, Decision Tree, SVM, Random Forest, Navie Bayes, XGBoost.
Performed comparative analysis on the techniques used.

4.Visualization

![download](https://user-images.githubusercontent.com/90588183/156969124-97780a2b-7df3-492a-8cf6-2b4d46eec754.png)


![156709823-65af0b4c-068b-48f0-80d4-797d80a5029c](https://user-images.githubusercontent.com/90588183/156958892-1f326de7-b582-4dc4-810d-26b8c0c5baa6.png)

![156709840-c8e5d6dc-9291-462a-9531-ccd59cbb8596](https://user-images.githubusercontent.com/90588183/156958906-aeff39b8-6c12-4a8d-97e2-d9285ac1bfa6.png)


# Libraries used

1.Data Cleaning: numpy, pandas

2.Visualisation: seaborn, matplotlib

3.Feature scaling: MinMaxScaler

4.Splitting to train and test: train_test_split

5.Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score

6.Algorithms: DecisionTreeClassifier, RandomForestClassifier, svm, KNeighborsClassifier, LogisticRegression, GaussianNB, XGBClassifier
