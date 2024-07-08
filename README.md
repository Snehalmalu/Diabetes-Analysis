Diabetes Prediction with Machine Learning
Python Version License: MIT Jupyter

Data Preprocessing
This project aims to develop a machine learning model to predict the onset of diabetes based on various health and lifestyle factors. The project involves data preprocessing, model building, evaluation, and hyperparameter tuning.

The dataset contains various features related to health indicators and lifestyle habits. The data is preprocessed to handle missing values, standardize numerical features, and encode categorical variables.

Model Building
Two machine learning models are explored for predicting diabetes:

Logistic regression: A statistical model that predicts the probability of an outcome based on a set of independent variables. more

Decision tree: A tree-like structure that classifies instances based on a series of decision rules. more

Pipelines are used to streamline the preprocessing and modeling steps.

Model Evaluation
The models are evaluated using two metrics:

Accuracy: The proportion of correctly classified instances.

F1 score: A measure of the balance between precision and recall. more

Hyperparameter tuning is performed using GridSearchCV to optimize the models for F1 score. more

Results
The best-performing model is selected based on the highest F1 score achieved during hyperparameter tuning. The selected model is saved as a pickle file for deployment in an application.

Stramlit Application
Installation
To install and run this project, follow these steps:

# Clone the repository
git clone https://github.com/PETERMUTWIRI/MERISKILL_DIABETES_ANALYSIS

# Change directory
cd MERISKILL_DIABETES_ANALYSIS

# Install dependencies
pip install -r requirements.txt

# Run the FastAPI application
streamlit run streamlit.py
Access the web application at http://localhost:8501 in your browser.

Access my well funtioning application at https://diabetes-analysis.streamlit.app/

Conclusion
The project demonstrates the application of machine learning for predicting diabetes risk based on health and lifestyle factors. The application can be used in applications to provide personalized risk assessments and inform preventive measures.
