# Olympics_ML_project
The Python code analyzes sports teams' data, emphasizing data cleaning, visualization using seaborn and matplotlib, and implementing a Linear Regression model for predictions.
1. Importing necessary libraries (pandas, numpy).
2. Loading data from a CSV file into a DataFrame for analysis.
3. Removing certain columns from the DataFrame.
4. Importing seaborn and matplotlib for data visualization.
5. Creating a scatter plot using seaborn's lmplot to analyze the relationship between 'athletes' and 'medals'.
6. Creating another lmplot to explore the relationship between 'age' and 'medals'.
7. Generating a histogram of the 'medals' column in the DataFrame.
8. Dropping rows with missing values from the DataFrame.
9. Splitting the data into training and testing sets based on the 'year' column.
10. Importing Linear Regression from scikit-learn and creating a Linear Regression model.
11. Defining predictors for the model.
12. Fitting the Linear Regression model on the training data.
13. Generating predictions using the trained model on the test data.
14. Adding the predicted values to the 'predictions' column in the test DataFrame.
15. Handling predicted values less than 0 by setting them to 0.
16. Calculating the mean absolute error between actual and predicted values using scikit-learn.
