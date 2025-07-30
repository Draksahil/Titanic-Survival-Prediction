# 🚢 Titanic Survival Prediction

## 📁 Project Structure

* `Titanic_project.ipynb`: Jupyter Notebook containing the full code for data analysis, preprocessing, model training, and evaluation.
* `README.md`: Project overview and documentation.

---

## 🧠 Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle missing values and perform feature engineering
* Encode categorical variables
* Apply classification algorithms: Logistic Regression, Decision Tree, Random Forest, etc.
* Compare model performance
* Make predictions on test data

---

## 📊 Tools and Libraries

* Python
* Pandas, NumPy (Data manipulation)
* Matplotlib, Seaborn (Visualization)
* Scikit-learn (Modeling and evaluation)

---

## 🔍 Exploratory Data Analysis (EDA)

Performed visual and statistical analysis to understand:

* Survival distribution across genders, classes, and age groups
* Correlation between features
* Missing data patterns

---

## 🛠️ Feature Engineering

* Filled missing values using appropriate strategies (mean, mode, etc.)
* Created new features like `FamilySize`
* Applied one-hot encoding to categorical variables (`Sex`, `Embarked`, `Pclass`)

---

## 🤖 Models Used

* **Logistic Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**

Model performance was evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

---

## 📈 Results

* The Random Forest model showed the highest accuracy.
* Feature importance showed `Sex`, `Pclass`, and `Fare` were among the most influential features.

---

## ✅ Conclusion

This project demonstrates the end-to-end process of solving a classification problem using machine learning:

1. Data cleaning
2. Visualization
3. Modeling
4. Evaluation
5. Prediction

---

## 📌 Future Improvements

* Hyperparameter tuning (GridSearchCV or RandomizedSearchCV)
* Ensemble techniques (e.g., XGBoost)
* Cross-validation for better generalization

---
