# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the likelihood of heart disease based on patient medical attributes. The project performs exploratory data analysis, feature engineering, model training, and evaluation using multiple classification algorithms.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals identify high-risk patients and take preventive measures.

This project uses Machine Learning techniques to analyze patient health data and predict the presence of heart disease.

---

## 🚀 Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Correlation analysis and feature selection
- Feature scaling using StandardScaler
- One-Hot Encoding for categorical features
- Model training using multiple algorithms
- Cross-validation based evaluation
- Performance comparison of models

---

## 📊 Dataset Information

The dataset contains **303 patient records** with the following attributes:

| Feature | Description |
|----------|-------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Cholesterol level |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia |
| target | Heart Disease (1 = Yes, 0 = No) |

---

## 🛠 Technologies Used

### Programming Language
- Python

### Libraries
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

### 1. K-Nearest Neighbors (KNN)
- Tested multiple values of K
- Evaluated using 10-Fold Cross Validation

### 2. Decision Tree Classifier
- Tree-based classification model

### 3. Random Forest Classifier
- Ensemble learning method
- Multiple decision trees combined for better performance

---

## 📈 Workflow

```text
Dataset
   │
   ▼
Data Exploration
   │
   ▼
Feature Engineering
   │
   ▼
One-Hot Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train/Test Preparation
   │
   ▼
Model Training
   │
   ├── KNN
   ├── Decision Tree
   └── Random Forest
   │
   ▼
Cross Validation
   │
   ▼
Performance Evaluation
```

---

## 📷 Exploratory Data Analysis

The notebook includes:

- Correlation Heatmap
- Feature Distribution Histograms
- Target Class Distribution
- Feature Relationship Analysis

---

## 📂 Project Structure

```text
Predicting-Heart-Disease/
│
├── Heart Disease Predictions.ipynb
├── dataset.csv
├── README.md
│
└── images/
    ├── correlation_heatmap.png
    ├── target_distribution.png
    └── model_comparison.png
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ManamoyB/Predicting-Heart-Disease.git
```

Move into the project directory:

```bash
cd Predicting-Heart-Disease
```

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Heart Disease Predictions.ipynb
```

---

## 📋 Requirements

```text
Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
```

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Feature importance visualization
- XGBoost implementation
- Deployment using Flask/FastAPI
- Interactive web dashboard
- Real-time patient prediction interface

---

## 👨‍💻 Author

**Manamoy B**

GitHub:
https://github.com/ManamoyB

---

## 📜 License

This project is intended for educational and learning purposes.

Feel free to fork, modify, and improve the project.

---

⭐ If you found this project useful, consider giving it a star.
