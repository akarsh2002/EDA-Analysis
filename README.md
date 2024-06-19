Analysis for X Education
This analysis aims to find ways to attract more industry professionals to X Education's courses.

Steps Taken:
Data Cleaning:

Replaced 'option select' with null values.
Converted null values to 'not provided', later removed during dummy creation.
Categorized location data into 'India', 'Outside India', and 'not provided'.
Exploratory Data Analysis (EDA):

Identified irrelevant elements in categorical variables.
No outliers in numeric values.
Dummy Variables:

Created dummies and removed 'not provided' elements.
Applied MinMaxScaler to numeric values.
Train-Test Split:

Split data into 70% training and 30% testing sets.
Model Building:

Used RFE for top 15 variables.
Manually removed variables with VIF < 5 and p-value < 0.05.
Model Evaluation:

Confusion matrix and ROC curve used for evaluation.
Achieved 80% accuracy, sensitivity, and specificity.
Prediction:

Optimum cut-off at 0.35 with 80% accuracy, sensitivity, and specificity on test data.
Precision-Recall:

Found cut-off at 0.41 with 73% precision and 75% recall on test data.
Key Findings:
Top factors influencing potential buyers:

Total time spent on the website.
Total number of visits.
Lead sources: Google, Direct traffic, Organic search, Welingak website.
Last activity: SMS, Olark chat conversation.
Lead origin: Lead add format.
Current occupation as a working professional.

Conclusion:
By focusing on these factors, X Education can significantly increase their conversion rates and attract more industry professionals to their courses.
