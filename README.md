# Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project aims to classify iris flowers into one of three species—**Setosa, Versicolor, and Virginica**—based on their sepal and petal measurements. The classification is performed using the **K-Nearest Neighbors (KNN) algorithm**, a simple yet powerful machine learning model.

## 🎯 Objectives
- Implement a classification model using the **K-Nearest Neighbors (KNN)** algorithm.
- Use the **Iris dataset**, which contains measurements of iris flowers across three species.
- **Visualize** the dataset to understand the relationships between the features.
- **Evaluate the model's performance** using metrics such as accuracy, precision, recall, and confusion matrix.

## File Uploaded
- ML with IRIS data.ipynb
- Iris.csv

## Prerequisites:
- Google Colab
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

## 📂 Dataset Information
The dataset contains **150 samples** of iris flowers with the following features:
- **Sepal Length (cm)**
- **Sepal Width (cm)**
- **Petal Length (cm)**
- **Petal Width (cm)**
- **Species** (Target Variable)

## 📊 About the Model: K-Nearest Neighbors (KNN)
KNN is a **supervised machine learning algorithm** that classifies data points based on their similarity to their nearest neighbors.

### 🔹 How KNN Works:
1. Choose the number of neighbors (K).
2. Calculate the distance between the new data point and all points in the training dataset.
3. Select the K nearest neighbors.
4. Assign the most common class among the neighbors to the new data point.

### ✅ Why KNN for This Project?
- KNN is **easy to understand and implement**.
- It performs well on **small datasets like the Iris dataset**.
- It is a **non-parametric model**, meaning it makes no assumptions about data distribution.

### ⚠️ Limitations of KNN:
- **Computationally expensive** for large datasets.
- **Sensitive to irrelevant features** and noisy data.
- **Choosing the right K-value** is crucial for optimal performance.

## 🛠 Implementation Steps
1. **Load the dataset** (from Scikit-learn or a CSV file).
2. **Explore the data** using Pandas and Matplotlib.
3. **Preprocess the data** (handle missing values, if any).
4. **Split the dataset** into training (80%) and testing (20%) sets.
5. **Train the KNN model** with K=1.
6. **Make predictions** on new data.
7. **Evaluate the model** using accuracy, confusion matrix, and classification report.

## 🚀 Results & Evaluation
![Iris Flower Classification](https://github.com/kishor-17168/Iris-Flower-Classification/blob/main/Screenshot%202025-03-30%20205127.png?raw=true)
- **Model Accuracy:** 100.00%
- **Precision: The proportion of correct predictions for each species out of all predictions made for that species. Since it's 1.00, it means no false positives.**
- **Recall: The proportion of correctly predicted instances out of all actual instances. A recall of 1.00 means no false negatives.**
- **F1-Score: A balance between precision and recall. Since both are 1.00, the F1-score is also perfect.**
- **Support: The number of actual samples per class in the test set.**

## Future Improvements & Learnings 🚀
✔️ Test other classification models (e.g., Decision Trees, SVM)
✔️ Perform hyperparameter tuning for better performance
✔️ Deploy the model using Flask or Streamlit

## Author
**Kishor Marandy**

