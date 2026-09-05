# Flight Delay Prediction using Machine Learning

## Overview
A Binary Classification project that predicts whether a flight will arrive 15 or more minutes late.

### Target
- `0` → Not delayed by 15+ minutes
- `1` → Delayed by 15+ minutes

## Workflow
1. Data loading and exploration
2. Data cleaning
3. Exploratory Data Analysis
4. Feature selection
5. Train-test split
6. Categorical encoding and preprocessing
7. Classification model training
8. Model evaluation
9. Model comparison
10. Best model selection
11. Model saving

## Algorithms
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

## Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Features Used
- Year
- Quarter
- Month
- Day of Month
- Day of Week
- Marketing Airline Network
- Origin
- Destination
- Scheduled Departure Time
- Scheduled Arrival Time
- Scheduled Elapsed Time
- Distance
- Distance Group

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib, Jupyter Notebook

## Project Files
```text
Flight-Delay-Prediction/
├── flight_delay_prediction.ipynb
├── flight_delay.csv
├── flight_delay_model.pkl
├── README.md
├── requirements.txt
├── project_description.txt
└── AUTHOR.txt
```

## Installation
```bash
pip install -r requirements.txt
```

## How to Run
Open `flight_delay_prediction.ipynb` in Jupyter Notebook/JupyterLab and run the cells from top to bottom. Keep `flight_delay.csv` in the same folder.

## Data Leakage
Post-flight outcome variables such as actual arrival delay are not used as prediction features, avoiding data leakage.

## Author
**Tanvi Dubey**
