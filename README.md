# synent-task8-loanprediction-bhupendrakumar
End-to-end Machine Learning project for predicting loan approval decisions using applicant demographics, financial information, and credit history.


# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Project Overview

Loan approval is one of the most important processes in the banking sector. Financial institutions receive thousands of loan applications and manually evaluating each application can be time-consuming and error-prone.

This project uses Machine Learning techniques to predict whether a loan application will be approved based on applicant information such as income, education, credit history, and loan amount.

Developed as part of the Synent Technologies Data Science Internship Program (Task 8 – Machine Learning Model).

---

## 🎯 Problem Statement

The objective of this project is to build a machine learning model that can automatically predict loan approval status.

The model helps financial institutions:

- Reduce manual effort
- Speed up decision making
- Improve consistency in loan approval processes

---

## 📂 Dataset Information

Dataset: Loan Prediction Dataset

Target Variable:

- Loan_Status

Input Features:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection

Loaded training and testing datasets using Pandas.

### 2. Data Cleaning

Handled missing values using:

- Mode for categorical features
- Median for numerical features

### 3. Exploratory Data Analysis (EDA)

Performed visual analysis using Seaborn and Matplotlib.

Visualizations include:

- Loan Status Distribution
- Gender vs Loan Status
- Education vs Loan Status
- Property Area vs Loan Status
- Credit History vs Loan Status

### 4. Data Preprocessing

- Removed unnecessary columns
- Encoded categorical variables using Label Encoding
- Prepared data for machine learning models

### 5. Train-Test Split

Dataset split into:

- Training Data: 80%
- Validation Data: 20%

Using:

```python
train_test_split(test_size=0.20, random_state=42)
```

### 6. Model Building

Three machine learning models were trained:

#### Logistic Regression

Used as a baseline classification model.

#### Decision Tree Classifier

Used to capture non-linear patterns.

#### Random Forest Classifier

Used ensemble learning for improved prediction performance.

---

## 🤖 Machine Learning Models

| Model | Purpose |
|---------|----------|
| Logistic Regression | Baseline Classification |
| Decision Tree | Rule-Based Prediction |
| Random Forest | Ensemble Learning |

---

## 📊 Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Confusion Matrix
- Classification Report

Best Performing Model:

✅ Random Forest Classifier

Accuracy:

**Update after notebook execution**

Example:

```text
Random Forest Accuracy: 84.55%
```

---

## 📈 Key Insights

- Credit History is one of the strongest factors affecting loan approval.
- Applicants with positive credit history have a significantly higher approval rate.
- Property Area and Education also contribute to prediction performance.
- Ensemble models provide better performance than single decision trees.

---

## 📷 Project Screenshots

### Loan Approval Distribution

<img width="571" height="455" alt="download" src="https://github.com/user-attachments/assets/d2310580-c483-4c47-9d8b-eb4b3350a0a8" />



---

### Credit History Analysis

<img width="571" height="433" alt="download" src="https://github.com/user-attachments/assets/414b7efb-d998-4c9a-8ff5-ea75c58e2183" />



---

### Property Area Analysis

<img width="571" height="432" alt="download" src="https://github.com/user-attachments/assets/6196eb6a-b6b8-4aae-af5a-c1405f0824cb" />


---

### Confusion Matrix

<img width="481" height="374" alt="download" src="https://github.com/user-attachments/assets/3c036fbb-0d1c-42a1-a0a5-1662ca9987cc" />


---

## 🚀 How To Run

Clone Repository

```bash
git clone https://github.com/bktechnology513/synent-task8-loanprediction-bhupendrakumar
```

Move to Project Folder

```bash
cd synent-task8-loanprediction-bhupendrakumar
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Launch Notebook

```bash
jupyter notebook
```

Run all cells.

---

## 📁 Repository Structure

```text
synent-task8-loanprediction-bhupendrakumar
│
├── data
│   ├── train.csv
│   └── test.csv
│
├── notebooks
│   └── LoanPrediction.ipynb
│
├── images
│   ├── loan_status.png
│   ├── credit_history.png
│   └── confusion_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🎓 Internship Task Mapping

Task: Advanced Level – Task 8

Requirements Completed:

✔ Data Preprocessing

✔ Feature Selection

✔ Train/Test Split

✔ Model Training

✔ Model Evaluation

✔ Machine Learning Prediction

---

## 👨‍💻 Author

Bhupendra Kumar

Data Science Intern

Synent Technologies Internship Program

---

## 📜 License

This project is developed for educational and internship purposes.
