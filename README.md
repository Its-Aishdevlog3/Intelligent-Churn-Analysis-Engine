# 📊 Customer Churn Prediction

This project predicts customer churn in a telecom company using machine learning. It involves data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation. A Random Forest model is used to achieve high accuracy in predicting churn.

---

## 📌 Objective

The objective is to identify customers who are likely to leave the service (churn) so that retention strategies can be applied.

---

## 📁 Dataset

- **Source**: Kaggle Sample Dataset
- **File**: 'WA_Fn-UseC_-Telco-Customer-Churn.csv'
- **Target**: 'Churn' (Yes/No)

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - 'pandas', 'numpy' – data manipulation
  - 'matplotlib', 'seaborn' – visualization
  - 'scikit-learn' – preprocessing, modeling, evaluation


## 🧱 Project Structure

# customer_churn_project/
# │
# ├── data_set/
# │ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
# │
# ├── churn_prediction.py # Main EDA, preprocessing, training script
# ├── venv/ # Python virtual environment (optional)
# ├── requirements.txt # List of required libraries
# └── README.md # Project overview

---

## 📊 Steps Performed

### 1. Data Cleaning

- Removed duplicates and missing values.
- Converted 'TotalCharges' to numeric.
- Replaced null 'TotalCharges' with the median.

### 2. Encoding & Transformation

- Label encoded categorical variables.
- Applied 'StandardScaler' on numerical features.

### 3. Exploratory Data Analysis (EDA)

- Analyzed distribution of churn.
- Visualized data type distributions, pie and count plots.

### 4. Model Training

- Split dataset (80% train / 20% test).
- Trained using **Random Forest Classifier**.
- Achieved accuracy of ~87%.

### 5. Model Evaluation

- Evaluated model with classification report:
  - Precision, Recall, F1-score

---
## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer_churn_project.git
cd customer_churn_project

# Create Virtual Environment (optional)

  python -m venv venv
  venv\Scripts\activate     # On Windows
  # OR
  source venv/bin/activate  # On macOS/Linux

# Install Requirements
  pip install -r requirements.txt

# How to Run
# Run the Python script for full analysis, model training, and evaluation:

  python customer_churn_prediction.py

## 🔍 Results

- **Accuracy**: ~87%
- **Best Performing Model**: Random Forest Classifier

Make sure the dataset is placed in the correct folder path (data_set/) and update the file path in the script if needed.
---

📌 Future Improvements
Add Flask API for online prediction.
Integrate SHAP for model explainability.
Store model as a pickle (.pkl) file and create a UI.

📚 References
Kaggle Sample Dataset


### ✅ Optional: 'requirements.txt' File

Create a file called 'requirements.txt' and include:

pandas
numpy
matplotlib
seaborn
scikit-learn# Intelligent-Churn-Analysis-Engine
