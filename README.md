# Regression Models Analysis

This project explores several statistical regression models and compares how different models describe the same data.

The project includes two notebooks and investigates multiple regression approaches:

• Linear Regression  
• Polynomial Regression  
• Logistic Regression  
• Poisson Regression  
• Negative Binomial concepts

The goal is to understand how model assumptions influence predictions and model performance.

---

# Project Structure

Linear&polynomial.ipynb
Logistic&Poisson&Binomial.ipynb


The notebooks contain the full modeling process including data exploration, model fitting and evaluation.

---

# Model Comparison

The following table compares the performance of the main regression models.

![Model Comparison](images/compare_models.png)

Polynomial regression achieved the best performance based on:

• Highest R²  
• Lowest AIC and BIC  
• Lowest test MSE

---

# Model Selection Using AIC and BIC

To determine the optimal polynomial degree we compared model complexity using information criteria.

![AIC BIC](images/bic.png)

Degree **2** achieved the lowest AIC and BIC values, indicating the best balance between model fit and complexity.

---

# Linear Regression

Linear regression assumes a straight-line relationship between predictors and the response variable.

![Linear Model](images/linear.png)

While the model captures the overall trend, it does not fully explain nonlinear patterns in the data.

---

# Interaction Model

Adding interaction terms allows the model to capture relationships between variables.

![Interaction Model](images/interaction.png)

This improves the model performance compared to the basic linear regression.

---

# Polynomial Regression

Polynomial regression allows modeling nonlinear relationships between variables.

![Polynomial Model](images/polynomial.png)

This model provided the best predictive performance.

---

# Logistic Regression

Logistic regression models probabilities and allows classification decisions based on a threshold.

![Sensitivity vs Specificity](images/0.6.png)

The model evaluates the trade-off between sensitivity and specificity across different thresholds.

---

# Poisson Regression

Poisson regression is used for modeling count data such as the number of events.

![3D Poisson Surface](images/3d.png)

The model predicts the expected number of events based on explanatory variables.

---

# Poisson Distribution Behavior

The following analysis shows the probability of observations falling within ±2 standard deviations.

![Probability ±2SD](images/2sd.png)

The distribution concentrates around the expected range as λ increases.

---

# Residual Analysis

Residual diagnostics help evaluate model fit.

![Residual Analysis](images/response.png)

Residuals outside the ±2 range indicate deviations from model assumptions.

---

# Mean vs Variance Analysis

For Poisson distributions the theoretical property is:


