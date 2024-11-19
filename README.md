# Titanic_Survival_Prediction
This project analyzes the Titanic dataset to predict the survival of passengers based on various features such as their age, gender, ticket class, and other details. The objective is to build a machine learning model that can classify passengers as survivors or non-survivors.

### Key Objectives:
- **Data Exploration**: Understand the dataset by visualizing and summarizing the key features.
- **Feature Engineering**: Create new features and preprocess data to improve model performance.
- **Model Building**: Train multiple machine learning models to predict survival and compare their performance.
- **Evaluation**: Use metrics such as accuracy, precision, recall, F1-score, and ROC AUC to evaluate the models.

### Dataset Details:
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Features**:
  - **Pclass**: Ticket class (1 = First, 2 = Second, 3 = Third)
  - **Sex**: Gender of the passenger
  - **Age**: Age of the passenger
  - **SibSp**: Number of siblings/spouses aboard
  - **Parch**: Number of parents/children aboard
  - **Fare**: Ticket fare
  - **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Target Variable**: 
  - **Survived**: Survival status (0 = No, 1 = Yes)

### Key Techniques & Algorithms Used:
1. **Exploratory Data Analysis (EDA)**:
   - Visualizations using **Seaborn** and **Matplotlib** to analyze survival trends based on different features.
   - Identifying missing data and outliers.
   
2. **Feature Engineering**:
   - Imputation of missing values (e.g., age, embarked) using KNN Imputer.
   - Encoding categorical variables (e.g., one-hot encoding for embarkation ports).
   - Creating new features like family size and title extraction from names.

3. **Preprocessing**:
   - Standardization of numerical features using **StandardScaler**.
   - Handling missing data and preparing the dataset for modeling.

4. **Model Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score, and ROC AUC.
   - Confusion Matrix for visualizing true positives, true negatives, false positives, and false negatives.
  

