# 📦 Flipkart Customer Support Ticket Classification

This project builds a machine learning model to classify Flipkart customer support tickets into predefined categories such as **Returns**, **Product Queries**, **Order Related**, and **Cancellations**. The model helps automate support ticket routing and improves operational efficiency.

---

## 🚀 Objective

To automate the classification of customer queries using machine learning, reducing manual triage time and improving service delivery.

---

## 🛠️ What We Did

- Cleaned and preprocessed the customer support dataset
- Engineered features: combined text + calculated response time
- Applied NLP cleaning and TF-IDF vectorization
- Trained two ML models: Logistic Regression and Random Forest
- Random Forest achieved ~84% accuracy
- Created an animated bubble chart to visualize live support category volumes

---

## 📁 Files Included

- `Flipkart_submission_project.ipynb`: Final notebook
- `Customer_support_data.csv`: Dataset (if public)
- `flipkart_bubble_animation.mp4`: Visualization (if included)
- `README.md`: Project overview

---

## 📊 Future Improvements

- Use transformer-based models like BERT for better text understanding
- Predict urgency and CSAT in addition to category
- Deploy as an API in a live support dashboard
