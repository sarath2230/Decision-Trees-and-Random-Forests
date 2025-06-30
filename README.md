# Task 5 – Tree-Based Models: Heart Disease Classification

In this task, we use **tree-based models** — Decision Trees and Random Forests — to classify whether a person has heart disease using the `heart.csv` dataset. These models are powerful for classification problems and are known for their interpretability and flexibility.

## 🎯 Objective

- Build and evaluate a **Decision Tree Classifier**
- Visualize the decision tree structure
- Control overfitting using `max_depth`
- Train a **Random Forest Classifier** and compare performance
- Analyze **feature importances**
- Evaluate with **cross-validation**

## 📊 Key Steps

- Loaded the `heart.csv` dataset
- Split data into training and testing sets
- Trained a **Decision Tree** and visualized it using `plot_tree`
- Evaluated model accuracy and generated a **classification report**
- Trained a **Random Forest** and compared accuracy
- Plotted **feature importances** to interpret model behavior
- Used **cross-validation** for more reliable evaluation
- Plotted accuracy of both models using a comparison bar graph

## 🧰 Tools & Libraries Used

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## ✅ Conclusion

Tree-based models performed well on the heart disease dataset. The **Random Forest** outperformed the single Decision Tree due to its ensemble strategy, and feature importance analysis gave insight into key medical indicators influencing predictions. This task demonstrated how tree-based classifiers can be both powerful and interpretable in real-world health prediction scenarios.

---



