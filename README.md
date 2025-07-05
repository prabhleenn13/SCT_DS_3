# 🚀 Decision Tree Classifier on Bank Marketing Dataset (Internship Task 3)

This repository contains my **internship Task 3 project**, where I built and evaluated a Decision Tree Classifier on the **Bank Marketing dataset** from the UCI Machine Learning Repository.  

The goal of this project is to predict whether a client will subscribe to a term deposit based on various personal, social, and economic attributes.  

---

## 📂 Files in this repository

| File | Description |
|-------|-------------|
| `bank_marketing_decision_tree.ipynb` | Jupyter notebook containing the complete workflow: data loading, exploration, preprocessing, model training, evaluation, and visualization |
| `full_dataset_decision_tree.png` | Visualization of the decision tree trained on the entire dataset (max depth = 5) |


---

## ⚙️ How to use this project

### ✅ Requirements
- Jupyter Notebook / JupyterLab
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - pydotplus
  - graphviz

### ✅ Steps to run
1️⃣ **Clone this repository**
```bash
git clone https://github.com/YourUsername/decision-tree-internship.git
or download as a ZIP and extract.

2️⃣ Get the dataset

Download the dataset from UCI Bank Marketing

Place bank-additional-full.csv in the same directory as the notebook (or update the path in the code).

3️⃣ Launch Jupyter Notebook

bash
Copy code
jupyter notebook
Open bank_marketing_decision_tree.ipynb and run all cells.

📊 Dataset Overview
The dataset contains information on direct marketing campaigns (phone calls) of a Portuguese banking institution.

Target:
y — Has the client subscribed to a term deposit? (yes/no)

📈 Project highlights
✅ One-hot encoding for categorical features
✅ Decision Tree Classifier using entropy criterion
✅ Train-test split (80% train / 20% test, stratified by target)
✅ Evaluation: accuracy, confusion matrix, classification report
✅ Visualizations: decision tree plots, top feature importances

💡 Possible future improvements
✨ Hyperparameter tuning (e.g., GridSearchCV)
✨ Apply cross-validation for better model reliability
✨ Address class imbalance (e.g., SMOTE, class weights)
✨ Compare performance with other models (e.g., Random Forest, Logistic Regression)
