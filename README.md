Here’s a clean, professional **README.md** you can directly add to your GitHub repository. It’s written in a student-friendly but project-ready style.

---

# 🚗 Car Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on predicting car prices using a **Linear Regression** model. The goal is to understand how different **categorical encoding techniques** impact model performance and to identify which encoding method works better for this dataset.

The project follows a complete **machine learning workflow**, starting from data exploration to model evaluation.

---

## 📊 Dataset

* **Source:** Kaggle
* **Link:** [https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction](https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction)
* **Description:**
  The dataset contains information about Ford cars, including features such as model, year, transmission, fuel type, mileage, engine size, and price.

---

## 🔍 Exploratory Data Analysis (EDA)

Before building the model, an in-depth **Exploratory Data Analysis (EDA)** was performed to:

* Understand the structure of the dataset
* Analyze data types (numerical & categorical)
* Study feature distributions and relationships
* Detect patterns, trends, and potential anomalies

EDA helped in understanding the **behavior of the data** and guided preprocessing decisions.

---

## 🛠️ Data Preprocessing

Since the dataset contains categorical variables, two different encoding techniques were applied **separately** to compare their impact on model performance:

### 1️⃣ Label Encoding

* Converts categorical values into numerical labels
* Simple and fast
* **Result:** Did not perform well for this dataset, as it introduced an artificial order among categories

### 2️⃣ One-Hot Encoding

* Creates binary columns for each category
* Prevents ordinal relationships between categories
* **Result:** Produced better model performance compared to label encoding

---

## 🤖 Model Training

* Algorithm used: **Linear Regression**
* Dataset split into:

  * **Training set**
  * **Testing set**
* The model was trained separately using:

  * Label Encoded data
  * One-Hot Encoded data

---

## 📈 Model Evaluation

After training, the model was evaluated using appropriate regression metrics.

### 🔎 Key Observations:

* The model trained with **Label Encoding** showed poor performance
* The model trained with **One-Hot Encoding** achieved better accuracy and generalization
* Encoding technique significantly affects linear regression performance on categorical data

---

## ✅ Conclusion

* Proper encoding of categorical variables is crucial
* **One-Hot Encoding outperformed Label Encoding** for car price prediction
* Linear Regression can work effectively when preprocessing is done correctly

---

## 🧠 Learning Outcomes

* Hands-on experience with EDA
* Understanding the impact of encoding techniques
* Building and evaluating regression models
* End-to-end ML pipeline implementation

---


---


