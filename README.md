# Retail-dataset-analysis

Data analysis and model evaluation on the retail dataset I made while participating in the ML Bootcamp by Global AI Hub.
You can access my notebook from the link : https://www.kaggle.com/code/cansusary/retail-analysis-bc

# Problem Identification

The project began with identifying a key business problem: analyzing customer purchasing behavior to uncover insights that can guide marketing strategies and improve sales. The primary goal was to explore relationships between customer segments, product categories, and purchasing patterns to predict trends and better understand customer preferences.

# Library Installation and Import 

Before diving into the analysis, necessary Python libraries were installed and imported, including Pandas, NumPy, Matplotlib, Seaborn for data handling and visualization, as well as Scikit-learn for machine learning models. These tools are essential for managing data, creating visual insights, and building predictive models.

# Data Loading and Reading

# Exploratory Data Analysis (EDA)

An initial Exploratory Data Analysis (EDA) was conducted to summarize the dataset. Descriptive statistics like mean, median, and distribution of variables were computed. Additionally, visualizations such as bar plots and count plots were created to provide insights into customer distribution, purchasing trends, and product preferences.

# Data Cleaning and Handling Missing Values

The next step involved cleaning the dataset. Missing values were detected using methods like isnull() and filled or dropped where appropriate. For numerical columns, imputation techniques like filling with mean or median values were used.

# Data Visualization

To gain deeper insights, various data visualizations were generated using Seaborn and Matplotlib. Bar plots, correlation heatmaps, and scatter plots allowed for visual interpretation of relationships between customer segments, product categories, and purchasing behavior. These visualizations helped to identify patterns and correlations that could influence modeling decisions.

# Machine Learning Model Selection and Building

Several machine learning algorithms were considered to determine the most suitable model. Linear regression and K-means clustering were chosen for initial experimentation. Linear regression was used to predict customer purchases based on features like amount and age, while K-means clustering helped identify customer segments based on purchasing behavior.

# Target Variable and Feature Selection

Careful consideration was given to selecting the target variable (Total Purchases) and the relevant features for the models.

# Cross-Validation

Cross-validation was applied to both models to evaluate their performance across different data splits. For linear regression, R-squared scores were calculated, while silhouette scores were used for the K-means model. These metrics helped assess the stability and accuracy of the models across multiple folds.

# Hyperparameter Optimization

Since K-means produced more favorable results, hyperparameter optimization was performed using Random Search to the model. This optimization step helped identify the best number of clusters and other model parameters, enhancing the model’s performance.

# Model Evaluation

The K-means algorithm was determined to be more suitable for the retail dataset. K-means is an unsupervised learning algorithm, which means it doesn’t require labeled data. Since the goal was to identify patterns and group customers based on their purchasing behavior, K-means was ideal for discovering hidden customer segments without predefined categories.
