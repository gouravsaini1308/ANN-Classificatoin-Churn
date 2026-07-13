# ANN Customer Churn Prediction

This project implements an Artificial Neural Network (ANN) to predict whether a bank customer is likely to leave the bank (customer churn). The model is trained on the Bank Customer Churn dataset and deployed as an interactive Streamlit web application where users can enter customer information and receive real-time churn predictions.

## Live Demo

https://ann-classificatoin-churn-qhjfrwxpapppp5gerdp3nowe.streamlit.app/

## Overview

Customer churn prediction is an important business problem in the banking industry. Retaining existing customers is significantly more cost-effective than acquiring new ones. This project leverages Deep Learning to analyze customer attributes and predict the probability of churn.

The application provides an intuitive interface where users can input customer details and instantly receive predictions along with the churn probability.

## Features

- Customer churn prediction using Artificial Neural Network (ANN)
- Interactive Streamlit web application
- Real-time prediction with churn probability
- Data preprocessing using saved encoders and scaler
- Supports categorical feature encoding
- Easy-to-use interface

## Dataset

The project uses the **Bank Customer Churn Modelling** dataset.

### Input Features

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

### Target Variable

- **Exited**
  - 0 → Customer stays
  - 1 → Customer leaves the bank

## Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Pickle

## Model Training

The ANN model was trained using TensorFlow/Keras with the following workflow:

- Data preprocessing
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Neural Network training
- Model evaluation
- Model saving for deployment

The trained model and preprocessing objects are stored and loaded during inference to ensure consistent predictions.

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <repository-folder>
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment.

Install the required packages:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Then open the local URL displayed in your terminal.

## Model Workflow

1. User enters customer information.
2. Categorical variables are encoded.
3. Numerical features are scaled.
4. The processed data is passed to the trained ANN model.
5. The model predicts:
   - Churn Probability
   - Customer Churn Prediction

## Future Improvements

- Hyperparameter optimization
- Improved feature engineering
- Model explainability using SHAP or LIME
- Docker deployment
- CI/CD pipeline integration
- Cloud deployment on AWS or Azure

## Author

**Gourav Saini**

## License

This project is intended for educational and learning purposes.

## Overview

Customer churn prediction is an important business problem in the banking industry. Retaining existing customers is significantly more cost-effective than acquiring new ones. This project leverages Deep Learning to analyze customer attributes and predict the probability of churn.

The application provides an intuitive interface where users can input customer details and instantly receive predictions along with the churn probability.

## Features

- Customer churn prediction using Artificial Neural Network (ANN)
- Interactive Streamlit web application
- Real-time prediction with churn probability
- Data preprocessing using saved encoders and scaler
- Supports categorical feature encoding
- Easy-to-use interface

## Dataset

The project uses the **Bank Customer Churn Modelling** dataset.

### Input Features

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

### Target Variable

- **Exited**
  - 0 → Customer stays
  - 1 → Customer leaves the bank

## Technologies Used

- Python
- TensorFlow / Keras
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Pickle

## Model Training

The ANN model was trained using TensorFlow/Keras with the following workflow:

- Data preprocessing
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Neural Network training
- Model evaluation
- Model saving for deployment

The trained model and preprocessing objects are stored and loaded during inference to ensure consistent predictions.

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <repository-folder>
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment.

Install the required packages:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Then open the local URL displayed in your terminal.

## Model Workflow

1. User enters customer information.
2. Categorical variables are encoded.
3. Numerical features are scaled.
4. The processed data is passed to the trained ANN model.
5. The model predicts:
   - Churn Probability
   - Customer Churn Prediction

## Future Improvements

- Hyperparameter optimization
- Improved feature engineering
- Model explainability using SHAP or LIME
- Docker deployment
- CI/CD pipeline integration
- Cloud deployment on AWS or Azure

## Author

**Gourav Saini**

## License

This project is intended for educational and learning purposes.
