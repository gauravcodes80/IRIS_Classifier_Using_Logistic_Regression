# IRIS_Logistic_Regression

# 🌸 Iris Virginica Classifier using Logistic Regression<br>

This project demonstrates a simple **binary classification** using **logistic regression** to determine whether a given iris flower is of the *Virginica* species based on its **petal width**.<br>

## 📊 Dataset<br>

We use the popular **Iris dataset** from `scikit-learn`. It contains 150 samples of iris flowers with 4 features each:<br>
- Sepal Length<br>
- Sepal Width<br>
- Petal Length<br>
- Petal Width<br>

For this project, we use **only Petal Width** as the feature.<br>

## 🎯 Objective<br>

Train a logistic regression model to classify whether a flower is **Virginica** (class label `2`) or not (`0` or `1`).<br>

## 🧠 Model<br>

We use **`LogisticRegression`** from `sklearn.linear_model` for binary classification:<br>
python
Y = (iris["target"] == 2)  # 1 if Virginica, else 0<br>
🖼️ Output Example<br>
Predicts whether a flower with 1.6 cm petal width is Virginica<br>

Displays a probability curve using matplotlib<br>



📈 Visualization
The project plots the probability curve showing how the likelihood of a flower being Virginica changes with petal width.

![Logistic_regression](https://github.com/user-attachments/assets/043323f8-07d4-470a-9188-943693857466)

