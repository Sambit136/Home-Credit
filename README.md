# Home Credit

### Summary of business problem and project objective

Home Credit is presently encountering the risk of loan defaults due to extending loans to
individuals in underserved demographics, who possess either inadequate or non-existent credit
histories.

The proposed project aims to iden@fy customers with low or no risk, enabling the provision of
loans to this group. The project will employ the following analy@cal problem-solving approach
The goal is to iden@fy customers with both low and high risks of loan repayment through
the implementa@on of a predic@ve classifica@on model.

The binary target variable is the "target" column, indica@ng whether a customer is
experiencing payment difficul@es with their loan or not. Predictor includes columns like
AMT_INCOME_TOTAL, AMT_CREDIT, FLAG_OWN_CAR, FLAG_OWN_REALTY

The success of this project lies on the effective identification of both low and high-risk
customers. By achieving this, Home Credit can expand its loan offerings for low-risk customers,
thereby increasing revenue generation and enhancing overall profitability.

The project output will include a roster of customers who are likely to repay the loan amount,
ensuring that individuals with no credit history are not rejected.

### Group's solution to the business problem
Predictive Modelling: Home Credit can use the predictive modelling system that accurately assesses the credit risk of individuals with limited credit histories.
Home Credit can use machine learning, data mining, and statistical analysis to glean insights from unconventional data. This involves collecting, preprocessing, and engineering relevant variables from large datasets, then training predictive models using algorithms like logistic regression, decision trees, random forests, or neural networks. They must also rigorously validate and fine-tune these models to ensure accuracy and fairness

### Contribution to the project

Below are my contribution to the project while creating my notebook

Data cleaning and Pre processing : Outlining steps for data cleaning, one-hot encoding, and handling missing values.
Model Selection: Discussing the use of decision trees, logistic regression, KNN, and gradient boosting for modeling
Algorithm Evaluation: Comparing algorithm performance and discussing implications.
Analysis Summary: Presenting results, interpretations, and suggestions for future work.

### The business value of the solution.

Improved Decision Making: Accurate predictions and data classification inform better business strategies and resource allocation.
Revenue Growth: Home Credit has the opportunity to tailor loan offers and outreach strategies to appeal to low-risk customers, including individuals with higher education, homeownership, and a limited number of Credit Bureau inquiries within a year.

### Difficulties that your group encountered along the way.

Data Quality Issues
Problem:Our datasets had many missing values across different features, a common occurrence in real-world data, particularly in finance where applicants may not disclose all information.
Solution: We used imputation to fill missing numeric data with column medians and missing categorical data with modes. Columns with over 50% missing values were considered for removal due to potential reliability issues.
Technical Challenges
Problem:The 'TARGET' variable exhibited high imbalance, a common trait in default prediction datasets. This imbalance poses a notable challenge for predictive modeling as it skews the model towards the majority class.
Solution:
We utilized downsampling techniques to address dataset imbalance, which involved decreasing the number of majority class samples to align with the minority class. This approach ensured that our model didn't overlook the crucial minority class (defaults).
Model Selection and Tuning: 
Problem:Choosing the right model and tuning hyperparameters were highly iterative and time-consuming tasks.
Solution: We experimented with multiple algorithms, including logistic regression, decision trees, and ensemble methods like Random Forest and Gradient Boosting. Using cross-validation, we fine-tuned the hyperparameters to find the best model settings.


### Learning

Technical: Learnt various data preprocessing techniques, machine learning algorithms, and model evaluation methods.

Business: Ensured the ability to connect insights derived from data analysis to practical business solutions and decision-making processes.
Presentation: During presentations to stakeholders, it's important to prioritize business insights and recommendations on the slides over technical procedures.


