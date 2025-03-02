## Subscriber Churn Prediction & Segmentation
### Tools & Technologies:
Python, Pandas, Scikit-Learn, Logistic Regression, Decision Tree, Random Forest, K-Means Clustering, Matplotlib, Seaborn

### Project Overview:
Developed classification models to predict subscriber churn and applied clustering analysis to segment users for AZ Watch, an educational streaming platform.

* Trained Logistic Regression, Decision Tree, and Random Forest models, achieving 92.5% accuracy for churn prediction.
* Applied K-Means clustering (k=3) to segment subscribers based on engagement behavior.
* Found that low-frequency, short-session users had higher churn risks.
* Used feature engineering & data preprocessing to improve model performance and segmentation accuracy.

### Key Contributions:
#### Churn Prediction Models:
* Trained Logistic Regression, Decision Tree, and Random Forest models to classify subscribers.
* Achieved 92.5% accuracy with Logistic Regression, the best-performing model.
#### Customer Segmentation:
* Applied K-Means clustering (k=3) to group subscribers based on engagement time and frequency.
* Identified that low-engagement users had higher churn rates, while frequent users showed high retention.
#### Feature Engineering & Preprocessing:
* One-hot encoded categorical variables (age group) to enhance model interpretability.
* Standardized numerical features for clustering analysis.

### Impact & Insights:
* Discovered that subscribers with high engagement frequency are less likely to churn.
* Recommended personalized marketing strategies, such as re-engagement emails for low-frequency users.
* Insights enable AZ Watch to optimize retention efforts and improve targeted campaigns.




## Customer Churn Prediction & Retention Strategies
### Tools & Technologies:
Python, Pandas, Scikit-Learn, Logistic Regression, Random Forest, Matplotlib, Seaborn

### Project Overview:
Developed classification models to predict customer churn in a telecom dataset, aiming to help businesses improve customer retention strategies.

* Developed Logistic Regression & Random Forest models to predict customer churn, achieving 95% accuracy.
* Engineered features, converting categorical data and applying scaling techniques for improved model performance.
* Conducted EDA, revealing customer service interactions and international plans as key churn predictors.
* Evaluated models using precision, recall, and F1-score, applying GridSearchCV for hyperparameter tuning.

### Key Contributions:
#### Exploratory Data Analysis (EDA):
* Analyzed customer behavior, including call duration, international plans, and customer service interactions.
* Found that higher customer service calls and international plan subscriptions correlate with higher churn rates.
#### Feature Engineering & Data Preprocessing:
* Converted categorical variables (Intl Plan, Vmail Plan, State) into numerical form.
* Scaled numerical features using StandardScaler to improve model performance.
#### Churn Prediction Models:
* Built Logistic Regression, Decision Tree, and Random Forest models to classify customers as likely to churn or stay.
* Random Forest achieved 95% accuracy, outperforming other models.
#### Model Evaluation & Optimization:
* Evaluated models using confusion matrix, precision, recall, and F1-score.
* Applied hyperparameter tuning (GridSearchCV & RandomizedSearchCV) to improve performance.

### Impact & Insights:
* Customers with high customer service interactions and international plans were more likely to churn.
* Reducing customer service issues and offering loyalty incentives can help minimize churn.
* Suggested targeted engagement strategies for at-risk customers based on data-driven insights.