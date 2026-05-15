# Customer Churn Prediction System

## Project Overview

This project is a Machine Learning-based Customer Churn Prediction System developed using Python and Streamlit. The application predicts whether a customer is likely to churn based on customer-related features and displays model performance through interactive visualizations and classification reports.

---

# Objectives

* Predict customer churn using machine learning algorithms.
* Compare different classification models.
* Visualize customer churn distribution and model performance.
* Provide an easy-to-use interactive dashboard using Streamlit.

---

# Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

# Machine Learning Models Used

1. Logistic Regression
2. KNN Normalize
3. Random Forest

---

# Model Accuracy

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 79.03%   |
| KNN Normalize       | 75.91%   |
| Random Forest       | 78.89%   |

---

# Classification Report Summary

The classification report was used to evaluate the performance of the churn prediction model.

## Important Metrics

### Accuracy

* Measures the overall correctness of the model predictions.
* The Logistic Regression model achieved an overall accuracy of 79.03%.

### Precision

* Measures how reliable the churn predictions are.
* Higher precision indicates fewer incorrect churn predictions.

### Recall

* Measures how effectively the model identifies actual churn customers.
* Important for customer retention analysis.

### F1-Score

* Provides a balance between Precision and Recall.
* Helps evaluate overall model effectiveness.

### Support

* Shows the total number of records in each class.

---

# Key Findings

* The model performed well in predicting non-churn customers.
* Churn prediction performance was comparatively lower.
* Random Forest achieved strong overall prediction performance.
* Recall for churn customers can be improved for better business decision-making.

---

# Features of the Application

* Interactive Streamlit dashboard
* Model accuracy visualization
* Customer churn distribution chart
* Classification report display
* Multiple machine learning model comparison

---

# How to Run the Project

## Install Required Libraries

```bash
pip install streamlit pandas numpy matplotlib scikit-learn
```

## Run the Streamlit Application

```bash
streamlit run churn_app.py
```

---

# Future Improvements

* Improve churn customer prediction recall.
* Add more machine learning algorithms.
* Deploy the application online.
* Add advanced data visualizations.

---

# Conclusion

This project demonstrates how machine learning can be used to predict customer churn and support business decision-making. The system helps identify customers who are likely to leave, enabling companies to take preventive actions and improve customer retention.

