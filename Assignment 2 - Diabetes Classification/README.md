# What to expect:
Dataset:diabetes_binary_classification_data.csv is a clean dataset of 253,680 survey
responses to the Center for Disease Control's (CDC) survey. The target variable
Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes.
This dataset has 21 feature variables and is not balanced.

Three models are used to analyze the data:
- Logistic regression
- Random forest
- XGBoost

RFE is used to create a model with fewer less important features. We compare the models with each other and also the models after RFE has been used.