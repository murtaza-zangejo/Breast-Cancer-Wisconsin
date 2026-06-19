# 🩺 Breast Cancer Wisconsin Classification Using Machine Learning

## 📌 Project Overview

This project implements a complete **Machine Learning classification pipeline** to predict whether a breast tumor is **Benign (non-cancerous)** or **Malignant (cancerous)** using the Breast Cancer Wisconsin Diagnostic dataset.

The objective is to develop and compare multiple supervised learning algorithms, perform exploratory data analysis, preprocess the data, train classification models, and evaluate their performance using different evaluation metrics.

The dataset contains features computed from digitized images of fine needle aspirate (FNA) samples of breast masses. These features describe characteristics of cell nuclei such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

# 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Understand feature relationships using visualization techniques
* Clean and preprocess the dataset
* Apply feature scaling
* Train multiple classification models
* Compare model performance
* Evaluate models using accuracy, precision, recall, F1-score, and confusion matrix
* Identify the best-performing machine learning model


# 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

Dataset characteristics:

| Property       | Value                 |
| -------------- | --------------------- |
| Total Samples  | 569                   |
| Features       | 30 Numerical Features |
| Target Classes | Benign / Malignant    |
| Problem Type   | Binary Classification |
| Missing Values | None                  |

Target:

* **M → Malignant**
* **B → Benign**


# 🛠️ Technologies Used

## Programming Language

* Python

## Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn


# 🔄 Machine Learning Workflow

```
Data Collection
        ↓
Data Exploration
        ↓
Data Cleaning
        ↓
Feature Analysis
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Performance Comparison


📊 Exploratory Data Analysis

Performed analysis includes:

### Dataset Understanding

* Shape of dataset
* Data types
* Statistical summary
* Missing value detection

### Visualization Implemented:

* Correlation Matrix
* Heatmap
* Histogram plots
* Box plots
* Feature distribution analysis


# ⚙️ Data Preprocessing

Steps performed:

### 1. Removing unnecessary columns Removed:

* ID column
* Unnamed: 32

### 2. Label Encoding

Target variable converted using Label Encoder:

Malignant → 1
Benign → 0

### 3. Feature Scaling

Standardization applied using:

StandardScaler()

This improves performance for distance-based and gradient-based algorithms.


# 🤖 Machine Learning Models Implemented

The following classification algorithms were trained and compared:

## 1. Logistic Regression

A statistical classification algorithm used as a baseline model.

## 2. K-Nearest Neighbor (KNN)

Classifies samples based on similarity with neighboring data points.

## 3. Support Vector Machine (SVM)

Finds the optimal hyperplane to separate malignant and benign classes.

## 4. Decision Tree Classifier

A tree-based model that learns decision rules from features.


## 5. Random Forest Classifier

An ensemble learning method combining multiple decision trees.


# 📈 Model Evaluation

Models were evaluated using:

## Accuracy Score

Measures overall prediction correctness.

## Precision

Measures how many predicted positive cases are actually positive.

## Recall

Important for medical applications because it measures detection capability.

## F1 Score

Balance between precision and recall.

## Confusion Matrix

Visual representation of:

* True Positive
* True Negative
* False Positive
* False Negative


# 📌 Results

The models were compared based on their classification performance.



# 🚀 Installation & Setup

Clone repository:

```bash
git clone https://github.com/yourusername/Breast-Cancer-Wisconsin.git
```

Move into project directory:

```bash
cd Breast-Cancer-Wisconsin
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter


# 💡 Key Learnings

Through this project:

* Learned complete ML classification workflow
* Performed medical dataset analysis
* Improved understanding of feature engineering
* Compared multiple classification algorithms
* Applied evaluation metrics for imbalanced healthcare problems


# 🔮 Future Improvements

Possible improvements:

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Deployment using Streamlit
* Create REST API using FastAPI
* Add Explainable AI (SHAP/LIME)
* Deploy model on cloud platforms


# ⚠️ Disclaimer

This project is developed for educational and research purposes only.

The model should not be used as a medical diagnostic system.

