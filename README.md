NAME :MANGAPATI DILEEP KUMAR

COMPANY :CODTECH IT SOLUTIONS

ID :CT08DS2465

Domain :ARTIFICAL INTELLIGENCE

Duration :15TH JUNE 2024 to 15TH JULY 2024

Mentor :G.SRAVANI
![firsttaskoutput](https://github.com/user-attachments/assets/097177ec-1cf7-4498-9b00-82def6a45972)


##Overview of the Project: This project involves preprocessing the Titanic dataset and training a logistic regression model to predict passenger survival. The key steps include data loading, preprocessing, model training, and evaluation.

Data Loading:

The Titanic dataset is loaded from a URL using pandas, and the first few rows are displayed to understand the data structure. Feature Selection:

Essential features (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked) are selected, and the target variable (Survived) is identified for the analysis. Preprocessing:

Missing values in numerical features (Age, Fare) are filled with median values, and categorical features (Embarked) are filled with the most frequent value. Numerical features are scaled using StandardScaler, and categorical features are one-hot encoded using OneHotEncoder. These preprocessing steps are combined using ColumnTransformer. Data Splitting and Model Training:

The data is split into training and testing sets using train_test_split. A logistic regression model is defined and incorporated into a pipeline along with the preprocessing steps. The model is trained on the training set. Model Evaluation:

The model makes predictions on the test set. A custom function evaluates the model's performance using accuracy, precision, recall, and F1-score, and prints these metrics to provide insights into the model's effectiveness.
