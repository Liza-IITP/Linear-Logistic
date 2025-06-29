
# MachineLearning

## 🧠 Feature Engineering and Exploratory Data Analysis (EDA)
- Missing Values Imputation  
- Handling Imbalanced Dataset  
- SMOTE  
- Handling Outliers  
- Encoding (Nominal, One-Hot, Label, Ordinal)

---

## 🔢 Simple and Multiple Linear Regression

| Model                         | Type              | Learning Technique        | Notes                                                                 |
|------------------------------|-------------------|---------------------------|-----------------------------------------------------------------------|
| Linear Regression (Custom)   | Simple Regression | Analytical (OLS)          | Fits line using closed-form solution; interpretable coefficients      |
| Multiple Linear Regression    | Multivariate       | Analytical (OLS)          | Supports multiple features; intercept & beta via matrix algebra       |
| Polynomial Linear Regression | Univariate/Multivariate | Analytical (OLS) | Transforms features into polynomial basis; then applies OLS          |
| Batch Gradient Descent       | Multivariate                | Iterative Optimization     | Uses all data per step; stable but slower on large datasets           |
| Stochastic Gradient Descent  | Multivariate                | Online Optimization        | Updates weights per sample; faster but noisy                         |
| Mini-batch Gradient Descent  | Multivariate                | Hybrid Optimization        | Compromise between BGD and SGD; faster convergence + smoother updates |

---

## 🧮 Logistic Regression

| Model                           | Activation | Learning Technique                | Notes                                                           |
|--------------------------------|------------|-----------------------------------|-----------------------------------------------------------------|
| Perceptron (Basic)             | Step       | Randomized update                 | Binary output (0 or 1), no probabilities                        |
| Perceptron (Sigmoid-based)     | Sigmoid    | Gradient-like updates             | Adds non-linearity, smooth decision making                      |
| Logistic Regression (Custom)   | Sigmoid    | MLE + Gradient Descent            | Trained using log loss; comparable to scikit-learn              |
| Multiclass Logistic Regression | Softmax    | Cross-Entropy + Gradient Descent  | Load_Digits dataset, NDVI Land Cover Classification task        |
