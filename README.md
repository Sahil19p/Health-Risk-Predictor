# Health Risk Prediction System

## Overview
A Machine Learning project that predicts an individual's health risk level based on lifestyle and health-related factors.

The project uses a Random Forest Classifier and provides an interactive web interface built using Streamlit.

## Features
- Health risk prediction
- Interactive user input form
- Lifestyle factor visualization
- Data preprocessing and exploratory data analysis
- Label encoding of categorical variables
- Machine Learning model training and evaluation
- Saved model and encoders for prediction

## Input Features
- Age
- Diet Quality
- Exercise Days per Week
- Sleep Hours
- Stress Level
- BMI
- Smoking
- Alcohol Consumption
- Family History of Disease

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Plotly
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning
The notebook explores:
- Logistic Regression
- Random Forest Classifier

The trained Random Forest model and LabelEncoder objects are saved using Pickle.

## Project Structure

```text
Health-Risk-Model/
│
├── app.py
├── health_risk_predict.ipynb
├── Health_risk_predict.pkl
├── label_encoders.pkl
├── synthetic_health_data.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Health-Risk-Model
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
python -m streamlit run app.py
```

## Dataset
The project uses a synthetic health dataset containing 4,000 records and 10 columns.

## Disclaimer
This project is developed for educational and learning purposes only. Predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.