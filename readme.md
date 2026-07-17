# Heart Disease Prediction using Machine Learning

> An end-to-end machine learning project demonstrating the complete workflow of data preprocessing, supervised learning, unsupervised learning, model evaluation, and performance comparison using the Heart Disease dataset.

---

## Project Overview

This project was developed as part of my Machine Learning coursework to explore the complete machine learning pipeline for a real-world healthcare classification problem. The objective is to predict whether a patient has heart disease based on various clinical attributes.

Rather than focusing only on model accuracy, this project emphasizes systematic data analysis, reproducible experimentation, model comparison, and interpretation of results.

---

## Research Motivation

Heart disease remains one of the leading causes of death worldwide. Early prediction can support physicians in identifying high-risk patients and making timely clinical decisions.

This project demonstrates how classical machine learning algorithms can be applied to medical datasets to build predictive models while comparing supervised and unsupervised learning approaches.

---

## Dataset

- **Dataset:** Heart Disease Dataset
- **Samples:** 270
- **Features:** 13 clinical attributes
- **Target:** Disease (Binary Classification)

The dataset contains patient information including age, blood pressure, cholesterol, chest pain type, ECG results, maximum heart rate, exercise-induced angina, and several other clinical measurements.

---

# Machine Learning Workflow

The project follows a complete machine learning workflow:

1. Dataset exploration
2. Data preprocessing
3. Feature selection
4. Data standardization
5. Train-test split
6. Pipeline creation
7. Model training
8. Model evaluation
9. Supervised vs Unsupervised comparison
10. Reflection and discussion

---

# Supervised Learning Models

Two supervised learning algorithms were implemented:

- Logistic Regression
- Random Forest Classifier

Each model was implemented using Scikit-learn Pipelines to ensure reproducible preprocessing and training.

---

# Unsupervised Learning

The dataset was also explored as an unsupervised learning problem using:

- K-Means Clustering

The clustering performance was evaluated using the Silhouette Score and compared with the supervised learning results.

---

# Evaluation Metrics

Classification models were evaluated using:

- Accuracy
- Precision
- Recall
- Confusion Matrix

For the unsupervised approach:

- Silhouette Score

---

# Results

Among the evaluated models, **Logistic Regression achieved the best overall performance** for this dataset.

**Performance Summary**

| Model | Accuracy | Precision | Recall |
|--------|----------|-----------|--------|
| Logistic Regression | **85.19%** | **78.57%** | **91.67%** |
| Random Forest | 81.48% | 76.92% | 83.33% |

The unsupervised K-Means clustering approach achieved a Silhouette Score of **0.1719**, indicating relatively weak natural cluster separation compared to the supervised models.

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Repository Structure

```
.
├── heart_disease.csv
├── Heart_Disease_ML.ipynb
├── README.md
└── requirements.txt
```

---

# Key Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- Machine learning pipelines
- Binary classification
- Clustering
- Model evaluation
- Performance comparison
- Experimental analysis using Scikit-learn

---

# Future Improvements

Potential future work includes:

- Hyperparameter optimization
- Cross-validation
- Ensemble learning techniques
- Explainable AI (SHAP/LIME)
- Deep learning approaches
- Clinical decision support integration

---

# Academic Purpose

This repository was developed as part of my undergraduate Machine Learning coursework. Its primary purpose is to demonstrate practical implementation skills, reproducible experimentation, and analytical thinking in applying machine learning techniques to healthcare data.

---

## Author

**Md. Maidul Islam**

B.Sc. in Computer Science and Technology 
China University of Petroleum, Beijing

**Research Interests**

- Machine Learning
- Artificial Intelligence
- Data Mining
- Healthcare AI
- Pattern Recognition

---

> *I welcome constructive feedback, research discussions, and academic collaboration opportunities.*