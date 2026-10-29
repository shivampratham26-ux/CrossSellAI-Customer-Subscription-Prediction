# CrossSellAI — Customer Subscription Prediction

A machine learning project that predicts the likelihood of a customer subscribing to a service using customer-related features and a Gradient Boosting Classifier.

**[🌐 Live Website](https://shivampratham26-ux.github.io/CrossSellAI-Customer-Subscription-Prediction/)** · **[💻 GitHub Repository](https://github.com/shivampratham26-ux/CrossSellAI-Customer-Subscription-Prediction)**

---

## 📌 Project Overview

CrossSellAI explores how machine learning can support customer subscription prediction. The project includes data preparation, exploratory data analysis (EDA), model training, evaluation, and a web-based demonstration interface.

## 🎯 Objectives

* Explore customer data through EDA.
* Prepare data for machine learning.
* Train a Gradient Boosting classification model.
* Evaluate model performance using classification metrics.
* Demonstrate customer subscription predictions through a web interface.

## 🛠️ Tech Stack

* **Language:** Python
* **Data Analysis:** Pandas
* **Machine Learning:** Scikit-learn
* **Development Environment:** Google Colab
* **Web Demonstration:** HTML/CSS/JavaScript
* **Version Control & Hosting:** GitHub and GitHub Pages

## 📊 Model Performance

| Metric              | Result |
| ------------------- | -----: |
| Validation Accuracy | 90.85% |
| ROC-AUC             | 93.49% |
| Training Records    | 25,317 |
| Validation Records  |  6,330 |
| Processed Features  |     51 |

**Model:** Gradient Boosting Classifier

These figures describe the project's reported validation results. Performance on new data may differ.

## ✨ Key Features

* Customer subscription prediction workflow
* Data exploration and preprocessing
* Classification model evaluation
* Probability-based prediction demonstrations
* Browser-accessible project showcase

## 🌐 Live Demo

Visit the project website:

**https://shivampratham26-ux.github.io/CrossSellAI-Customer-Subscription-Prediction/**

The GitHub Pages site is a static showcase. It does not, by itself, host or execute the Python machine learning model.

## 📁 Repository Structure

```text
CrossSellAI-Customer-Subscription-Prediction/
├── assets/
│   ├── app-case3.png
│   ├── case1.png
│   ├── case2.png
│   ├── case3.png
│   └── case4.png
├── index.html
└── README.md
```
## 📊 Model Performance

The **CrossSellAI Customer Subscription Prediction System** uses a **Gradient Boosting Classifier** to predict whether a customer is likely to subscribe to a banking product.

### 🎯 Performance Metrics

| Metric                         | Result                       |
| ------------------------------ | ---------------------------- |
| **Machine Learning Algorithm** | Gradient Boosting Classifier |
| **Validation Accuracy**        | 90.85%                       |
| **ROC-AUC Score**              | 93.49%                       |
| **Training Records**           | 25,317                       |
| **Validation Records**         | 6,330                        |
| **Processed Features**         | 51                           |

### 📈 Classification Report

| Class               | Precision | Recall | F1-Score | Support |
| ------------------- | --------- | ------ | -------- | ------- |
| No Subscription (0) | 0.93      | 0.97   | 0.95     | 5,587   |
| Subscription (1)    | 0.68      | 0.41   | 0.51     | 743     |

### 🔍 Key Observations

* The model achieved **90.85% validation accuracy**, demonstrating strong overall classification performance.
* The **93.49% ROC-AUC score** indicates good discrimination between potential subscribers and non-subscribers.
* The model performs particularly well in identifying customers unlikely to subscribe.
* The recall for actual subscribers is **41%**, indicating an opportunity to improve positive-class detection.
* Future improvements may include hyperparameter tuning, class balancing, and threshold optimization.

## 🚀 Future Improvements

* Deploy the interactive Python model through a suitable application hosting service.
* Improve detection of customers who are likely to subscribe.
* Add further model comparisons and evaluation visualizations.
* Expand the documentation with reproducible training instructions.

### ✅ Conclusion

The Gradient Boosting Classifier provides a strong baseline for customer subscription prediction. While overall accuracy and ROC-AUC are high, improving recall for potential subscribers remains an important area for future development.


## 👨‍💻 Author

**Shivam Pratham**
B.Tech — Artificial Intelligence & Data Science
Amity University Jharkhand

---

*Developed as a machine learning project exploring customer subscription prediction.*
