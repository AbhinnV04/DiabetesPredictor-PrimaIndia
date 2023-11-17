# Diabetes Prediction Project

This project focuses on predicting the likelihood of diabetes in patients based on diagnostic measurements using the Pima Indian Diabetes Dataset. The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases and aims to diagnostically predict whether a patient has diabetes or not. The patients in the dataset are females at least 21 years old of Pima Indian heritage.

## Dataset Description

- **Source:** [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Objective:** Diagnostically predict diabetes based on medical predictor variables.
- **Variables:** The dataset includes medical predictor variables such as the number of pregnancies, BMI, insulin level, age, and more.
- **Acknowledgements:** Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus.

## Exploratory Data Analysis (EDA)

Performed EDA using Python to understand the dataset, visualize distributions, and identify patterns. The exploratory analysis laid the foundation for building a predictive model.

## Model Building

Utilized machine learning techniques, including Logistic Regression, Random Forest, and XGBoost, to create a predictive model for diabetes detection. The model underwent optimization and evaluation to ensure robust performance.

## Deployment

The model is deployed using Streamlit, providing an interactive web interface for users to input medical data and receive predictions about the likelihood of diabetes.

## Project Structure

- `notebooks/`: Contains Jupyter notebooks for EDA and model development.
- `model/`: Stores the trained and optimized machine learning model files.
- `streamlit/`: Holds the Streamlit app files for model deployment.
- `dataset/`: The dataset used for training and testing the model.

## Usage
### A. Use the deployed webapp:
[Click here](google.com)

### B. Run this locally:
1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Streamlit app:
    ```bash
    streamlit run streamlit/app.py
    ```

Visit the Streamlit app in your web browser to interact with the deployed model.

Feel free to have fun with this!