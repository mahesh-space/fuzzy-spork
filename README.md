
# 🌸 Iris Flower Classification using Machine Learning

This project uses a machine learning model to classify iris flower species based on sepal and petal dimensions. It is developed as part of an AICTE Capstone Project and implemented in Google Colab using Python and Scikit-learn.

## 📌 Project Overview

The Iris dataset is a classic multi-class classification problem where the objective is to predict the species of a flower based on the following features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

Predicted Classes:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🧪 Technologies Used

- Python 3
- Google Colab
- Scikit-learn (RandomForestClassifier)
- Pandas & NumPy
- Seaborn & Matplotlib (for visualization)

## 🛠️ How It Works

1. Load the built-in Iris dataset from scikit-learn.
2. Visualize the data using pairplots and boxplots.
3. Split the data into training and testing sets.
4. Train a Random Forest Classifier.
5. Evaluate performance using accuracy, classification report, and confusion matrix.
6. Predict flower species for a new set of input features.

## 📈 Model Performance

- ✅ Accuracy: ~97%
- ✅ High precision & recall for all 3 classes
- ✅ Visualized Confusion Matrix and feature importance

## 🔍 Sample Prediction

Example input:

```python
[5.1, 3.5, 1.4, 0.2]  # sepal length, sepal width, petal length, petal width
````

Predicted output:

```python
'Iris-setosa'
```

## 📸 Screenshots

| Pairplot                              | Confusion Matrix                                  | Sample Prediction                             |
| ------------------------------------- | ------------------------------------------------- | --------------------------------------------- |
| ![Screenshot_15-6-2025_18227_colab research google com](https://github.com/user-attachments/assets/674e9ff1-cc91-4e9e-9a4d-8862e6c6823e)| ![Screenshot_15-6-2025_182454_colab research google com](https://github.com/user-attachments/assets/b6613ca4-bb18-4203-a538-582dee80f771)| ![Screenshot_15-6-2025_182517_colab research google com](https://github.com/user-attachments/assets/ca9f30fa-8423-4278-ba7a-29c82f07582a)|

## 📁 Files

* iris\_classification.ipynb → Colab notebook
* README.md → This file
* requirements.txt → List of dependencies (optional)
* screenshots/ → Folder for images used in README

## 📚 References

* [https://scikit-learn.org/stable/auto\_examples/datasets/plot\_iris\_dataset.html](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
* [https://archive.ics.uci.edu/ml/datasets/iris](https://archive.ics.uci.edu/ml/datasets/iris)
* [https://matplotlib.org/](https://matplotlib.org/)
* [https://seaborn.pydata.org/](https://seaborn.pydata.org/)

---

 Developed by: \[MG]


