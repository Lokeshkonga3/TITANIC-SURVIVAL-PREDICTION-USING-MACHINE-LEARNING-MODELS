## 🎯 Objectives

The main objectives of this project are:

- To explore and clean the **Titanic dataset** for predictive modeling.
- To handle missing data:
  - Fill missing values in the `Age` column using the median.
  - Fill missing values in the `Embarked` column using the mode.
  - Drop unnecessary columns such as `PassengerId`, `Name`, `Ticket`, and `Cabin`.
- To convert categorical variables into numerical format using `LabelEncoder`:
  - Encode `Sex` and `Embarked`.
- To build and compare two predictive models:
  - **Linear Regression** (for demonstration of continuous prediction, using MSE and R²).
  - **Decision Tree Classifier** (for binary classification of survival).
- To evaluate model performance using:
  - Mean Squared Error (MSE)
  - R² Score
  - Accuracy Score
- To visualize key trends affecting survival:
  - Survival rate by gender
  - Age distribution of passengers
  - Survival rate by passenger class
- To create a clean and structured dataset suitable for training other ML algorithms.

