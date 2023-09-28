# Churn Prediction Project
Customer churn, often referred to as customer attrition, is a critical business metric that measures the rate at which customers stop doing business with a company. Predicting churn is essential for businesses to take proactive actions and retain valuable customers.
### Detailed description of the columns in the dataset
1. CustomerID: The unique identifier of the customer. Each client has a unique identifier for identification.
2. gender: The gender of the client. It can be "Male" (male) or "Female" (female).

3. SeniorCitizen: An indicator indicating whether the client is a senior citizen. This is a binary sign, where 1 denotes an elderly citizen, and 0 does not.

4. Partner: An indicator indicating whether the client has a roommate (partner). This is a binary sign, where "Yes" (yes) means the presence of a partner, and "No" (no) - his absence.

5. Dependents: An indicator indicating whether the client has dependents (children or other dependent persons). This is a binary sign, where "Yes" (yes) means the presence of dependents, and "No" (no) - their absence.

6. tenure: The number of months that the client is already a client of the company. This is a quantitative attribute representing the duration of customer service.

7. PhoneService: An indicator indicating whether the telephone service is connected for the client. This is a binary sign, where "Yes" (yes) means the presence of a service, and "No" (no) - its absence.

8. MultipleLines: An indicator indicating whether the client has multiple lines (telephone lines). This is a categorical attribute that can take the values "Yes" (yes), "No" (no) or "No phone service" (no telephone service).

9. InternetService: The type of Internet connection provided to the client. This is a categorical attribute that can take values such as "DSL", "Fiber optic" (optical fiber) or "No" (no Internet connection).

10. OnlineSecurity: An indicator indicating whether an online security service is provided to the client. This is a categorical attribute that can take the values "Yes" (yes), "No" (no) or "No internet service" (no Internet connection).

11. OnlineBackup: An indicator indicating whether an online data backup service is provided to the client. This is a categorical attribute similar to OnlineSecurity.

12. DeviceProtection: An indicator indicating whether a device protection service is provided to the client. This is a categorical attribute similar to OnlineSecurity.

13. TechSupport: An indicator indicating whether a technical support service is provided to the customer. This is a categorical attribute similar to OnlineSecurity.

14. StreamingTV: An indicator indicating whether a streaming TV service is provided to the customer. This is a categorical attribute similar to OnlineSecurity.

15. StreamingMovies: An indicator indicating whether a movie streaming service is provided to the client. This is a categorical attribute similar to OnlineSecurity.

16. Contract: The type of contract concluded by the client with the company. This is a categorical attribute that can take the values "Month-to-month" (monthly), "One year" (annual) or "Two year" (two-year).

17. PaperlessBilling: An indicator indicating whether a customer uses paper invoices or electronic billing. This is a binary sign, where "Yes" (yes) means the use of electronic accounts, and "No" (no) - paper.

18. PaymentMethod: Payment method for services. This is a categorical attribute that can take on various meanings, such as "Electronic check" (electronic check), "Credit card (automatic)" (credit card with autopayment) and others.

19. MonthlyCharges: The client's monthly payments for services.

20. TotalCharges: Total expenses of the client for services for all time.

21. Churn: An indicator indicating whether the client has left (outflow) or stayed. This is a binary sign, where "Yes" (yes) means the outflow of the client, and "No" (no) - remained.

These columns contain information about customers and their services, which makes them important when solving the problem of forecasting Churn (Churn Prediction) or other tasks in the field of customer base analysis.

## Project Overview
In this project, we have developed a churn prediction model using Python and scikit-learn. The model is built on a dataset named 'churn.csv', which contains various customer-related features, including customer demographics and usage patterns.

## Key Steps in the Project
1. Data Preprocessing:

- We start by loading the dataset and checking for missing values, ensuring that the data is clean and ready for analysis.
- Data types are examined, and numeric inconsistencies in the 'TotalCharges' column are addressed.
- Categorical variables are encoded, and the target variable 'Churn' is transformed into binary values.
2. Data Scaling:

- The feature data is standardized using the StandardScaler to ensure that all features have the same scale.
3. Model Building:

- We split the dataset into training and testing sets.
- Hyperparameter tuning is performed using GridSearchCV with logistic regression as the base model.
- The best hyperparameters are identified, and the optimal model is trained on the training data.
4. Model Evaluation:

- The model's performance is evaluated on the testing data, and key metrics such as accuracy are recorded.
5. Results:

- The project reports the best hyperparameters for the logistic regression model and its performance on the test data.
## Note:

This description provides an overview of the project. If necessary, you can add more detailed information, results and conclusions from data analysis and experiments with models.
## Author
The author of this project: Aleksandr Loginov   https://github.com/LoginovAM-ds
## Connection
If you have any questions or suggestions, feel free to contact me via a.loginov.ds@gmail.com or https://www.facebook.com/profile.php?id=100074840106705.