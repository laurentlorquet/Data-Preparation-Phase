# Data-Preparation-Phase
Load a dataset, explore and prepare it by cleaning, transforming, and visualizing the data.


## DATA PREPARATION PHASE
Select a dataset from UCI Machine Learning Repository ( https://archive.ics.uci.edu/datasets)
Perform the following tasks in a Jupyter notebook:
1. Load the CSV file and display its shape (use .shape).
2. Print the header and the last few rows (use .head() and .tail()).
3. Print a summary of the dataset's statistical details (use .describe()).
4. Display a concise summary of the dataframe (use .info()).
5. Add an index column and display its new shape.
6. Choose a numerical field and print its unique values.
7. Replace an extreme set of values in the dataset with zero, -1, or np.NaN.
8. Plot a histogram of a numerical variable.
9. Choose a categorical field and represent it as a numerical field (create a new column), then 
display the last few rows (use .tail()).
10. Use the zscore function to standardize a numerical field (create a new column), then show its 
histogram.
11. Identify a field and use a criterion of your choosing to filter for outliers. Create a new dataset 
with the outliers and display the first few rows (use .head()).
12. Sort the dataset and display 15 interesting fields.
