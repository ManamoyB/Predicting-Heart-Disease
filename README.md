# Heart Disease Prediction | ML Classification Using Multiple Algorithms

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Library-blue?style=flat-square&logo=scikit-learn)
![KNN](https://img.shields.io/badge/KNN-Algorithm-green?style=flat-square)
![Decision Tree](https://img.shields.io/badge/Decision%20Tree-Classifier-purple?style=flat-square)
![Random Forest](https://img.shields.io/badge/Random%20Forest-Ensemble-darkgreen?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=flat-square&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)

---

## 📌 Project Overview

**Heart Disease Prediction** is a comprehensive machine learning classification project that predicts the likelihood of heart disease in patients using multiple algorithms. The project demonstrates the complete ML pipeline: data exploration, feature engineering, model training, cross-validation, and comparative performance analysis.

**Key Highlights:**
- ✅ **Multi-Algorithm Comparison**: KNN, Decision Tree, Random Forest
- ✅ **Complete ML Pipeline**: EDA → Feature Engineering → Model Training → Evaluation
- ✅ **Cross-Validation**: 10-fold CV for robust performance assessment
- ✅ **Feature Engineering**: Scaling, encoding, correlation analysis
- ✅ **303 Patient Records**: Real-world medical dataset
- ✅ **14 Health Attributes**: Comprehensive patient health data
- ✅ **Production Insights**: Comparative model performance metrics
- ✅ **Educational Value**: Step-by-step Jupyter notebook walkthrough

---

## 🎯 Why This Matters

Cardiovascular disease remains one of the **leading causes of death globally**:

- **Early Detection**: ML models can identify high-risk patients early
- **Healthcare Intervention**: Enable preventive measures before complications
- **Clinical Support**: Assist healthcare professionals in diagnosis
- **Data-Driven Decisions**: Objective assessment based on medical metrics
- **Accessibility**: Brings diagnostic insights to resource-limited settings
- **Scalability**: Automated screening for large patient populations

This project demonstrates **production-grade classification modeling** in healthcare.

---

## 📊 Dataset Overview

### Patient Health Data
- **Total Records**: 303 patient instances
- **Features**: 14 medical attributes
- **Target**: Heart disease presence (binary: 0 = No, 1 = Yes)
- **Real-World Data**: UCI Machine Learning Repository

### Feature Descriptions

| Feature | Type | Description | Range |
|---------|------|-------------|-------|
| **age** | Numeric | Patient age in years | 29-77 |
| **sex** | Categorical | Gender (M/F) | Binary |
| **cp** | Categorical | Chest pain type (4 types) | 0-3 |
| **trestbps** | Numeric | Resting blood pressure (mmHg) | 94-200 |
| **chol** | Numeric | Cholesterol level (mg/dl) | 126-564 |
| **fbs** | Categorical | Fasting blood sugar > 120 | Binary |
| **restecg** | Categorical | Resting ECG results | 0-2 |
| **thalach** | Numeric | Max heart rate achieved | 60-202 |
| **exang** | Categorical | Exercise-induced angina | Binary |
| **oldpeak** | Numeric | ST depression by exercise | 0-6.2 |
| **slope** | Categorical | Slope of ST segment | 0-2 |
| **ca** | Numeric | Coronary vessels colored (fluoroscopy) | 0-4 |
| **thal** | Categorical | Thalassemia type | 0-3 |
| **target** | Binary | Heart disease presence | 0-1 |

---

## ✨ Key Features

### 1. **Comprehensive Data Exploration**
   - Exploratory Data Analysis (EDA) with visualizations
   - Correlation heatmap analysis
   - Target class distribution analysis
   - Feature relationship exploration

### 2. **Robust Feature Engineering**
   - Missing value handling
   - Categorical encoding (One-Hot Encoding)
   - Feature scaling (StandardScaler)
   - Correlation-based feature selection
   - Outlier detection & treatment

### 3. **Multiple Classification Algorithms**
   - **K-Nearest Neighbors (KNN)**: Distance-based classifier
   - **Decision Tree**: Tree-based classifier with interpretability
   - **Random Forest**: Ensemble method with multiple trees

### 4. **Cross-Validation & Evaluation**
   - 10-Fold Cross-Validation
   - Accuracy, Precision, Recall, F1-Score metrics
   - Confusion matrices
   - Model comparison analysis

### 5. **Jupyter Notebook**
   - Step-by-step explanations
   - Commented code for learning
   - In-line visualizations
   - Performance metrics & insights

### 6. **Visualization Suite**
   - Correlation heatmaps
   - Distribution plots (histograms, KDE)
   - Box plots for outlier detection
   - Model comparison charts
   - Confusion matrices

---

## 🛠️ Tech Stack

### Data Processing & Analysis
- **Pandas** - Data manipulation, cleaning, aggregation
- **NumPy** - Numerical operations, array processing
- **Scikit-learn** - ML algorithms, preprocessing, evaluation

### Machine Learning Algorithms
- **KNN (K-Nearest Neighbors)** - Instance-based learning
- **Decision Tree Classifier** - Tree-based classification
- **Random Forest Classifier** - Ensemble learning

### Data Preprocessing
- **StandardScaler** - Feature normalization
- **OneHotEncoder** - Categorical encoding
- **Train-Test Split** - Data partitioning
- **Cross Validation** - Model validation strategy

### Visualization & Notebooks
- **Matplotlib** - Static plotting library
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

### Development Environment
- **Python 3.8+** - Programming language
- **Git** - Version control
- **pip** - Package manager

---

## 📈 Machine Learning Pipeline

```
Dataset (303 patients, 14 features)
        ↓
   [DATA LOADING]
        ↓
   [EDA & ANALYSIS]
   - Visualizations
   - Correlation analysis
   - Feature distribution
        ↓
   [DATA PREPROCESSING]
   - Handling missing values
   - Outlier detection
   - Feature scaling
   - One-Hot Encoding
        ↓
   [FEATURE ENGINEERING]
   - Correlation-based selection
   - Feature scaling
   - Normalization
        ↓
   [TRAIN-TEST SPLIT] (80-20)
        ↓
   [MODEL TRAINING]
   ├── KNN Classifier
   ├── Decision Tree
   └── Random Forest
        ↓
   [CROSS VALIDATION] (10-Fold)
        ↓
   [PERFORMANCE EVALUATION]
   - Accuracy, Precision, Recall
   - F1-Score, Confusion Matrix
        ↓
   [MODEL COMPARISON]
   └── Best model selection
```

---

## 🤖 Algorithm Details

### K-Nearest Neighbors (KNN)
- **How it works**: Classifies based on K nearest neighbors
- **Hyperparameter**: K value (tested: 1, 3, 5, 7, 9)
- **Pros**: Simple, interpretable, no training phase
- **Cons**: Computationally expensive at inference
- **Best for**: Non-linear decision boundaries

### Decision Tree Classifier
- **How it works**: Recursive binary splitting on features
- **Hyperparameters**: max_depth, min_samples_split
- **Pros**: Interpretable, handles non-linear relationships
- **Cons**: Prone to overfitting
- **Best for**: Feature importance analysis

### Random Forest Classifier
- **How it works**: Ensemble of multiple decision trees
- **Hyperparameters**: n_estimators, max_depth
- **Pros**: Reduces overfitting, handles non-linearity
- **Cons**: Less interpretable, computationally intensive
- **Best for**: High accuracy predictions

---

## 📊 Performance Metrics

### Evaluation Framework
```
Accuracy  = (TP + TN) / (TP + TN + FP + FN)
Precision = TP / (TP + FP)
Recall    = TP / (TP + FN)
F1-Score  = 2 * (Precision * Recall) / (Precision + Recall)
```

### Cross-Validation Strategy
- **Method**: 10-Fold Cross-Validation
- **Rationale**: Robust model evaluation on limited data
- **Benefit**: Better generalization estimates

### Expected Results
- **KNN**: 60-70% accuracy (varies with K)
- **Decision Tree**: 75-85% accuracy
- **Random Forest**: 80-90% accuracy

---

## 🎮 What You Can Do

- **Explore EDA**: Understand patient data distributions & relationships
- **Learn Feature Engineering**: See preprocessing & scaling techniques
- **Train Models**: Run classification algorithms on medical data
- **Compare Algorithms**: Evaluate performance across different models
- **Analyze Predictions**: Review confusion matrices & error analysis
- **Visualize Data**: Create publication-quality medical data plots
- **Extend Project**: Add new algorithms or feature engineering techniques
- **Understand Cross-Validation**: Learn robust model evaluation methods

---

## 📂 Project Structure

```
Predicting-Heart-Disease/
├── Heart Disease Predictions.ipynb    # Main analysis notebook
├── dataset.csv                         # Patient health data (303 records)
├── README.md                           # Documentation
│
└── images/
    ├── correlation_heatmap.png        # Feature correlation visualization
    ├── target_distribution.png        # Class distribution chart
    ├── feature_distributions.png      # Individual feature histograms
    ├── model_comparison.png           # Algorithm performance comparison
    └── confusion_matrices.png         # Model confusion matrices
```

---

## 🚀 Installation & Setup

### Prerequisites
```bash
✓ Python 3.8+
✓ pip (Python package manager)
✓ Jupyter Notebook (optional, for interactive analysis)
✓ Virtual environment (recommended)
```

### Clone Repository
```bash
git clone https://github.com/ManamoyB/Predicting-Heart-Disease.git
cd Predicting-Heart-Disease
```

### Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Or install from requirements:
```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook
```bash
jupyter notebook
```

Open `Heart Disease Predictions.ipynb` in your browser.

---

## 📖 Usage Guide

### 1. **Load and Explore Data**
```python
# The notebook loads and displays dataset overview
# Check shape, data types, missing values
# Visualize feature distributions
```

### 2. **Analyze Relationships**
```python
# Create correlation heatmap
# Identify feature importance
# Understand disease patterns
```

### 3. **Prepare Data**
```python
# Handle missing values
# Encode categorical features
# Scale numerical features
# Split train/test data
```

### 4. **Train Models**
```python
# Train KNN with different K values
# Train Decision Tree
# Train Random Forest
# Perform 10-Fold Cross-Validation
```

### 5. **Compare Performance**
```python
# View accuracy scores
# Analyze confusion matrices
# Compare precision/recall/F1
# Select best model
```

---

## 📈 Development Process

### Phase 1: Problem Understanding
- Studied cardiovascular disease domain
- Identified key health indicators
- Defined classification objective (binary prediction)

### Phase 2: Data Exploration
- Loaded UCI Heart Disease dataset
- Analyzed 14 medical features
- Visualized distributions & correlations
- Identified class imbalance

### Phase 3: Feature Engineering
- Applied StandardScaler for numerical features
- One-Hot Encoded categorical features
- Performed correlation analysis
- Selected most important features

### Phase 4: Model Development
- Implemented KNN classifier
- Trained Decision Tree model
- Built Random Forest ensemble
- Configured cross-validation

### Phase 5: Model Evaluation
- Calculated accuracy, precision, recall, F1
- Generated confusion matrices
- Compared algorithm performance
- Analyzed prediction errors

### Phase 6: Analysis & Insights
- Identified best-performing model
- Explained feature importance
- Discussed trade-offs between algorithms
- Prepared recommendations

---

## 🧠 Key Learning Outcomes

This project teaches:

1. **Data Preprocessing**: Handling medical data with categorical & numerical features
2. **EDA Techniques**: Visualization & statistical analysis of health data
3. **Feature Scaling**: Why and how to normalize features
4. **Categorical Encoding**: One-Hot Encoding for categorical variables
5. **Model Selection**: Choosing algorithms for binary classification
6. **Cross-Validation**: Robust model evaluation on limited data
7. **Algorithm Comparison**: Understanding trade-offs between KNN, Decision Tree, Random Forest
8. **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score in healthcare context

---

## 🚀 Future Improvements

- [ ] **Hyperparameter Tuning** - GridSearchCV for optimal parameters
- [ ] **XGBoost/LightGBM** - Modern gradient boosting algorithms
- [ ] **Feature Importance** - SHAP values or permutation importance
- [ ] **SMOTE** - Handle class imbalance if present
- [ ] **Web Deployment** - Flask/FastAPI web interface
- [ ] **Model Explainability** - LIME for local interpretability
- [ ] **Ensemble Voting** - Combine multiple models
- [ ] **Real-time Prediction** - Interactive patient assessment tool
- [ ] **ROC-AUC Analysis** - Comprehensive threshold analysis
- [ ] **Statistical Testing** - P-values for model comparisons

---

## ⚠️ Important Disclaimer

**Medical Guidance**: This project is for **educational purposes only** and should NOT be used for:

- Clinical diagnosis without professional validation
- Treatment recommendations
- Medical decision-making
- Patient care without doctor consultation

Always consult qualified healthcare professionals for medical decisions.

---

## 📊 Model Comparison Summary

| Algorithm | Type | Interpretability | Speed | Accuracy | Best For |
|-----------|------|-----------------|-------|----------|----------|
| **KNN** | Instance-based | High | Slow | Medium | Non-linear patterns |
| **Decision Tree** | Tree-based | Very High | Fast | Medium-High | Feature importance |
| **Random Forest** | Ensemble | Medium | Medium | High | Best accuracy |

---

## 💻 Code Example

```python
# Load data
import pandas as pd
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import RandomForestClassifier

# Load dataset
df = pd.read_csv('dataset.csv')
X = df.drop('target', axis=1)
y = df['target']

# Preprocessing
scaler = StandardScaler()
X_scaled = scaler.fit_transform(X)

# Train-test split
X_train, X_test, y_train, y_test = train_test_split(
    X_scaled, y, test_size=0.2, random_state=42
)

# Train model
model = RandomForestClassifier(n_estimators=100, random_state=42)
model.fit(X_train, y_train)

# Cross-validation
cv_scores = cross_val_score(model, X_train, y_train, cv=10)
print(f"CV Accuracy: {cv_scores.mean():.2%}")

# Evaluation
accuracy = model.score(X_test, y_test)
print(f"Test Accuracy: {accuracy:.2%}")
```

---

## 📞 Contact & Support

**Author:** Manamoy Banerjee

**Connect:**
- **GitHub**: [@ManamoyB](https://github.com/ManamoyB)
- **LinkedIn**: [Manamoy's Profile](https://linkedin.com/in/your-profile)
- **Email**: [your.email@example.com]

**Questions or Issues:**
- Open a [GitHub Issue](https://github.com/ManamoyB/Predicting-Heart-Disease/issues)
- Review Jupyter notebook for detailed explanations
- Check UCI ML Repository for dataset information

---

## 📄 License

This project is for educational purposes. Feel free to fork, modify, and learn from it.

---

## ⭐ If This Helped You

If you found this project useful:
- ⭐ **Star** this repository
- 🍴 **Fork** to build your own classification project
- 💬 **Share** with your network
- 📧 **Mention** in your portfolio/resume

---

## 🙌 Credits & Acknowledgments

- **UCI Machine Learning Repository** - Heart disease dataset
- **Scikit-learn** - Excellent ML library & documentation
- **Pandas & NumPy** - Data manipulation powerhouses
- **Healthcare Community** - Medical data insights

---

**Last Updated:** June 2026 | **Status:** Active Learning | **Python 3.8+** | **Classification Project**
