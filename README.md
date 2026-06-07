# Customer Churn Prediction

A machine learning project focused on predicting customer churn using classification models and customer behavioral data.

The project analyzes customer demographics, financial attributes, and account activity to identify customers who are likely to leave a bank. Multiple machine learning models are evaluated and compared to determine the most effective approach for churn prediction.

---

## Project Objective

The primary objective of this project is to build predictive models that can identify customers at risk of churning. Early identification of potential churners enables businesses to implement targeted retention strategies, improve customer satisfaction, and reduce revenue loss.

The project applies data preprocessing, exploratory data analysis, feature engineering, and machine learning techniques to classify customers into churn and non-churn categories.

---

## Dataset

The dataset contains customer-level information including:

* Customer demographics
* Credit score
* Geography (Country)
* Gender
* Age
* Account balance
* Number of products
* Estimated salary
* Active membership status
* Churn status (Target Variable)

### Target Variable

* `0` = Customer Retained
* `1` = Customer Churned

---

## Key Features

* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Categorical Variable Encoding
* Feature Engineering
* Logistic Regression Classification
* Random Forest Classification
* XGBoost Classification
* Cross-Validation
* ROC-AUC Evaluation
* Confusion Matrix Analysis
* Feature Importance Analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

## Methodology

### Data Preprocessing

* Missing value inspection
* Duplicate value checking
* Encoding categorical variables
* One-hot encoding for geographical features
* Feature scaling

### Exploratory Data Analysis

The dataset was analyzed to understand:

* Customer churn distribution
* Demographic characteristics
* Financial behavior
* Relationships between features and churn

### Model Development

Three machine learning models were implemented:

#### Logistic Regression

A baseline classification model used to establish benchmark performance.

#### Random Forest

An ensemble learning method that combines multiple decision trees to improve predictive performance.

#### XGBoost

A gradient boosting algorithm designed for high-performance classification tasks.

### Model Evaluation

Models were compared using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Cross-Validation ROC-AUC

---

## Results

Among the models evaluated, **Random Forest** achieved the strongest overall performance based on ROC-AUC and classification metrics.

Key findings include:

* High accuracy in identifying non-churn customers.
* Moderate success in detecting churn customers.
* Strong predictive capability using customer behavioral and financial features.

---

## Feature Importance

Feature importance analysis identified the following variables as the strongest predictors of customer churn:

1. Age
2. Number of Products
3. Estimated Salary
4. Account Balance
5. Credit Score

These factors play a significant role in determining customer retention behavior.

---

## Repository Structure

```bash
Customer-Churn-Prediction/
│
├── CustomerChurnPrediction.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Navigate to the project directory:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook CustomerChurnPrediction.ipynb
```

Run all cells sequentially to reproduce the analysis and model results.

---

## Business Impact

Customer churn prediction enables organizations to:

* Improve customer retention
* Reduce acquisition costs
* Identify high-risk customers
* Design targeted marketing campaigns
* Increase long-term profitability

---

## Future Improvements

* Hyperparameter tuning
* Class imbalance handling
* SHAP explainability analysis
* Deployment as a web application
* Real-time churn prediction dashboard

---

## Author

Ashis Pal

Data Analytics | Machine Learning | Econometrics | Quantitative Finance

---

