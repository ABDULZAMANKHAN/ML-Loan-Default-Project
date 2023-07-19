# ML-Loan-Default-Project

●	Developed ML models (Logistic Regression, Random Forest Classifier, Decision Tree Classifier) with high accuracies (0.87, 1.0, 0.99) to predict loan default. 
●	Utilized Python libraries: Pandas, Matplotlib, Seaborn, Scikit-learn for data preprocessing, missing values, feature engineering, and model building. 
●	Employed visualizations (histograms, boxplots, barplots, pairplots, correlation heatmaps) to analyze data distribution, identify key variables, and understand their impact on the target variable.
●	Addressed outliers using boxplots to ensure data integrity and enhance model performance. 
●	Utilized PyCaret library to streamline model development, achieving high accuracies (Gradient Boosting Classifier: 0.9906, Random Forest Classifier: 0.9903), comparing with Logistic Regression (0.7616) and SVM with Linear Kernel (0.5552).

In this project, I performed Exploratory Data Analysis (EDA) to gain insights into our dataset before building a predictive model.
Here are the key steps I followed during EDA to extract valuable information from the data:

Understanding the Data Structure:
Examining the dimensions of the dataset using df.shape to get the number of rows and columns.
Using df.head() or df.tail() to inspect a few rows and understand the data's structure.

Summarizing the Data:
Using df.info() to get an overview of the data types and missing values in each column.
Utilizing df.describe() to generate descriptive statistics for numerical columns, such as mean, standard deviation, minimum, maximum, quartiles, etc.
Analyzing unique values and frequency counts in categorical columns using df['column_name'].value_counts().

Handling Missing Values:
Identifying missing values using df.isnull().sum() and assessing their impact on the dataset.
Deciding on an appropriate strategy to handle missing values, such as imputation or removal, based on the nature and extent of missing data.

Visualizing the Data:
Creating various plots and visualizations to understand the distributions, relationships, and patterns within the data.
Using histograms, box plots, and density plots to examine the distribution of numerical variables.
Utilizing bar plots, pie charts, and count plots to visualize categorical variables.
Plotting correlation matrices or heatmaps to explore relationships between variables.
Generating scatter plots or pair plots to visualize the interactions between multiple variables.

Identifying Outliers:
Detecting outliers that may exist in the dataset, as they can impact the model's performance.
Using box plots, scatter plots, or statistical techniques like Z-score or IQR (Interquartile Range) to identify and handle outliers appropriately.

Analyzing Feature Relationships:
Investigating the relationships between independent variables and the target variable.
Using scatter plots, line plots, or box plots to identify trends, correlations, or dependencies.
Computing correlation coefficients (e.g., Pearson's correlation) to quantify the strength and direction of relationships.

Feature Engineering:
Creating new features or transforming existing ones to enhance the predictive power of the model.
Generating derived variables, performing scaling, or applying mathematical transformations based on domain knowledge.

Addressing Data Inconsistencies and Errors:
Identifying and correcting any inconsistencies, errors, or anomalies in the data that could impact the model's performance.
Handling erroneous values, duplicates, or data entry mistakes as necessary.
Remember, EDA is an iterative process, and I refined these steps as I gained more insights into the data. EDA helped me understand the data better,
identify potential issues, and make informed decisions when preprocessing, selecting features, and building the machine learning model.
