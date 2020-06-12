# S2E-dfki-Predict-the-department-wide-sales-for-each-store

# Approaches
1. Pre-processing
2. Feature Engineering
3. Machine Learning (Linear Regression, Gradient Boosting)
4. Deep Learning (LSTM)

# Prepossessing
1. 3 datasets (sales, stores, feature)
2. Spit the sales data into train and test
3. Merge train, feature
4. Handling Missing Value 
5. Extract 3 month (Aug 2012-Oct 2012) from Merge dataset.

# Feature Engineering
1. String ‘Date’ into dataframe object.
2. ‘Weekly_Sales’ for each Date         sale_to_date
3. ‘Weekly_Sales’ of each ‘Store’ and ‘Dept’          sale_to_dept_store
4. ‘IsHoliday’ column contains boolean          int
5. Split the data set
6. OneHotEncoder: Encode categorical features as a one-hot numeric array.
7. Applied Encode categorical features as a one-hot numeric array.
8. Applied OneHotEncoder on ‘Store’ Feature


