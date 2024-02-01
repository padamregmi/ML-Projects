A fully functional ML pipeline to predict the loan grant for the customer based on the customer profile features Age, credit_score, loan_amount_requested,annual_income, employment_years

Steps involved:
1. Preprocesse data
2. EDA
3. Pipeline for numerical columns and categorical columns-< Age
4. Merge pipelines using ColumnTransformer
5. Build a complete pipeline
6. Deploy the model using modelbit
7. Create function to call the pipeline using modelbit which creates REST API endpoint to call the deployed model
8. Call the API using CURL command to test the model prediction
