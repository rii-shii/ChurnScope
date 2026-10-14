# ChurnScope — Customer Churn Analysis

## 1. Project Overview

ChurnScope is a customer churn analysis project that explores customer behavior and identifies patterns associated with customer cancellations. The project uses Python, Pandas, NumPy, Matplotlib, and Seaborn to analyze customer data and visualize important business insights.

## 2. Dataset Overview

- Total customers: 7,043
- Total columns: 21
- Churned customers: 1,869
- Retained customers: 5,174
- Overall churn rate: 26.54%

## 3. Data Cleaning

The following data-cleaning steps were performed:

- Converted `TotalCharges` into a numeric column.
- Identified 11 blank `TotalCharges` values.
- Filled those 11 values with zero because the corresponding customers had zero months of tenure.
- Checked for duplicate records.
- Verified that each customer ID was unique.
- Confirmed that no missing values remained after cleaning.

## 4. Key Findings

### Finding 1: Overall Customer Churn

The overall churn rate was 26.54%. Out of 7,043 customers, 1,869 had churned, while 5,174 remained customers.

### Finding 2: Contract Type

Customers with month-to-month contracts had a churn rate of 42.71%. Customers with one-year contracts had a churn rate of 11.27%, while customers with two-year contracts had a churn rate of only 2.83%.

**Business insight:** Month-to-month contracts were strongly associated with higher customer churn.

### Finding 3: Customer Tenure

Customers who churned had a median tenure of approximately 10 months, compared with approximately 38 months for customers who stayed.

**Business insight:** Customer retention efforts may be particularly valuable during the early months of the customer relationship.

### Finding 4: Monthly Charges

Customers who churned had average monthly charges of approximately 74.44, compared with 61.27 for retained customers.

**Business insight:** Higher monthly charges were associated with higher churn in this dataset.

### Finding 5: Internet Service

Customers using fiber-optic internet had a churn rate of 41.89%. DSL customers had a churn rate of 18.96%, while customers without internet service had a churn rate of 7.40%.

**Business insight:** Fiber-optic customers represent a group worth investigating further to understand their service experience and retention needs.

### Finding 6: Payment Method

Customers using electronic checks had the highest churn rate at 45.29%. The churn rates for mailed checks, automatic bank transfers, and automatic credit-card payments were 19.11%, 16.71%, and 15.24%, respectively.

**Business insight:** The relationship between payment method and churn deserves further investigation.

### Finding 7: Customer Demographics

Senior citizens had a churn rate of 41.68%, compared with 23.61% for other customers.

Customers without partners had a churn rate of 32.96%, compared with 19.66% for customers with partners.

Customers without dependents had a churn rate of 31.28%, compared with 15.45% for customers with dependents.

**Business insight:** Churn patterns differed across customer groups, suggesting that retention strategies may benefit from customer segmentation.

### Finding 8: Online Security and Technical Support

Customers without online security had a churn rate of 41.77%, compared with 14.61% for customers who had online security.

Customers without technical support had a churn rate of 41.64%, compared with 15.17% for customers who had technical support.

**Business insight:** The availability or use of additional support and security services was associated with lower churn.

## 5. Business Recommendations

1. Investigate ways to improve retention among month-to-month contract customers.
2. Pay attention to new customers during their early months.
3. Review pricing, perceived value, and service satisfaction among customers with higher monthly charges.
4. Investigate customer experiences among fiber-optic internet users.
5. Examine whether electronic-check users experience payment or billing difficulties.
6. Evaluate the needs of customer groups with higher observed churn rates.
7. Explore whether online security and technical support offerings can improve customer satisfaction and retention.

These recommendations should be validated with further analysis or customer feedback before implementation.

## 6. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## 7. Conclusion

The analysis identified several customer characteristics associated with churn, including contract type, tenure, monthly charges, internet service, payment method, and the availability of support and security services.

The findings can help guide further investigation into customer retention strategies. However, these are observational patterns and do not establish that any individual factor directly causes churn.

## 8. Future Improvements

- Build an interactive churn dashboard.
- Perform deeper customer segmentation.
- Develop a machine-learning model to predict churn.
- Evaluate model performance using suitable classification metrics.
- Identify customer segments that may benefit from targeted retention efforts.