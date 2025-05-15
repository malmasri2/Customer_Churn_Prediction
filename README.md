# Customer_Churn_Prediction
This project focuses on predicting customer churn in a subscription-based streaming service using machine learning techniques. The objective is to help businesses identify users who are likely to cancel their subscriptions and take preventive actions to retain them.

The dataset includes information on customer demographics, engagement behavior (e.g., watch time, number of logins), subscription details (e.g., membership type, payment issues), and customer support history (e.g., number of complaints, resolution time). The target variable is a binary churn indicator (churned or not).

The project was carried out in several stages:

1)(Data Exploration & Cleaning)
The dataset was examined for missing values, outliers, and data types. Descriptive statistics and visualizations such as histograms and boxplots were used to understand trends and relationships. Correlation matrices helped identify which variables might influence churn.

2)(Modeling with Decision Trees)
A decision tree classifier was trained using scikit-learn. Hyperparameters such as tree depth and split criteria were optimized using GridSearchCV. SMOTE was applied to balance the dataset due to class imbalance. Model performance was evaluated using accuracy, precision, recall, F1 score, and confusion matrices.

3)(Improvement with Random Forests)
To improve predictive performance, a random forest classifier was built and tuned. It showed significant improvement in all evaluation metrics compared to the single decision tree. Feature importance analysis revealed that engagement-related features like watch time and number of logins were key predictors of churn.

4)(Business Insights & Recommendations)
The results were translated into actionable strategies. These included enhancing personalized content recommendations, reducing customer support resolution time, and offering loyalty incentives to long-term subscribers.
