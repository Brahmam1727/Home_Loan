
# Home_Loan
 1. [GithubAccount](https://github.com)
 2. [VSCodeIDE](https://code.visualstudio.com/)
 3. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)


#  Home Loan Default Prediction

An end-to-end Machine Learning project that predicts whether a customer is likely to default on a home loan. This solution helps financial institutions improve credit risk assessment and make data-driven lending decisions.

---

##  Project Objective

The goal of this project is to build a robust predictive model that identifies high-risk loan applicants using demographic, financial, and credit history data.

**Business Impact:**

* Reduce loan default risk
* Improve loan approval quality
* Enable proactive risk management
* Support data-driven credit decisions

---

##  Dataset

* Source: Home Credit Default Risk dataset
* Multiple relational tables containing customer credit information
* Target variable: `TARGET`

  * **1 → Defaulter**
  * **0 → Non-defaulter**

---

##  Project Workflow

### 1️ Data Understanding

* Explored structure of application and secondary tables
* Identified missing values and data types

### 2️ Data Cleaning

* Handled missing values
* Removed high-null columns
* Treated outliers in financial variables

### 3️ Feature Engineering

* Created financial risk ratios
* Engineered age and employment features
* Aggregated multi-table credit history

### 4️ Encoding & Scaling

* One-Hot Encoding for categorical variables
* StandardScaler for numerical features
* Built reusable preprocessing pipeline

### 5️ Model Building

Trained and compared multiple models:

* Logistic Regression
* Decision Tree
* Random Forest ⭐
* Gradient Boosting

### 6️ Model Evaluation

Evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC (primary metric)

**Best Model:** Random Forest / Gradient Boosting (based on ROC-AUC)

---



###  Prediction Pipeline

User Input → Preprocessing → Trained Model → Default Risk Output

---

##  Tech Stack

**Programming:**

* Python

**Libraries:**

* Pandas
* NumPy
* Scikit-learn
* Statsmodels
* Matplotlib
* Seaborn



##  Challenges Faced

* High missing values in credit data
* Multi-table data aggregation complexity
* Class imbalance in defaulters
* Feature scaling across heterogeneous variables

**Solutions:**

* Robust imputation strategy
* Customer-level aggregation
* ROC-AUC–based evaluation
* Standardized preprocessing pipeline

---

create new Enviroment

```
conda create Brahmam -p python==3.13.5 -y

```







