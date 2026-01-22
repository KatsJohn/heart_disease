# Heart Failure Prediction – Supervised Machine Learning

This repository contains a Jupyter Notebook that explores and solves a **supervised machine learning classification problem** focused on **predicting heart failure** based on clinical and demographic data.

The project walks through the complete data science workflow: data loading, exploratory data analysis (EDA), preprocessing, model training, and evaluation using multiple machine learning algorithms.

---

## 📌 Project Overview

Cardiovascular diseases (CVDs) are among the leading causes of death worldwide. Early detection of heart failure can significantly improve patient outcomes. In this project, machine learning models are trained to predict the presence of heart disease using structured patient data.

The notebook is designed to be educational and practical, combining theory, visualization, and hands-on implementation.

---

## 🧠 Models Used

Several supervised learning algorithms are implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier

Each model is trained, evaluated, and compared using appropriate performance metrics.

---

## 📊 Dataset

* The dataset is loaded from a CSV file (`heart.csv`)
* Contains clinical features such as age, sex, chest pain type, cholesterol, blood pressure, and more
* Target variable indicates the presence or absence of heart disease

> **Note:** The dataset path in the notebook is configured for Google Colab and Google Drive. You may need to update the path when running locally.

---

## 🔍 Workflow

1. **Import Libraries** – NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, etc.
2. **Data Loading** – Read and inspect the dataset
3. **Exploratory Data Analysis (EDA)** – Visualizations and statistical insights
4. **Data Preprocessing**

   * Handling categorical variables
   * Feature scaling
   * Train-test split
5. **Model Training** – Train multiple classifiers
6. **Evaluation**

   * Accuracy
   * Confusion Matrix
   * Classification Report
7. **Model Comparison** – Identify the best-performing model

---

## 📈 Visualizations

The notebook includes:

* Distribution plots
* Correlation heatmaps
* Feature comparison plots
* Model performance visualizations

These help in understanding the data and interpreting model behavior.

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)

Click the badge at the top of the notebook or upload the file directly to Colab:

* Ensure the dataset is available in your Google Drive
* Update the file path if necessary

### Option 2: Run Locally

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook heart_failure_prediction_project1.ipynb
   ```
4. Update the dataset path and run all cells

---

## 📁 File Structure

```
├── heart_failure_prediction_project1.ipynb
├── heart.csv   # dataset (not included unless added)
└── README.md
```

---

## 🛠 Tools & Libraries

* Python 3
* NumPy
* Pandas
* Matplotlib
* Seaborn
* scikit-learn
* Google Colab (optional)

---

## 🎯 Purpose

This project is ideal for:

* Learning supervised machine learning
* Practicing end-to-end ML workflows
* Understanding healthcare-related prediction problems
* Academic coursework or portfolio projects

---

## 📜 License

This project is for educational purposes. Feel free to use, modify, and experiment with the code.

---

## 👤 Author

Created as part of a supervised machine learning project on heart failure prediction.

Happy coding ❤️
