This project utilized the Boston housing dataset to create a machine learning model capable of predicting a home's value based on its various features. The project followed all the standard steps of a data analysis pipeline to identify and optimize the most accurate predictive model.

Project Process and Actions:

Data Exploration and Preprocessing: At the start of the project, the dataset's structure was examined, and data cleaning was performed by filling 5 missing values in the $RM$ column with the median.

Model Comparison: A total of 15 different regression models, including linear regression, decision trees, random forests, and gradient boosting, were trained and their performances were compared. In this phase, the Gradient Boosting and Random Forest models stood out with the highest R 
2
  scores.

Model Optimization: To further enhance the performance of the top-performing Random Forest and Gradient Boosting models, their hyperparameters were tuned using the GridSearchCV method.

Feature Importance Analysis: Using the best-performing model, Random Forest, the most influential features in predicting housing prices were identified. This analysis determined that the average number of rooms per dwelling (RM) and the percentage of the population in lower status (LSTAT) had the greatest impact on predictions.

Saving the Final Model: As the final step of the project, the best-performing model (Random Forest) and the data scaling tool (scaler) were saved as files for future use in making predictions.

Results Obtained:

The project resulted in a high-accuracy, optimized Random Forest Regression Model for predicting housing prices. This model not only achieved a high R 
2
  score (0.6826) but also provided valuable insights into the key features driving its predictions.
