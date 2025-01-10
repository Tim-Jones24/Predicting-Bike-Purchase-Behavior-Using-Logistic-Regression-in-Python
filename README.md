# Predicting Bike Purchase Behavior Using Logistic Regression in Python
This project explores the prediction of bike purchase behavior among customers using Logistic Regression Model.

#### Overview
The goal of this project is to predict whether a customer is likely to purchase a bike based on given features. Using a Logistic Regression model, the project identifies patterns in the data and evaluates the model's performance

####  Workflow
1. Data Preparation:
   * Loaded data into Python.
   * Performed descriptive analysis for abetter understanding of the dataset.
   * Dropped unncessary feature (ID) to focus on meaningful features.
   * Converted categorical variables into numerical using Label Encoding.

2. Feature Engineering: 
   * Conducted a collinearity check to asses realtionships betwen predictors
   * Scaled features to normalize the data for better model performance.

3. Model Development:
   * Defined features (X) and Traget variable (Y).
   * Split the dataset into training and testing sets.
   * Implemented a Logistic Regression Model to predict bike purchases.

4. Model Evaluation:
   * Evaluated the model's performance using:
     * Accuracy: 59%
     * Mean Squared Error: 0.41
     * Root Mean Squared Error (RMSE): 0.6403
5. Deployment:
   * Deployed the model to work with new data for practical applications.

#### Tools and Technologies:
* Languages: Python
* Libraries: Pandas, Numpy, Seaborn, Scikit-learn.

#### Project Objectives:
* Predict customer bike purchase behavior based on given data.
* Use Logistic Regression to identify factors influencing purchasing decisions.
* Evaluate and deploy the model to enable predictions on unseen data.

#### Key Insights:
* Factors influencing bike purchase behaivior were identified and modeled
* Predictions cab assit businesses in targeting potential customers.

#### Conclusion
Leveraging Python and key libraries this project helped to identify the liklihood of a customer purchasing a bike based on various features. The model achieved an RMSE score of 0.6403, highlighting areas of improvement and further exploration.

#### Future Work
* Experiment with advanced algorithms like Random Forest and Gradient Boosting.
* Otimize hyperparameters to improve model accuracy.
* Explore feature engineering for better predictions.
