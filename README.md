--------------------------------------------------Readme-----------------------------------------------------------
Data encoding in machine learning refers to the process of converting raw data into a format that a machine learning 
algorithm can understand and process. Machine learning models work with numbers, so we need to transform data into
numerical form if it isn’t already.
Overview of One-Hot Encoding
One-Hot Encoding is a technique used to convert categorical (non-numerical) data into a numerical format so it can be used in machine learning models.
 It transforms each unique category value into a binary vector where:
Each category is represented as a column.
The value is 1 in the column corresponding to the category and 0 in all other columns
Disadvantages of One-Hot Encoding
High Dimensionality:
If there are many unique categories, the number of columns increases significantly (e.g., 100 categories = 100 new columns).
Sparse Data:
For large datasets, one-hot encoding creates many zeros, increasing memory usage.
