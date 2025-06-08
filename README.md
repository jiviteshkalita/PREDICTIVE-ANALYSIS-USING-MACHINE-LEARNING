# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
Company : CODTECH IT SOLUTIONS. 
Name : Jivitesh Kalita. 
Intern ID : CT04DN972. 
Domain : Data Analytics. 
Duration : 6 weeks. 
Mentor : Neela Santosh. 
Description:
This task was executed using Jupyter Notebook, a web-based interactive computing platform that supports live code, visualizations, and narrative text.
The goal of this project is to analyze customer data from a telecommunications company and develop a predictive model to determine whether a customer is likely to churn (i.e., stop using the company's services). This is a common business problem in the telecom sector, where customer retention is significantly more cost-effective than acquisition.

The project is divided into two phases:

Exploratory Data Analysis (EDA) – file: task2EDAnew.ipynb

Model Building and Evaluation – file: task2modelbuilding.ipynb
Phase 1: Exploratory Data Analysis (EDA)
In the EDA notebook, various preprocessing and visualization steps are undertaken to gain insight into the dataset and prepare it for modeling.

Key Tasks:

Data Loading and Inspection: The Telco dataset (CSV format) is loaded using Pandas, and essential checks are performed, such as examining null values, data types, and column distributions.

Data Cleaning: Columns with inconsistent data (e.g., "TotalCharges" being object type instead of float) are cleaned and converted into the appropriate format.

Descriptive Statistics: Summary statistics (mean, median, mode, etc.) help understand the central tendencies and spread of data.

Univariate Analysis: Features like gender, contract type, tenure, payment method, etc., are individually analyzed using bar plots and histograms.

Bivariate Analysis: Relationships between variables (e.g., contract type vs churn, tenure vs churn) are explored using visual tools such as box plots and heatmaps.

Label Encoding: Categorical variables are encoded to prepare for machine learning algorithms.

Phase 2: Model Building
In the model building notebook, the cleaned and preprocessed dataset is used to train and evaluate several classification models.

Key Tasks:

Train-Test Split: The dataset is divided into training and test sets to evaluate generalizability.

Feature Scaling: Techniques like StandardScaler are used to bring numerical features to the same scale.

Model Training: Various machine learning classifiers such as:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

Decision Tree
are trained on the data.

Evaluation Metrics: Models are evaluated based on metrics such as:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix
These help identify not just overall accuracy but also how well models handle both churned and non-churned customers.

Model Comparison: All models are compared to identify the most effective one for churn prediction.

Practical Applications:
Customer Retention: Companies can use this model to identify at-risk customers and target them with promotions or support.

Revenue Assurance: Proactively managing churn can lead to higher lifetime customer value and more stable revenue.

Marketing Optimization: Helps allocate resources effectively by targeting likely churners with personalized offers.

Churn Analytics Tools: Forms the backend of dashboards or APIs that enable real-time churn prediction.

Output : ![Image](https://github.com/user-att)achments/assets/f99c4992-c05d-4b5c-8844-60d53f412494

