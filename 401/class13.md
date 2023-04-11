# Linear Regression

## Reading

### [How to Run Linear Regression in Python](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)

## Additional Resources
### [Linear Regression in Python](https://realpython.com/linear-regression-in-python/)

## Videos
### [Introduction to Simple Linear Regressions](https://www.youtube.com/watch?v=KsVBBJRb9TE)

## Bookmark and Review
### [https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6](Train & Test)
### [What is Linear Regression](https://www.statisticssolutions.com/what-is-linear-regression/)

## Reading Questions
1. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?
   - It is used to establish a relationship between the independent and dependent variables. Linear regression a good place to start for data analysis and machine learning becuase it provides a simple visualization for data.
2. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.
    - import .csv file using pd.read_csv()
    - isolate desired X, and y values using some type of df.loc statement
    - use np.reshape() to reshape X array for use by train_test_split
    - use train_test_split to get train and test data
    - use LinearRegression.fit and lr.predict to train and create linear equation for best fit line
    - plot the graph using pyplot
3. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?
   - to allow for comparison to actual data