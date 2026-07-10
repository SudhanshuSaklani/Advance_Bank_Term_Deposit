# Advance Bank Term Deposit Analysis & Prediction

This repository contains a comprehensive data analysis and machine learning project focused on understanding customer behavior regarding bank term deposit subscriptions. Using a dataset of banking interactions, the project identifies the demographic, financial, and behavioral factors that influence whether a customer subscribes to a term deposit.

---

## Project Overview

The primary objective of this project is to:

- Analyze the factors influencing a customer's decision to subscribe to a term deposit.
- Perform exploratory data analysis (EDA) to uncover meaningful insights.
- Build a reliable binary classification model to predict customer subscription outcomes.

---

## Key Features & Analysis

### Customer Demographics Analysis

- Explores how customer demographics such as **age** and **job category** influence subscription rates.

### Balance & Deposit Trends

- Examines the relationship between a customer's **account balance** and their likelihood of subscribing to a term deposit.

### Contact Duration Insights

- Analyzes the **last contact duration**, showing that longer customer interactions are generally associated with higher subscription rates.

### Campaign Effectiveness

- Evaluates:
  - Contact methods (**Cellular vs Telephone**)
  - Number of campaign contacts
  - Overall marketing campaign effectiveness

### Correlation Heatmap

- Visualizes relationships among numerical features to identify important correlations within the dataset.

---

## Technical Implementation

### Data Preprocessing

To ensure data integrity and prevent **data leakage**, a preprocessing pipeline was built using **ColumnTransformer**.

#### Numerical Features

- StandardScaler

#### Categorical Features

- OneHotEncoder

---

## Predictive Modeling

A **Logistic Regression** classifier was trained for binary classification.

### Why Logistic Regression?

- Provides high model interpretability.
- Enables coefficient analysis.
- Makes feature importance easy to understand.
- Performs efficiently on structured tabular datasets.

---

## Key Takeaways

- **Communication Matters**
  - Customers contacted via **cellular** were significantly more likely to subscribe than those contacted via telephone.

- **Customer Engagement**
  - Longer conversations and more campaign interactions positively influenced subscription rates.

- **Financial Profile**
  - Customers with higher account balances and specific occupations showed a greater likelihood of subscribing to term deposits.

---

## Tech Stack

### Programming Language

- Python 3 (Jupyter Notebook / IPykernel)

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  - Logistic Regression
  - ColumnTransformer
  - StandardScaler
  - OneHotEncoder

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/bank-term-deposit-analysis.git
```

### 2. Navigate to the Project

```bash
cd bank-term-deposit-analysis
```

### 3. Open the Notebook

Launch the notebook:

```text
Advance_Bank_Term_Deposit.ipynb
```

using Jupyter Notebook or JupyterLab.

### 4. Run the Notebook

Execute the notebook cells sequentially to:

- Load the dataset
- Perform data preprocessing
- Conduct exploratory data analysis (EDA)
- Train the Logistic Regression model
- Evaluate model performance
- Visualize insights

---

## Project Structure

```text
├── Advance_Bank_Term_Deposit.ipynb
├── README.md
└── dataset/
```

---

## Project Highlights

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Correlation Analysis
- Logistic Regression Classification
- Feature Importance Analysis
- Data Visualization
- Marketing Campaign Insights

---

## License

This project is intended for educational and learning purposes.

---

## If you found this project helpful, consider giving it a star!
