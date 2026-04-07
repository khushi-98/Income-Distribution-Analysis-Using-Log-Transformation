# Income Distribution Analysis Using Log Transformation

## 📖 Overview

This project demonstrates how log transformation can be used to analyze skewed data, specifically income distribution. Real-world income data is often highly skewed, and applying a logarithmic transformation helps normalize the data and reveal clearer patterns.

---

## 🎯 Objectives

* Generate synthetic income data using a log-normal distribution
* Apply log transformation to reduce skewness
* Compare original vs transformed distributions
* Analyze relationships between income, age, and experience
* Understand the benefits of log transformation in data analysis

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📊 Dataset Description

The dataset is synthetically generated and includes:

* **Income**: Log-normally distributed values
* **Log_Income**: Log-transformed income
* **Age**: Random values between 18 and 65
* **Experience**: Derived from age with slight randomness

---

## ⚙️ Methodology

### 1. Data Generation

* Income data is generated using a log-normal distribution to simulate real-world skewness.

### 2. Log Transformation

* A natural logarithm is applied to income:

  ```
  Log_Income = log(Income)
  ```

### 3. Visualization

* Histograms with KDE plots are used to compare:

  * Original income distribution
  * Log-transformed income distribution

### 4. Correlation Analysis

* Correlation of income and log-income is calculated with:

  * Age
  * Experience

---

## 📈 Results & Insights

### 🔹 Distribution

* Original income is **right-skewed**
* Log-transformed income is **more normally distributed**

### 🔹 Correlation

* Log transformation may improve linear relationships
* Correlation values become more stable and interpretable

---

## ✅ Key Takeaways

Log transformation is useful because it:

* ✔ Reduces skewness in data
* ✔ Improves model performance
* ✔ Makes relationships more linear
* ✔ Helps meet statistical assumptions

---

## 🚀 How to Run

1. Install required libraries:

   ```
   pip install numpy pandas matplotlib seaborn
   ```
2. Run the Python script:

   ```
   python script.py
   ```

---

## 📌 Conclusion

Log transformation is a powerful preprocessing step when working with skewed data like income. It enhances visualization, improves statistical analysis, and leads to better modeling outcomes.

---

## 📬 Future Work

* Apply transformation to real-world datasets
* Test impact on regression models
* Explore other transformations (Box-Cox, sqrt)

---
