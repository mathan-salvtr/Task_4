# Task 4 – Logistic Regression (Breast Cancer Classification)

## 📌 Objective
To build a binary classification model using Logistic Regression that predicts whether a tumor is malignant (M) or benign (B) based on various medical features.

---

## 📂 Dataset
- **File**: `data.csv`
- **Source**: Breast Cancer Wisconsin Dataset
- **Target Column**: `diagnosis` (M = Malignant, B = Benign)

---

## ✅ Steps Performed

### 1. Data Import & Exploration
- Loaded the dataset using pandas
- Dropped unused columns: `id`, `Unnamed: 32`
- Converted `diagnosis` to binary (M = 1, B = 0)

### 2. Data Preprocessing
- Separated features and target
- Applied `StandardScaler` to normalize input features

### 3. Train-Test Split
- Used `train_test_split()` from sklearn to split into 80% training and 20% testing

### 4. Logistic Regression Model
- Trained a Logistic Regression classifier
- Printed model summary and default threshold output

### 5. Threshold Tuning & Sigmoid Visualization
- Retrieved predicted probabilities
- Applied a custom threshold (0.3) for higher sensitivity
- Compared performance with confusion matrix and classification report
- Visualized F1-score across thresholds
- Plotted the Sigmoid function used in logistic regression

### 6. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1)
- ROC Curve & AUC Score

---

## 📊 Output
- Confusion matrix and evaluation metrics
- ROC curve plotted
- F1 Score vs Threshold visualized
- Sigmoid curve explained

---

## 🧠 Tools & Libraries
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (`LogisticRegression`, `StandardScaler`, `train_test_split`, `classification_report`, etc.)

---

## 🔎 Insights
- Logistic Regression is effective for binary classification.
- Threshold tuning is crucial in healthcare applications to balance sensitivity and specificity.
- Sigmoid function transforms model output to a probability score for class prediction.

---

