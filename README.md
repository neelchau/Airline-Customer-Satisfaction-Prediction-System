# ✈️ Airline Customer Satisfaction Prediction

## 📝 **Overview**

This project focuses on building a **Machine Learning model** to predict **airline passenger satisfaction levels** based on service quality, flight experience, and demographic factors.
The goal is to help airlines analyze customer feedback data and identify factors that most influence satisfaction.

The project involves **data preprocessing, feature engineering, model training**, and **performance comparison** across multiple algorithms to identify the most accurate one.

---

## 🎯 **Objectives**

* Predict passenger satisfaction using machine learning models.
* Identify key features impacting satisfaction (service, delays, comfort, etc.).
* Compare model performances and select the best-performing algorithm.
* Provide insights to improve customer experience and retention.

---

## 🧠 **Technologies Used**

| Category                 | Tools / Libraries   |
| ------------------------ | ------------------- |
| **Programming Language** | Python              |
| **Data Processing**      | pandas, numpy       |
| **Visualization**        | matplotlib, seaborn |
| **Machine Learning**     | scikit-learn        |
| **Notebook Environment** | Jupyter Notebook    |

---

## ⚙️ **Methodology**

1. **Data Collection:** Dataset includes passenger attributes and satisfaction ratings.
2. **Data Cleaning & Preprocessing:** Handled missing values, encoded categorical features, and normalized numerical data.
3. **Feature Engineering:** Extracted relevant features that influence satisfaction.
4. **Model Training:** Applied multiple ML algorithms for classification.
5. **Evaluation:** Compared model performance using accuracy metrics.
6. **Result Interpretation:** Selected the model with the best accuracy for deployment.

---

## 📊 **Model Performance**

| Model                           | Accuracy (%) |
| ------------------------------- | ------------ |
| Logistic Regression             | 88.77        |
| K-Nearest Neighbors             | **90.83**    |
| Support Vector Machine (Linear) | 88.32        |
| Gaussian Naive Bayes            | 86.12        |
| Random Forest Classifier        | **94.43**    |
| Gradient Boosting Classifier    | 93.98        |
| Decision Tree Classifier        | 92.28        |

✅ **Best Model:** Random Forest Classifier (94.43% Accuracy)

---

## 🔍 **Insights**

* Random Forest performed the best, showing its robustness for mixed-type datasets.
* Flight delays, seat comfort, and onboard service were key satisfaction factors.
* Simpler models like Logistic Regression still provided strong baseline results.


---

## 🏁 **Conclusion**

The Airline Passenger Satisfaction Prediction project effectively demonstrates the use of supervised learning techniques to understand and predict customer satisfaction. The insights derived can help airlines make data-driven decisions to improve overall passenger experience and service quality.
