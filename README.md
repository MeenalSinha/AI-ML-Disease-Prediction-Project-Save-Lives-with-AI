# 🩺 AI-ML-Disease-Prediction-Project-Save-Lives-with-AI

## 📌 Overview

The **Heart Disease Predictor** is a machine learning project designed to detect the likelihood of heart disease based on patient health data. Using medical attributes (age, cholesterol, chest pain type, blood pressure, etc.), the model applies classification algorithms to assist in healthcare diagnostics and early disease detection.

This project is built in **Python (Jupyter Notebook/Colab)** and leverages well-known ML libraries for training, evaluation, and predictions.

---

## 🚀 Features

* Data preprocessing & cleaning for healthcare datasets
* Training multiple ML models (Logistic Regression, Random Forest)
* Model evaluation using accuracy, F1-score, and confusion matrix
* Feature importance visualization for medical attributes
* Export trained models (`.pkl`) for deployment
* Simple prediction workflow with user-uploaded patient data

---

## 🛠 Technologies Used

* **Python 3.x**
* **NumPy, Pandas** → Data handling
* **Scikit-learn** → Machine learning algorithms
* **Matplotlib, Seaborn** → Data visualization
* **Joblib** → Model saving & loading
* **Google Colab/Kaggle API** → Dataset management

---

## ⚙ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/IHRM-AI/Heart-Disease-Predictor.git
   cd Heart-Disease-Predictor
   ```

2. **(Optional) Create virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶ Usage

* Open the project in **Google Colab**:
  [Disease\_Predictor\_Save\_lives\_with\_AI.ipynb](https://github.com/MeenalSinha/AI-ML-Disease-Prediction-Project-Save-Lives-with-AI/blob/main/Disease_Predictor_Save_lives_with_AI.ipynb)

* Run the notebook step by step:

  1. Download dataset from Kaggle
  2. Preprocess data (clean missing values, encode categorical features)
  3. Train models (Logistic Regression / Random Forest)
  4. Evaluate performance (accuracy \~84–88%)
  5. Save trained model for reuse

* For **user predictions**:

  * Fill patient data in `heart_user_template.csv`
  * Upload file in Colab
  * The notebook outputs predictions: `0 = No Disease`, `1 = Disease Present`

---

## 📊 Example Workflow

1. Load dataset from Kaggle
2. Handle missing values
3. Feature encoding & scaling
4. Train Logistic Regression & Random Forest models
5. Evaluate accuracy & confusion matrix
6. Save trained model with **Joblib**
7. Predict on new user data

---

## 👨‍💻 Author

**Meenal Sinha**

* 📧 [meenal.sinha09@gmail.com](mailto:meenal.sinha09@gmail.com)

---
