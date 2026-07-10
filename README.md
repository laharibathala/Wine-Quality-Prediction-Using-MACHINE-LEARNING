# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

The Wine Quality Prediction project uses Machine Learning algorithms to predict the quality of wine based on its physicochemical properties. The model is trained on the Wine Quality dataset and classifies wine quality using different classification algorithms.

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that accurately predicts wine quality based on various chemical features.

---

## 📂 Dataset

- Dataset: Wine Quality Dataset
- Source: UCI Machine Learning Repository / Kaggle
- Records: 1,599
- Features: 11 Input Features + 1 Target Variable

### Input Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable

- Quality

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Machine Learning Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## 📁 Project Structure

```
Wine-Quality-Prediction/
│
├── data/
│   └── winequality.csv
│
├── notebooks/
│   └── Wine_Quality_Prediction.ipynb
│
├── images/
│   ├── confusion_matrix.png
│   ├── accuracy_comparison.png
│   └── feature_importance.png
│
├── README.md

```

---

## 📈 Project Workflow

1. Import Dataset
2. Data Preprocessing
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Performance Comparison
11. Prediction

---

## 📊 Model Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📷 Visualizations

The project includes:

- Correlation Heatmap
- Quality Distribution
- Boxplots
- Feature Importance
- Confusion Matrix
- Accuracy Comparison Graph

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Wine-Quality-Prediction.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Run all notebook cells.

---

## 📌 Results

Among all the machine learning algorithms tested, the model with the highest accuracy performed best for predicting wine quality.

Example:

| Model | Accuracy |
| Knn | 0.682462% |
| Logistic Regression | 0.682462% |
| Decision Tree | 0.710769% |
| Random Forest | 0.786462% |
| SVM | 0.707077% |

Replace XX with your actual results.

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Deep Learning Models
- Deployment using Flask or Streamlit
- Real-time Wine Quality Prediction

---
## ⭐ Conclusion

This project demonstrates how Machine Learning techniques can effectively predict wine quality using physicochemical properties. Different classification algorithms were compared, and the best-performing model was identified based on evaluation metrics.
