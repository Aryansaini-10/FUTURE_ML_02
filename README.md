# FUTURE_ML_02
# 🎯 Support Ticket Classification System (Task 2)

## 📌 Project Overview

This project focuses on building a **Machine Learning system** that automatically classifies customer support tickets and assigns priority levels using **Natural Language Processing (NLP)** techniques.

The goal is to help support teams respond faster and more efficiently by automating ticket handling.

---

## 🚀 Objectives

* Classify support tickets into categories (e.g., Billing, Technical, Account)
* Predict ticket priority (High, Medium, Low)
* Perform text preprocessing and feature extraction
* Evaluate model performance using standard metrics

---

## 🧠 Tech Stack

* **Python**
* **Pandas & NumPy**
* **NLTK (Natural Language Processing)**
* **Scikit-learn**
* **Matplotlib & Seaborn**
* **Jupyter Notebook / Google Colab**

---

## 📂 Dataset

* Dataset used: **Customer Support Tickets Dataset**
* Key columns:

  * `Ticket Description` (Input text)
  * `Ticket Type` (Category label)
  * `Ticket Priority` (Priority label)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed null values
* Cleaned text (lowercase, removed special characters)
* Removed stopwords using NLTK

### 2️⃣ Feature Engineering

* Converted text into numerical form using **TF-IDF Vectorization**

### 3️⃣ Model Training

* **Logistic Regression** used for:

  * Ticket Type Classification
  * Ticket Priority Prediction

### 4️⃣ Model Evaluation

* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix Visualization

### 5️⃣ Prediction System

* Built a function that takes user input and predicts:

  * Ticket Category
  * Ticket Priority

---

## 📊 Results

* Successfully classified support tickets with good accuracy
* Model performs well on real-world-like customer queries
* Visualization provided for better understanding of data distribution

---

## 🧪 Example Prediction

**Input:**

```
"My payment failed but money got deducted"
```

**Output:**

```
Category: Billing
Priority: High
```

---

## 📁 Project Structure

```
FUTURE_ML_02/
│
├── notebook/
│   └── task2.ipynb
│
├── data/
│   └── customer_support_tickets.csv
│
├── model/
│   ├── model_type.pkl
│   ├── model_priority.pkl
│   └── vectorizer.pkl
│
└── README.md
```
![image alt](https://github.com/Aryansaini-10/FUTURE_ML_02/blob/313006e21cc9070169064995f89a3fc88435fc46/Screenshot%202026-03-30%20132551.png)
![image alt](https://github.com/Aryansaini-10/FUTURE_ML_02/blob/88f68a814093aeff57c26a6dbbe2439fcd431c8e/Screenshot%202026-03-30%20132607.png)
---

## 💡 Key Learnings

* Practical implementation of NLP techniques
* Text preprocessing and feature extraction
* Building and evaluating classification models
* Real-world problem-solving using ML

---

## 🔥 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Implement Deep Learning (LSTM / BERT)
* Build a web app using Streamlit
* Improve accuracy with hyperparameter tuning

---

## 📌 Conclusion

This project demonstrates how Machine Learning can automate support systems, reduce response time, and improve customer satisfaction.

---

## 👨‍💻 Author

**Aryan Saini**

---

## 🔗 Connect With Me

(https://www.linkedin.com/in/aryan-saini-a62b8a341/)
