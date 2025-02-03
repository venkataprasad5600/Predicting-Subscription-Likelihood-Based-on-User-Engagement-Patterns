# 📌 Predicting-Subscription-Likelihood-Based-on-User-Engagement-Patterns

# 📝 Overview
In this project, we harness the power of Machine Learning (ML) and Artificial Intelligence (AI) to help a company classify its trial app users into two categories:
1. Likely to Subscribe
2. Unlikely to Subscribe

The ultimate goal is to provide the management team with data-driven insights to optimize investment decisions and improve subscription rates. This project focuses on analyzing user behavior and predicting their likelihood to subscribe based on app-usage data.

# 🎯 Problem Statement
With increasing competition in app-based services, it is crucial to understand user behavior and predict which trial users are likely to become paying subscribers. By analyzing app usage patterns and behavioral data, this project aims to:
- Classify users as likely or unlikely to subscribe.
- Provide actionable insights to improve marketing strategies and user engagement.



# 🏷️ Dataset Description : 
The project uses the following datasets:
1. appdataset.csv: Contains primary app usage data.
2. new_appdata10.csv: Updated app usage data for additional analysis.
3. top_screens.csv : Provides information about the most frequently used app screens.

# ✨ Key features include:
- User Engagement Metrics : Time spent on the app, number of sessions, etc.
- Behavioral Patterns: Screens visited, actions performed.
- Subscription Status : Labels for supervised learning models.

# 💻 Project Workflow
The project is structured as follows:

Step 1: Data Understanding and Preprocessing.
1. Load and inspect datasets (appdataset.csv, new_appdata10.csv, top_screens.csv).
2. Handle missing or inconsistent data.
3. Engineer new features (e.g., session durations, screen visit counts).
4. Normalize and scale the data for better model performance.

Step 2: Exploratory Data Analysis (EDA)
1. Visualize user engagement trends (e.g., time spent on specific screens).
2. Identify correlations between user actions and subscription likelihood.
3. Analyze patterns in the most frequently used app screens.

Step 3: Machine Learning Model Development
1.Model Selection:
   - Use classification algorithms such as Logistic Regression, Random Forest, or Gradient Boosting.
2 Training and Validation:
   - Split data into training and validation sets.
   - Optimize model performance using techniques like hyperparameter tuning.
3.Evaluation :
   - Evaluate models using metrics like accuracy, precision, recall, and F1-score.

# 🛠️ Technologies Used
- Programming Language: Python
- Libraries and Tools:
  - Pandas: Data manipulation and analysis.
  - NumPy: Numerical computations.
  - Matplotlib & Seaborn: Data visualization.
  - Scikit-learn: Machine learning algorithms like logistic Regression and grid search.
  - Jupyter Notebook: Code execution and documents 


# 📊 Key Insights
Certain app screens are strongly correlated with subscription likelihood.
Users who interact with specific features are more likely to subscribe.
Engagement duration and frequency are critical factors in determining subscription rates.
Results
Successfully classified users into likely and unlikely to subscribe.
Identified actionable insights to improve user retention and conversion rates.

# 🚀 Future Work
Implement a recommendation system to improve user engagement.
Incorporate time-series analysis for better predictions.
Extend the analysis to include user demographics and feedback.

# License
This project is licensed under the MIT License.

