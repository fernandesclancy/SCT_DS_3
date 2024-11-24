**Bank Marketing Decision Tree Classifier 📊**

About
This project aims to predict whether a customer will purchase a product or service based on their demographic and behavioral data using a Decision Tree Classifier. The analysis is performed on the Bank Marketing dataset, which is available on the UCI Machine Learning Repository.

Using Python and popular data analysis libraries, the project explores relationships between various features like age, job, education, and previous contact details to uncover patterns and trends related to customer purchase behavior.

Dataset
The dataset used in this project is the Bank Marketing dataset. It contains data from a direct marketing campaign for a bank, including attributes like:

Age: Age of the customer
Job: Type of job (e.g., admin, technician, services)
Marital: Marital status of the customer
Education: Education level of the customer
Default: Whether the customer has credit in default (yes/no)
Housing: Whether the customer has a housing loan (yes/no)
Loan: Whether the customer has a personal loan (yes/no)
Contact: Contact communication type (e.g., cellular, telephone)
Month: Last contact month of the year
Day_of_week: Last contact day of the week
Duration: Duration of the last contact in seconds
Campaign: Number of contacts performed during this campaign
Pdays: Number of days since the client was last contacted from a previous campaign
Previous: Number of contacts performed before this campaign
Poutcome: Outcome of the previous marketing campaign (success, failure)
Y: Whether the customer subscribed to a product (yes/no)
Analysis Workflow
1. Data Cleaning
Handled missing values in numerical and categorical columns.
Converted categorical variables into numerical values using Label Encoding.
Dropped irrelevant columns for analysis, such as duration (since it's highly correlated with the target variable).
2. Exploratory Data Analysis (EDA)
Key analyses conducted include:

Customer Subscription by Job: Visualized the subscription rates across different job types.
Survival by Age: Analyzed the distribution of age among customers who subscribed vs. those who did not.
Marital Status and Subscription: Explored how marital status affects subscription rates.
Correlation Analysis: Used heatmaps to identify significant correlations among features, especially related to age, previous contacts, and campaign success.
3. Modeling
A Decision Tree Classifier was trained using:

Features: Age, Job, Marital Status, Education, Loan, Contact Type, etc.
Target Variable: Whether the customer subscribed to the product (y).
Model Evaluation
Accuracy Score was used to measure the model's performance.
Confusion Matrix was used to evaluate the classification results.
Visualizations
Several visualizations were created to illustrate findings, including:

Subscription by Job Type
Age Distribution of Subscribers and Non-Subscribers
Heatmap for Feature Correlations
Decision Tree Visualization: A graphical representation of the trained decision tree classifier.
Libraries Used
pandas for data manipulation
matplotlib and seaborn for data visualization
scikit-learn for machine learning model
Key Findings
Job Type and Subscription: Certain job types like 'technician' and 'services' have a higher likelihood of subscribing to the product.
Age and Subscription: Younger customers are slightly more likely to subscribe to the product.
Loan and Subscription: Customers with personal loans are less likely to subscribe to the product.
Acknowledgements
Bank Marketing Dataset: UCI Machine Learning Repository
