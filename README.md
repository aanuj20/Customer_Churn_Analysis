# Overview

The analysis aims to understand the factors contributing to customer churn and to visualize the distribution of churned customers. The notebook includes data loading, data cleaning, exploratory data analysis (EDA), and visualization.

# Dataset Description
The dataset contains the following columns:
  * customerID: Unique identifier for each customer.
  * gender: Gender of the customer (Male/Female).
  * SeniorCitizen: Indicates if the customer is a senior citizen (1/0).
  * Partner: Indicates if the customer has a partner (Yes/No).
  * Dependents: Indicates if the customer has dependents (Yes/No).
  * tenure: Number of months the customer has stayed with the company.
  * PhoneService: Indicates if the customer has a phone service (Yes/No).
  * MultipleLines: Indicates if the customer has multiple lines (Yes/No/No phone service).
  * InternetService: Type of internet service (DSL/Fiber optic/No).
  * OnlineSecurity: Indicates if the customer has online security (Yes/No/No internet service).
  * OnlineBackup: Indicates if the customer has online backup (Yes/No/No internet service).
  * DeviceProtection: Indicates if the customer has device protection (Yes/No/No internet service).
  * TechSupport: Indicates if the customer has tech support (Yes/No/No internet service).
  * StreamingTV: Indicates if the customer has streaming TV (Yes/No/No internet service).
  * StreamingMovies: Indicates if the customer has streaming movies (Yes/No/No internet service).
  * Contract: Type of contract (Month-to-month/One year/Two year).
  * PaperlessBilling: Indicates if the customer has paperless billing (Yes/No).
  * PaymentMethod: Payment method (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic)).
  * MonthlyCharges: Monthly charges for the customer.
  * TotalCharges: Total charges for the customer.
  * Churn: Indicates if the customer has churned (Yes/No).

# Analysis Steps
1. Data Loading: The dataset is loaded using pandas.
2. Data Cleaning:
  * Missing values in the TotalCharges column are replaced with '0' and the column is converted to a float type.
  * The SeniorCitizen column is converted from binary (0/1) to categorical ('No'/'Yes').

3. Exploratory Data Analysis (EDA):
  * Basic statistics and information about the dataset are displayed.
  * The distribution of churned customers is visualized using a count plot.
  * The percentage of churned customers is calculated and visualized using a pie chart.
  * The distribution of churned customers by gender is visualized using a count plot.

# Visualizations
  * Count Plot of Churned Customers: Shows the number of customers who have churned versus those who have not.
  * Pie Chart of Churned Customers: Displays the percentage of churned customers.
  * Count Plot of Churned Customers by Gender: Illustrates the distribution of churned customers by gender.

# Dependencies
  * pandas
  * numpy
  * matplotlib
  * seaborn

# Usage
  To run this notebook, ensure you have the required libraries installed. You can install them using pip:

  pip install pandas numpy matplotlib seaborn

  Then, open the Jupyter Notebook and run each cell sequentially to perform the analysis and generate the visualizations.

# Conclusion
The analysis provides insights into the factors contributing to customer churn and helps in understanding the distribution of churned customers. The visualizations highlight key trends and patterns in the data, which can be used to develop strategies to reduce churn.
