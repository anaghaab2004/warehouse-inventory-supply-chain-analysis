# Predictive Modeling and Optimization in Logistics Systems

##  Project Overview

This project was completed as part of **Week 4 of the YUVA Internship – Logistics Data Analyst Intern**.

The project focuses on applying **predictive modeling and data analysis techniques** to a logistics dataset to predict **delivery time deviation** and identify important operational factors that can influence logistics performance.

Python and machine learning techniques were used to prepare the data, train multiple regression models, evaluate their performance, identify important features, and propose optimization strategies for logistics operations.

---

##  Objectives

The main objectives of this project are:

- Predict delivery time deviation using logistics-related variables.
- Compare different machine learning regression models.
- Evaluate model performance using appropriate metrics.
- Perform cross-validation to assess model consistency.
- Identify important factors influencing delivery time deviation.
- Develop practical optimization recommendations for logistics operations.

---

##  Dataset

The dataset contains **32,065 records and 26 columns** representing different logistics and operational factors.

### Key Features

- Vehicle GPS latitude and longitude
- Fuel consumption rate
- ETA variation
- Traffic congestion level
- Warehouse inventory level
- Loading and unloading time
- Handling equipment availability
- Order fulfillment status
- Weather condition severity
- Port congestion level
- Shipping costs
- Supplier reliability score
- Lead time
- Historical demand
- Route risk level
- Customs clearance time
- Driver behavior score
- Fatigue monitoring score
- Disruption likelihood score
- Delay probability

### Target Variable

**`delivery_time_deviation`**

The target represents the deviation in delivery time and is treated as a continuous numerical variable for regression modeling.

---

##  Technologies Used

- **Python**
- **Google Colab**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computation
- **Matplotlib** – Data visualization
- **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and model evaluation

---

##  Methodology

The project followed the following workflow:

```text
Data Loading
     ↓
Data Preparation
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Cross-Validation
     ↓
Feature Importance Analysis
     ↓
Prediction Visualization
     ↓
Logistics Optimization Recommendations
