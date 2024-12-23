# Homework 1 : Data Exploration

## Obejctive
The objective of this exercise is to perform data exploration using Pandas and to calculate various statistical measures for a real dataset. By the end of the exercise, you should be able to:
Load a dataset into a Pandas DataFrame
Explore the structure and format of the data
Calculate measures of central tendency, variability, and shape
Perform basic data cleaning and preprocessing
Dataset

For this exercise, we will be using the "Iris" dataset, which contains information about three species of iris flowers. The dataset is available in the "sklearn" library in Python.
To load the dataset, you will need to install the "sklearn" library and import the dataset using the following code:
------------------------------------------------------------------------------------------------from sklearn.datasets import load_iris 
 data = load_iris() 
df = pd.DataFrame(data["data"], columns=data["feature_names"])
df["target"] = data["target"] 
df["target"] = df["target"].map({0: "setosa", 1: "versicolor", 2: "virginica"}) 
------------------------


## Instructions
Load the "Iris" dataset into a Pandas DataFrame using the code provided above.
Display the first 5 rows of the DataFrame using the "head()" method.
Check the shape of the DataFrame using the "shape" attribute.
Check the data types of each column using the "dtypes" attribute.
Check for missing values in the DataFrame using the "isnull()" method and the "sum()" method.
Calculate the mean, median, and mode for the "sepal length (cm)" column.
Calculate the range, variance, and standard deviation for the "petal width (cm)" column.
Calculate the skewness and kurtosis for the "sepal width (cm)" column.
Count the number of unique values in the "target" column using the "nunique()" method.
Group the data by the "target" column and calculate the mean for each group using the "groupby()" method and the "mean()" method.
