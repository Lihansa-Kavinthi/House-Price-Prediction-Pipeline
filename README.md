# 🏠 House Price Prediction Pipeline 📈

This repository contains a comprehensive predictive modeling workflow for estimating house prices using advanced regression techniques. The project focuses on transforming raw real estate data into actionable insights through rigorous feature engineering and model evaluation.

---

### 🚀 Project Overview
The objective of the `predictive modeling.ipynb` script is to accurately forecast housing prices based on a variety of features. It addresses common data challenges such as text-to-numeric encoding and model selection to achieve the best predictive performance.

### ✨ Key Features
* **🛠️ Automated Encoding**: Utilizes `pd.get_dummies` to seamlessly convert categorical text data into a numerical format suitable for machine learning.
* **📏 Robust Scaling**: Implements feature scaling to ensure that all variables contribute equally to the model's predictions.
* **🤖 Multi-Model Approach**: Implements and compares multiple algorithms, including **Linear Regression** and **Random Forest Regressor**.
* **📊 Visual Analysis**: Includes scatter plot visualizations to compare predicted prices against actual test values, providing a clear view of model accuracy.

---

### 🛠️ Technical Stack
* **Python**: Core language for the data pipeline.
* **Pandas**: Essential for data loading, cleaning, and one-hot encoding.
* **Scikit-Learn**: Powering the train-test split, regression models, and scaling.
* **Matplotlib**: Used for generating performance scatter plots.

---

### 🧬 Workflow Logic
1. **Data Loading**: Imports raw data from `house prediction.csv`.
2. **Feature Engineering**: Fixes column naming issues and handles categorical variables through dummy encoding.
3. **Training**: Splits the data (e.g., 404 training samples) and fits regression models to the 500+ generated features.
4. **Evaluation**: Visualizes residuals and prediction errors to verify model reliability.

---

### 📂 How to Run

1. Ensure `house prediction.csv` is in the same folder as the notebook.
2. Install the requirements:

```bash
pip install pandas scikit-learn matplotlib
```
Run the cells in `predictive modeling.ipynb` to execute the full pipeline! 🎊
