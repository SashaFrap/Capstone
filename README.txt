Vehicle Emissions Prediction Project
This project aims to predict the amount of CO2 a vehicle will emit based on its characteristics such as engine size, type of fuel used, and transmission type. We use machine learning to understand how different features of vehicles affect their emissions. The goal is to help in environmental assessments and to guide regulations that might help reduce vehicle emissions.
Data
The dataset used includes information on 639 vehicles from the year 2000, detailing aspects like engine size, fuel type, and CO2 emissions. It's a publicly available dataset originally intended for regulatory use, to monitor the environmental impact of different vehicle types.
Model
We chose a Gradient Boosting Machine (GBM) model for its effectiveness in handling complex, non-linear relationships between features in structured data. This model is particularly good at regression tasks like predicting emissions based on various vehicle attributes.
Hyperparameter Optimisation
The hyperparameters optimised were:
* n_estimators: Number of trees in the forest.
* learning_rate: Speed at which the model learns.
* max_depth: Maximum depth of each tree.
We used a grid search approach, testing combinations of these parameters and measuring their performance using cross-validation, to find the best settings that minimise prediction errors.
Results
The optimised model significantly improved the predictions of vehicle emissions, achieving a low mean squared error (MSE) and high R-squared value, indicating accurate predictions and a high percentage of variance explained by the model. This suggests that our model can reliably predict emissions, which could be used to help manufacturers and regulators make better decisions to reduce vehicle emissions.

