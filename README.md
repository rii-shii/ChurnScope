# ChurnScope — Customer Churn & Retention Analysis

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Project Overview

**ChurnScope** is a data analytics project that explores customer churn patterns and identifies factors associated with customer cancellations.

Using Python and data visualization, this project analyzes customer demographics, contract types, tenure, monthly charges, internet services, payment methods, and support services to uncover useful business insights.

## 🎯 Project Objectives

- Analyze the overall customer churn rate.
- Identify customer segments with higher churn rates.
- Explore relationships between customer tenure and churn.
- Compare churn across contract types and payment methods.
- Visualize findings and develop data-driven business recommendations.

## 📊 Dataset Overview

- **Total customers:** 7,043
- **Total features:** 21
- **Churned customers:** 1,869
- **Retained customers:** 5,174
- **Overall churn rate:** 26.54%

The project uses a Telco Customer Churn dataset containing customer information, service subscriptions, billing details, and churn status.

## 🛠️ Tools & Technologies

- **Python** — data analysis
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations
- **Jupyter Notebook** — exploratory analysis
- **Visual Studio Code** — development environment

## 🔍 Key Findings

### 1. Contract Type

Month-to-month customers had a churn rate of **42.71%**, compared with 11.27% for one-year contracts and 2.83% for two-year contracts.

### 2. Customer Tenure

Customers who churned had a median tenure of approximately **10 months**, compared with approximately 38 months for customers who stayed.

### 3. Monthly Charges

Customers who churned had average monthly charges of approximately **74.44**, compared with 61.27 for retained customers.

### 4. Internet Service

Fiber-optic customers had a churn rate of **41.89%**, higher than the 18.96% observed among DSL customers.

### 5. Payment Method

Electronic-check customers had the highest observed churn rate at **45.29%**.

### 6. Support Services

Customers without online security or technical support had substantially higher observed churn rates than customers with these services.

## 📈 Visualizations

The analysis includes:

- Overall churn distribution
- Churn rate by contract type
- Churn rate by internet service
- Churn rate by payment method
- Customer tenure comparison by churn status
- Customer segmentation by demographic and service characteristics

## 💡 Business Recommendations

- Investigate retention opportunities for month-to-month customers.
- Focus on improving the early customer experience.
- Review pricing and perceived value among customers with higher monthly charges.
- Investigate service satisfaction among fiber-optic customers.
- Explore billing experiences among electronic-check users.
- Evaluate how support and security services relate to customer retention.

These recommendations are based on observed associations and should be validated before implementation.

## 📁 Project Structure

```text
churnscope/
├── data/
│   └── raw/
│       └── Telco-Customer-Churn.csv
├── notebooks/
│   └── 01_exploration.ipynb
├── PROJECT_FINDINGS.md
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install Python.
3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `notebooks/01_exploration.ipynb` in Jupyter Notebook or VS Code.
5. Select the appropriate Python environment and run the notebook cells.

Place the dataset at `data/raw/Telco-Customer-Churn.csv` before running the notebook.

## 📌 Conclusion

ChurnScope demonstrates how exploratory data analysis can uncover patterns associated with customer churn and support business decision-making.

The project provides a foundation for future work involving interactive dashboards, customer segmentation, and machine-learning-based churn prediction.

## 👤 Author

Created as a data analytics portfolio project.