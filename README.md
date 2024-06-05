Insurance Charge Predictor
Welcome to the Insurance Charge Predictor project! This application predicts insurance charges based on user-provided information using various machine learning models.

Key Features
Data Preprocessing: Cleaning and preparing data.
EDA: Understanding data patterns and relationships.
Outlier Handling: Managing outliers to improve model performance.
Machine Learning Algorithms: Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
Model Persistence: Models saved using Pickle.
Deployment: Hosted using Streamlit for easy accessibility.
How It Works
Users input the following details:

Age
BMI
Sex
Number of Children
Smoking Status
Region in India
They can then select a machine learning model (Linear Regressor, Decision Tree Regressor, Random Forest Regressor) to predict the insurance charge.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/insurance-charge-predictor.git
Navigate to the project directory:
bash
Copy code
cd insurance-charge-predictor
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit application:
bash
Copy code
streamlit run app.py
Usage
Open your browser and go to http://localhost:8501. Enter the required details, select the machine learning model, and click "Predict" to get the estimated insurance charge.

Models
Linear Regression: Assumes a linear relationship between features and target.
Decision Tree Regressor: Splits data into subsets based on feature values.
Random Forest Regressor: Builds multiple decision trees and merges their predictions.

Thank you for using the Insurance Charge Predictor! We hope this tool provides valuable insights and predictions for your insurance needs.
