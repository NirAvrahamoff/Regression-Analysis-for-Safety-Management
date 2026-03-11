# Regression Models Analysis

This project explores several statistical regression models and demonstrates how different models can describe data in different ways.

The project includes two notebooks and analyzes three main types of regression:

- Linear & Polynomial Regression
- Logistic Regression
- Poisson / Negative Binomial Regression

The goal is to understand when each model should be used and how the results differ depending on the statistical assumptions.

---

# Project Structure


The notebooks include data exploration, model fitting and visualization.

---

# Linear & Polynomial Regression

The first part of the project analyzes how environmental variables influence machine performance.

The models tested:

- Linear Regression
- Polynomial Regression
- Linear Regression with interaction terms

### Data Visualization

![Linear Scatter](images/linear_scatter.png)

This visualization shows the relationship between environmental variables and machine performance.

---

### Linear Model Prediction

![Predicted vs Actual](images/predicted_vs_actual.png)

This plot compares the predicted values from the linear regression model with the true values.

---

### Polynomial Regression

![Polynomial Regression](images/polynomial_fit.png)

Polynomial regression allows capturing nonlinear relationships between variables.

---

# Logistic Regression

Logistic regression is used when the response variable represents **probability or classification**.

In this analysis the model estimates the probability of an event occurring based on several predictors.

![Logistic Probability](images/logistic_probability.png)

The logistic curve maps values into probabilities between 0 and 1.

---

# Poisson and Negative Binomial Regression

Poisson regression is used for **count data**, such as number of events occurring during a period of time.

Examples include:

- number of failures
- number of accidents
- number of events per time unit

![Poisson Distribution](images/poisson_distribution.png)

Negative Binomial regression extends the Poisson model when the data shows **over-dispersion**.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Key Insight

Different regression models describe data in different ways.

- Linear regression assumes a straight relationship
- Polynomial regression captures nonlinear patterns
- Logistic regression models probabilities
- Poisson regression models event counts

Choosing the correct model depends on the structure of the data and the research question.


