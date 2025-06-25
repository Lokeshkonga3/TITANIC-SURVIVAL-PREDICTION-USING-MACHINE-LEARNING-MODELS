# TITANIC-SURVIVAL-PREDICTION-USING-MACHINE-LEARNING-MODELS
# 🚢 Titanic Dataset - Survival Prediction (Regression & Classification Models)

This project demonstrates a machine learning pipeline for predicting survival on the Titanic dataset using **Linear Regression** and **Decision Tree Classifier**. It includes data cleaning, feature encoding, model training, and visual analysis.

---

## 📁 Files Included

- `titanic.csv` – Dataset used for analysis
- `titanic_modeling.ipynb` – Jupyter Notebook / Python script with complete code
- `README.md` – Project documentation

---

## 🎯 Objectives

- Load and clean the Titanic dataset
- Handle missing values
- Encode categorical variables
- Split data into training and test sets
- Train and evaluate:
  - A **Linear Regression** model (for educational purposes)
  - A **Decision Tree Classifier** (for classification)
- Visualize survival trends across key variables like gender, age, and passenger class

---

## 🧹 Data Preprocessing Summary

| Step                         | Description                                  |
|------------------------------|----------------------------------------------|
| Drop Irrelevant Columns      | `PassengerId`, `Name`, `Ticket`, `Cabin`     |
| Fill Missing `Age`           | Use median value                             |
| Fill Missing `Embarked`      | Use mode value                               |
| Encode `Sex` and `Embarked`  | Using `LabelEncoder`                         |

---

## 📊 Modeling

### 🔵 Linear Regression (for demonstration)
- Model is trained to predict survival as a continuous value (not ideal but helps to demonstrate MSE and R²).
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - R² Score

### 🟢 Decision Tree Classifier
- Model predicts survival as a binary classification task.
- **Evaluation Metric**:
  - Accuracy Score

---

## 📈 Visualizations

1. **Survival Rate by Gender**
   - Visual comparison of survival probability for males vs females.
2. **Age Distribution**
   - Histogram showing how passenger ages are distributed.
3. **Survival Rate by Passenger Class**
   - Bar chart showing how class impacted survival chances.

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn` (`LinearRegression`, `DecisionTreeClassifier`, `LabelEncoder`, etc.)

---

## ▶️ How to Run

1. Upload the `titanic.csv` file.
2. Open the notebook in Google Colab or Jupyter.
3. Run the cells sequentially.
4. Check the model outputs and plots.

---

## ✅ Results Snapshot

| Model                 | Metric            | Value         |
|----------------------|-------------------|---------------|
| Linear Regression     | MSE               | *e.g. 0.15*   |
|                      | R² Score           | *e.g. 0.32*   |
| Decision Tree Classifier | Accuracy Score | *e.g. 0.81*   |

(*Replace with actual values from your run*)

---

## 📝 Next Steps

- Try other models like Random Forest, Logistic Regression, or SVM
- Perform hyperparameter tuning (e.g., `max_depth`, `min_samples_split`)
- Add cross-validation and confusion matrix
- Use advanced feature engineering like `FamilySize`, `IsAlone`, or title grouping

---

## 🤝 Contributing

Feel free to fork, modify, and suggest improvements!

---

## 📃 License

This project is open-source under the [MIT License](LICENSE).
