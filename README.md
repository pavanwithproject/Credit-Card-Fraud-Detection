# 💳 Credit Card Fraud Detection using PaySim Dataset

This project demonstrates how to detect fraudulent financial transactions using a machine learning pipeline. It uses the PaySim simulation dataset and applies logistic regression, SMOTE for balancing, and meaningful visualizations to interpret the data.

---

## 📁 Dataset

* **Source**: [PaySim Dataset on Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)
* **Filename**: `paysim.csv` (rename after extracting)
* **Features**:

  * `step`, `type`, `amount`, `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`, `isFraud`

---

## ⚙️ Technologies Used

* Python 3.x
* Jupyter Notebook
* Pandas, NumPy
* Scikit-learn
* Seaborn & Matplotlib
* Imbalanced-learn (SMOTE)

---

## 📊 Visualizations

Generated and saved in the `images/` folder:

* Class distribution
* Log-scaled amount distributions
* Fraud by transaction type
* Hourly fraud activity
* ROC Curve with AUC

---

## 🧪 Model & Pipeline

1. Data Cleaning & Exploration
2. Feature Engineering (Log transform on `amount`)
3. SMOTE for class imbalance
4. Logistic Regression
5. Evaluation with:

   * Confusion Matrix
   * Classification Report
   * ROC-AUC Score

---

## 📝 Results

* **Model**: Logistic Regression
* **AUC Score**: \~0.99 (varies with data split)
* **Imbalanced classes** handled using SMOTE

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone 
cd Fraud-Detection-PaySim
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Download Dataset

* Visit: [https://www.kaggle.com/datasets/ealaxi/paysim1](https://www.kaggle.com/datasets/ealaxi/paysim1)
* Download and extract
* Rename CSV to `paysim.csv` and place it in the project folder

### 4. Run the Notebook

```bash
jupyter notebook fraud_detection_paysim.ipynb
```

---

## 📁 Project Structure

```
Fraud-Detection-PaySim/
│
├── images/                    # Saved visualizations
├── paysim.csv                # Dataset file
├── fraud_detection_paysim.ipynb   # Jupyter notebook (main project)
├── requirements.txt          # Dependencies               
└── README.md                 # Project documentation
```


---

Feel free to star ⭐ this repo or fork 🍴 for future reference!
