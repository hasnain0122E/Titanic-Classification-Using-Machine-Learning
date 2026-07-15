# 🚢 Titanic Survival Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

---

# 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using **Supervised Machine Learning Classification Algorithms**.

The project demonstrates a complete machine learning workflow including:

- Data Exploration
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Training Multiple Classification Models
- Model Evaluation
- Best Model Selection

Multiple machine learning algorithms were trained and evaluated using standard classification metrics. Among all the evaluated models, **Support Vector Machine (SVM)** achieved the highest **F1-Score** and was selected as the best-performing model.

---

# 🎯 Objective

The objective of this project is to compare the performance of various classification algorithms on the Titanic dataset and identify the most effective model for predicting passenger survival.

---

# 📂 Dataset

**Dataset:** Titanic - Machine Learning from Disaster

The dataset contains passenger information such as:

- Passenger Class
- Age
- Gender
- Fare
- Family Size
- Embarked Port
- Survival Status (Target Variable)

Target Variable:

```
Survived

0 → Did Not Survive

1 → Survived
```

---

# ⚙️ Machine Learning Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Data Preprocessing
    │
    ▼
Train-Test Split
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Best Model Selection (SVM)
```

---

# 🤖 Classification Algorithms Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Naive Bayes
- Support Vector Machine (SVM)

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

Since F1-Score provides a balanced evaluation of Precision and Recall, it was used as the primary metric for selecting the best model.

---

# 🏆 Best Model

| Model | Selection |
|--------|-----------|
| Support Vector Machine (SVM) | ✅ Best Performing Model |

**Reason:**

- Highest F1-Score
- Strong Precision-Recall Balance
- Best overall classification performance

---

# 📁 Repository Structure

```
ML_P3_Learning_Classification_Algorithm/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── Titanic_Classification.ipynb
│
├── images/
│
├── models/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/hasnain0122E/ML_P3_Learning_Classification_Algorithm.git
```

Navigate to the project directory

```bash
cd ML_P3_Learning_Classification_Algorithm
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📈 Results

After training and evaluating multiple classification algorithms, **Support Vector Machine (SVM)** achieved the best overall performance based on the **F1-Score**, making it the final selected model for Titanic survival prediction.

---

# 📚 Learning Outcomes

This project helped strengthen my understanding of:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Performance Comparison
- Machine Learning Workflow

---

# 🔮 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- Feature Selection Techniques
- Save Trained Models using Joblib
- Model Deployment using Flask or FastAPI
- Interactive Web App using Streamlit

---

# 👨‍💻 Author

**Hasnain Ali**

- GitHub: https://github.com/hasnain0122E
- LinkedIn: *(Add your LinkedIn profile URL here)*

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub!