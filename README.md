# Classification with Logistic Regression
# 🧠 Logistic Regression Binary Classifier - Breast Cancer Detection

This project demonstrates how to build a **binary classification model** using **Logistic Regression** to detect whether a tumor is **malignant (M)** or **benign (B)** using the Breast Cancer dataset.

---

## 📌 Objective

To classify tumors as malignant or benign using logistic regression.

---

## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📁 Dataset Info

- **Source**: Breast cancer dataset (uploaded as `data.csv`)
- **Target Column**: `diagnosis` (B = 0, M = 1)
- **Features**: 30 numerical features + ID column
- **Rows**: ~570+

---

## 📈 Workflow

### 1. Data Preprocessing

- Removed unnecessary columns: `id`, `Unnamed: 32`
- Encoded the `diagnosis` column:  
  - `M` → 1 (malignant)  
  - `B` → 0 (benign)
- Handled all features as numerical

### 2. Train/Test Split

- Split data into 80% training and 20% testing sets
- Used stratified sampling to maintain class balance

### 3. Feature Scaling

- Applied **StandardScaler** to normalize feature values

### 4. Model Training

- Trained a **Logistic Regression** classifier using `sklearn`

### 5. Evaluation

- Metrics:
  - **Confusion Matrix**
  - **Precision, Recall, F1-score**
  - **ROC Curve & AUC Score**

### 6. Visualization

- **ROC Curve** shows tradeoff between true positive and false positive rate
- **Sigmoid Function** plotted to understand probability output

---
