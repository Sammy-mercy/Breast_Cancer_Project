# 🩺 Breast Cancer Classification using Support Vector Machines (SVM)

---

## 📌 Project Overview
This project uses the **built-in Breast Cancer dataset from `sklearn.datasets`** to explore the effectiveness of **Support Vector Machines (SVM)** for cancer classification.  
The aim is to:
- Build an SVM model
- Optimize it using **GridSearchCV**
- Evaluate and compare results

---

## 📂 Dataset Information
- Built-in dataset from `sklearn.datasets.load_breast_cancer`
- Features: Tumor characteristics (mean radius, texture, perimeter, area, etc.)
- Target: **0 (Malignant)** or **1 (Benign)**

---

## 🎯 Objectives
- Load and inspect the dataset
- Perform light exploratory data analysis (EDA)
- Split data into training and testing sets
- Train SVM model without hyperparameter tuning
- Implement GridSearchCV for hyperparameter optimization
- Compare performance between base SVM and optimized SVM
- Draw insights and conclusions

---

## 🎯 Objectives
- Predict **loan repayment status**.
- Compare **Decision Tree** vs **Random Forest** classifiers.
- Evaluate which algorithm performs better.

---

## 🛠 Tools & Libraries
- **Python 3.8+**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook**

---

## 🔍 Workflow
1. Import and load dataset from sklearn
2. Perform basic EDA:
   - Distribution checks
   - Correlation heatmaps
3. Split dataset into training and test sets
4. Train base SVM model without GridSearchCV
5. Import and configure GridSearchCV:
   - Parameters tuned: C, kernel, gamma
6. Train optimized SVM model using GridSearchCV
7. Evaluate both models using:
   - Accuracy score
   - Confusion Matrix
   - Classification Report
8. Compare results and discuss conclusions

---

## 📈 Key Findings
- The initial SVM model performed well but lacked fine-tuned accuracy.
- GridSearchCV significantly improved performance by optimizing hyperparameters:
    - Best kernel: 'rbf'
    - Optimal C and gamma values improved generalization.
- Conclusion: Hyperparameter tuning is critical for SVM effectiveness.

---

## 📦 Installation & Usage
```bash
# 1️⃣ Clone the repository
git clone https://github.com/Sammy-mercy.git

# 2️⃣ Navigate into the project directory
cd Breast_Cancer_Project

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Open the Jupyter Notebook
jupyter notebook
```
---

## 📌 Future Improvements
- Apply feature scaling (StandardScaler) to improve performance further
- Compare SVM with other algorithms like Logistic Regression and Random Forest
- Implement RandomizedSearchCV for faster hyperparameter tuning
- Deploy as a simple web app for real-time predictions

---

## 📜 License
This project is licensed under the MIT License.
