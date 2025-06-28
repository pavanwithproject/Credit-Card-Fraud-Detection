
# 💳 Credit Card Fraud Detection — Machine Learning & Data Analysis

This project applies machine learning to detect fraudulent credit card transactions using a highly imbalanced dataset.

---

## 📂 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions with 492 frauds (Class 1)
- Features are anonymized (V1–V28), plus `Time`, `Amount`, and `Class`

---

## ⚙️ Tools & Libraries
- **Python**, **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib** (for visualization)
- **Scikit-learn**, **SMOTE** (for modeling & handling class imbalance)

---

## 📊 Exploratory Data Analysis (EDA)

### Class Distribution
![Class Distribution](images/class_distribution.png)

- The dataset is highly imbalanced (~0.17% fraud cases)
- Requires resampling techniques for effective model learning

### Correlation Heatmap
![Heatmap](images/heatmap.png)

- Shows feature correlations; helps understand relationships between variables

---

## 🧪 Model Building

### 1. Data Preprocessing
- Normalized `Amount` feature
- Dropped `Time` feature (optional)
- Resampled using **SMOTE** to balance fraud vs non-fraud cases

### 2. Algorithms Used
- Logistic Regression
- Random Forest

### 3. Evaluation Metrics
- **Precision**, **Recall**, **F1 Score**, **Confusion Matrix**, **ROC AUC**

### Confusion Matrix (Example)
![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve
![ROC Curve](images/roc_curve.png)

---

## 🏆 Results
- Logistic Regression: ~91% Recall, 94% Precision on balanced data
- Random Forest: Higher AUC with less false positives

---

## 📁 Files in Repository
- `credit_card_fraud_detection.ipynb`: Jupyter Notebook with full analysis and models
- `images/`: Folder with saved plots (confusion matrix, ROC curve, etc.)
- `README.md`: This file

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/pavanwithproject/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection
   ```
2. Open and run the notebook `credit_card_fraud_detection.ipynb` in Jupyter or Google Colab

---

## 👤 Author
**Pavan**  
GitHub: [pavanwithproject](https://github.com/pavanwithproject)
