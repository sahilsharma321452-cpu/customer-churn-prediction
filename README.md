# Customer Churn Prediction

## Overview

Customer Churn Prediction is a machine learning project that predicts whether a customer is likely to leave a company based on their demographic information, account details, and service usage patterns. The goal is to help businesses identify at-risk customers and take proactive measures to improve customer retention.

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine Learning model training
* Model evaluation and comparison
* Customer churn prediction
* Interactive prediction interface (if deployed using Streamlit)

## Dataset

The dataset contains customer information such as:

* Gender
* Senior Citizen status
* Partner status
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Monthly Charges
* Total Charges
* Churn Status

Target Variable:

* **Churn**

  * Yes: Customer left the company
  * No: Customer stayed with the company

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Streamlit (Optional)

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Customer Churn Prediction

## Model Performance

The model was evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix
* ROC-AUC Score

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Navigate to the project directory:

```bash
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Project Structure

```text
customer-churn-prediction/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── images/
```

## Future Improvements

* Hyperparameter tuning
* Deployment on cloud platforms
* Real-time prediction API
* Advanced ensemble models
* Automated retraining pipeline

## Results

The trained model can accurately predict customer churn and help businesses identify customers who are likely to leave, enabling targeted retention strategies.

## Author

Sahil Sharma

Feel free to contribute, raise issues, or suggest improvements.
