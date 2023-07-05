# loan_acceptance

## This project is to check the acceptance of loan credit.

* Machine Learning: predict loan acceptance



* Data Visualization
  * Read the loan credit dataset from a CSV file "Loan_Train.csv" using the `read_csv()` function.
  * Encode the categorical variables using the `OneHotEncoder` from `scikit-learn`, and store the encoded variables in a new DataFrame.
  * Concatenate the original numerical variables with the encoded variables DataFrame using the `concat()` function.
  * Select the columns representing loan acceptance categories and create a new DataFrame with the selected columns.
  * Use `loc()` function to replace the values of Loan_Status_Y with "Yes" and "No".
  * Calculate the count of loan acceptance for each category using `sum()` function.
  * Create a stacked bar chart using `plot()` function.


* Chatbot: Streamlit Interface - text box



* Model.predict() 
