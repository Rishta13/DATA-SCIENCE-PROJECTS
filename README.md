 📊 Data Science Projects

A collection of end-to-end data science and analysis projects built using Python. Each project covers real-world datasets with a focus on exploratory data analysis, data visualisation, and deriving actionable insights.

**Tools & Libraries:** Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn


 🗂️ Projects

### 1. 🫀 Heart Disease Risk Analysis
**File:** `Heart_Disease_Analysis.ipynb`

Analysed a clinical dataset to identify key risk factors associated with heart disease using EDA and statistical visualisation.

**Highlights:**
- Identified chest pain type and resting blood pressure as top predictors via correlation analysis
- Used countplots, heatmaps, and histograms to surface patterns across 13 clinical variables
- Framed findings as potential early screening criteria for at-risk patients

**Tech:** Pandas · Matplotlib · Seaborn

---

### 2. 💳 Credit Fraud Detection — Dealing with Imbalanced Datasets
**File:** `Credit_Fraud_||_Dealing_with_Imbalanced_Datasets.ipynb`

Explored techniques to handle severely imbalanced data (fraud = ~0.17% of transactions) and built classifiers to detect fraudulent credit card transactions.

**Highlights:**
- Applied **Random Under-Sampling** and **SMOTE (Synthetic Minority Over-sampling)** to balance classes
- Compared 4 classifiers: Logistic Regression, KNN, SVC, and Decision Tree using cross-validation and ROC-AUC scores
- Used **t-SNE** for dimensionality reduction and cluster visualisation
- Implemented a Neural Network (Keras) and compared performance under both sampling strategies
- Removed outliers using IQR method on high-correlation features (V14, V12, V10)

**Tech:** Pandas · Scikit-learn · Imbalanced-learn · Keras · Matplotlib · Seaborn

---

### 3. 🧠 Mental Health EDA + Prediction
**File:** `Mental_Health_(EDA_+_Prediction).ipynb`

Performed exploratory data analysis on a mental health survey dataset to uncover patterns in workplace mental health, followed by predictive modelling.

**Highlights:**
- Analysed survey responses across demographics, company size, and remote work status
- Identified key factors influencing likelihood of seeking mental health treatment
- Built a prediction model to classify treatment-seeking behaviour

**Tech:** Pandas · Matplotlib · Seaborn · Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rishta13/DATA-SCIENCE-PROJECTS.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn keras
   ```
3. Open any notebook in Jupyter or Google Colab and run cells in order.
