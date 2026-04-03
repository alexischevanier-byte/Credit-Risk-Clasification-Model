📊 Credit Risk Classification Model

🎯 Objective

The goal of this project is to build a machine learning model that classifies whether a customer represents a high credit risk, based on financial and behavioral characteristics.

---

🧠 Business Context

In financial institutions, accurately assessing credit risk is critical to minimize losses and make informed lending decisions.

This project simulates a real-world scenario where customer data is used to predict the likelihood of default, enabling better risk management and decision-making.

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Logistic Regression)

---

📊 Methodology

1. Data Generation

A synthetic dataset was created to simulate real customer profiles, including:

- Age
- Income
- Loan amount
- Credit score
- Employment history

---

2. Feature Engineering

A key financial metric was created:

- Debt-to-Income Ratio (DTI)
  → Measures the proportion of income used to cover debt

This variable is widely used in real credit risk analysis.

---

3. Target Variable Creation

A classification label ("risk") was generated based on realistic business rules:

- Low credit score
- High debt-to-income ratio
- Short employment history

Customers meeting these conditions are labeled as high risk.

---

4. Model Training

A Logistic Regression model was trained to:

- Learn relationships between variables
- Estimate probability of default
- Classify customers into risk categories

---

5. Model Evaluation

The model was evaluated using:

- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC Score

These metrics help assess how well the model distinguishes between high-risk and low-risk customers.

---

📈 Key Visualizations

ROC Curve
<img width="570" height="460" alt="image" src="https://github.com/user-attachments/assets/e9bd5546-2a64-48e5-9d3c-a2350a6189f5" />


---

🔍 Key Insights

- Customers with low credit scores are significantly more likely to be classified as high risk

- A high debt-to-income ratio is a strong indicator of financial stress and default risk

- Customers with short employment history show higher probability of risk

- The model demonstrates a strong ability to differentiate between high-risk and low-risk customers, as reflected by the ROC-AUC score

- Predicting probability of risk (not just classification) enables more flexible and realistic decision-making

---

🚀 Conclusion

This project demonstrates how machine learning can be applied to credit risk assessment by combining financial indicators and predictive modeling.

The model provides a practical approach to identifying high-risk customers and supports more informed lending strategies.

---

👤 Author

Alexis Lopez
