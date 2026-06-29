# Week 3 – Baseline Predictive Modeling Plan

## Objective

Develop a baseline machine learning model to predict whether a hotel booking will be cancelled (`is_canceled`).

---

## Problem Statement

Booking cancellations lead to revenue loss for hotels. The objective of Week 3 is to build a predictive model that identifies bookings with a high probability of cancellation.

---

## Machine Learning Workflow

### Step 1: Load the Cleaned Dataset
- Import the cleaned dataset prepared during Week 1.

### Step 2: Select Features
Use relevant features such as:
- Lead Time
- ADR
- Total Stay Nights
- Total Guests
- Market Segment
- Deposit Type
- Customer Type
- Previous Cancellations
- Booking Changes
- Special Requests

Target Variable:
- `is_canceled`

### Step 3: Data Preprocessing
- Encode categorical variables.
- Prepare the dataset for machine learning.

### Step 4: Train-Test Split
- Split the dataset into 80% training and 20% testing data.

### Step 5: Build Baseline Models
- Logistic Regression
- Decision Tree Classifier

### Step 6: Model Evaluation
Evaluate the models using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### Step 7: Model Comparison
Compare both models and identify the better-performing model for predicting booking cancellations.

---

## Expected Outcome

Develop a baseline predictive model that helps hotels identify high-risk bookings and supports customer retention and revenue optimization.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook