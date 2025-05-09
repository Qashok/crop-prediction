# 🌾 Crop Prediction using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
An intelligent system that predicts the most suitable crop to cultivate based on soil and environmental conditions using supervised machine learning.

---

## 📌 Table of Contents

- [🚀 Project Motivation](#-project-motivation)
- [📊 Dataset Information](#-dataset-information)
- [🧠 Model Overview](#-model-overview)
- [📈 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🛠️ Technologies Used](#️-technologies-used)
- [💻 How to Run](#-how-to-run)
- [🖼️ Visualizations](#-visualizations)
- [🔮 Future Work](#-future-work)
- [📄 License](#-license)

---

## 🚀 Project Motivation

Choosing the right crop is crucial for maximizing yield and maintaining soil health. Many small-scale farmers rely on experience rather than data. This project uses machine learning to offer data-driven crop recommendations, promoting precision agriculture.

---

## 📊 Dataset Information

- **Source**: [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- **Rows**: ~2,200 samples  
- **Features**:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- **Target**: Crop label (e.g., rice, maize, cotton, etc.)

---

## 🧠 Model Overview

- **Algorithm Used**: Random Forest Classifier (achieved high accuracy)
- **Other models tested**: K-Nearest Neighbors, Decision Tree
- **Evaluation Metrics**: Accuracy, Confusion Matrix

---

## 📈 Exploratory Data Analysis

The notebook includes insightful EDA:
- Heatmap showing feature correlation
- Countplot of crop frequency
- Distribution plots for all input features
- Summary statistics and missing value analysis

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## 💻 How to Run

1. Clone this repository or open it in [Replit](https://replit.com/).
2. Ensure `Crop_recommendation.csv` is in your working directory.
3. Open and run the `crop_prediction.ipynb` notebook.
4. Modify the test input to predict the most suitable crop.

```python
# Example
model.predict([[90, 42, 43, 20.0, 82.0, 6.5, 202.0]])
