# Sales-Analysis

### The data analysis process begins with data cleaning, involving tasks such as:

1. Removing NaN values from the DataFrame.
2. Filtering rows based on specific conditions.
3. Adjusting column types using methods like `to_numeric`, `to_datetime`, and `astype`.

### Upon completing the data cleaning phase, we transition to data exploration, addressing five central business questions:

1. Determining the most profitable month and quantifying the revenue generated during that period.
2. Identifying the city with the highest volume of product sales.
3. Determining the optimal time for displaying advertisements to maximize customer purchases.
4. Investigating products frequently sold together.
5. Analyzing the best-selling product and exploring factors contributing to its success.

### To answer these questions, diverse pandas and matplotlib methods are employed, such as:

- Concatenating multiple CSV files using `pd.concat`.
- Adding columns to augment the dataset.
- Parsing cell values as strings to generate new columns (using `.str` methods).
- Applying the `.apply()` method for custom operations.
- Using `groupby` to perform aggregate analysis.
- Visualizing results through bar charts and line graphs.
- Implementing proper labeling and annotations on graphs.

These techniques ensure not only data integrity but also offer valuable insights into the sales performance and trends within the electronics store dataset.
