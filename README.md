
#  Health Insurance Premium Prediction

##  Project Overview
This project predicts health insurance premiums using Machine Learning. It analyzes customer information such as age, gender, BMI, smoking status, number of children, and region to estimate insurance charges accurately. The goal is to support fair premium pricing and improve risk assessment for insurance providers.

---

##  Objectives
- Predict health insurance charges using Linear Regression.
- Identify the factors that influence insurance premiums.
- Evaluate the model using performance metrics.
- Support data-driven decision-making for insurance companies.

---

##  Dataset
The dataset contains the following features:

- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges (Target Variable)

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

##  Exploratory Data Analysis (EDA)
The dataset is analyzed to:
- Understand feature distributions.
- Detect missing values and outliers.
- Explore relationships between variables.
- Identify factors affecting insurance charges.

---

##  Machine Learning Model
Three Linear Regression models are developed:

1. Simple Linear Regression (Age)
2. Multiple Linear Regression (Age + BMI)
3. Linear Regression using all available features

Categorical variables are encoded before training, and the dataset is split into training and testing sets.

---

##  Model Evaluation
The model is evaluated using:
- Mean Squared Error (MSE)
- R-squared (R² Score)

These metrics measure prediction accuracy and model performance.

---

##  Results
The model successfully predicts health insurance premiums based on customer information. Features such as age, BMI, and smoking status have a significant impact on insurance charges. The model can assist insurance companies in pricing policies more accurately.

---

##  Future Enhancements
- Apply advanced regression algorithms.
- Perform hyperparameter tuning.
- Build a web application for premium prediction.
- Deploy the model using Flask or Streamlit.

---

