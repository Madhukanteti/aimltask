http://localhost:8890/notebooks/madhuaimltask.ipynb
Step 1: Dataset Creation
Created a  dataset with the following features:

Task ID

Task Complexity (Low, Medium, High)

User Engagement (Low, Medium, High)

Task Duration (in hours)

Completed On Time (Yes/No)

Used Python libraries like pandas and numpy to generate the dataset.

Step 2: Model Development
Used RandomForestRegressor from scikit-learn to predict task duration based on:

Task Complexity

User Engagement

Split the dataset into training and testing sets.

Evaluated the model using Mean Squared Error (MSE).

Saved the trained model to a file (model.pkl) using pickle.

Step 3: Visualization
Generated visualizations to analyze the model's performance:

Actual vs Predicted Task Duration (scatter plot).

Feature Importance (bar plot).

Saved these visualizations as image files (actual_vs_predicted.png and feature_importance.png).

