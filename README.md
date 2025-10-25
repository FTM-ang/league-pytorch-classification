# 🧠 League of Legends Win Prediction

**Course:** Introduction to Neural Networks and PyTorch — IBM / Coursera

Project that implements a full ML pipeline: data preprocessing, EDA, model training, evaluation, and feature importance.

---

## 📊 Goal
Predict whether a team wins (`win` = 1) or loses (`win` = 0) from match statistics.

---

## ⚙️ Technologies Used
- Python  
- PyTorch  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🧩 Key Steps
1. **Data Loading & Cleaning** – Reading and preparing the dataset.  
2. **Exploratory Data Analysis (EDA)** – Understanding distributions, correlations, and outliers.  
3. **Feature Scaling** – Standardizing numerical features using `StandardScaler`.  
4. **Model Building** – Implementing logistic regression using PyTorch’s `nn.Linear` layer.  
5. **Training with Regularization** – Applying L2 regularization to improve generalization.  
6. **Model Evaluation** – Confusion matrix, classification report, ROC-AUC curve.  
7. **Feature Importance** – Extracting learned weights to interpret feature impact.  

---

## 📈 Results
- Baseline logistic regression achieved near-random performance (accuracy ≈ 0.51, AUC ≈ 0.51).
- In the future, I would use a neural network architecture with the Adam optimizer for this type of problem.
- The feature importance analysis highlights which in-game metrics have the strongest influence on the win probability.

هل تبغيني 

---

## 🖼️ Visualizations
- Confusion Matrix  
- ROC Curve  
- Top 15 Most Important Features  

---
## Target distribution
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/88237032-1b17-47fd-b242-cfb66c212ffe" />

## Correlation heatmap (for top 10 features with highest variance)
<img width="850" height="767" alt="image" src="https://github.com/user-attachments/assets/9a7a03e9-877c-4f48-942e-de810d1e332f" />

