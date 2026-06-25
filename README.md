# Customer Churn Prediction & Customer Segmentation

## Overview

This project predicts customer churn using a **Random Forest Classifier** and performs **Customer Segmentation** using the **K-Means Clustering** algorithm on the IBM Telco Customer Churn dataset.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model building, evaluation, hyperparameter tuning, and customer segmentation.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* One-Hot Encoding
* Correlation Heatmap
* Random Forest Classification
* Model Evaluation
* Cross Validation
* Hyperparameter Tuning using GridSearchCV
* Feature Importance Analysis
* Customer Segmentation using K-Means
* Business Insights

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
├── images/
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* VS Code

---

## Machine Learning Models

### Random Forest Classifier

Used to predict whether a customer is likely to churn.

### K-Means Clustering

Used to segment customers into different groups based on their characteristics.

---

## Model Performance

| Metric                     | Value      |
| -------------------------- | ---------- |
| Test Accuracy              | **77.79%** |
| Cross Validation Accuracy  | **77.92%** |
| Best GridSearchCV Accuracy | **78.45%** |
| ROC-AUC Score              | **0.8356** |

---

## Important Features

The most influential features affecting customer churn are:

* Total Charges
* Tenure Months
* Monthly Charges
* Contract Type
* Dependents

---

## Customer Segments

The K-Means algorithm identified three customer segments:

* High Risk New Customers
* Budget Loyal Customers
* Premium Loyal Customers

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git
```

2. Navigate to the project directory.

```bash
cd Customer-Churn-Prediction
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Open the notebook located in the `notebooks` folder and run all cells.

---

## Future Improvements

* Compare additional machine learning models.
* Deploy the model using Streamlit or Flask.
* Build an interactive dashboard.
* Improve feature engineering and model performance.

---

## Author

**Rishabh Bhardwaj**

Computer Science Engineering Student
