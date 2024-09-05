# EDA on Sales Data using Python

In this project, I utilized Python Pandas and Matplotlib to analyze and answer key business questions based on 12 months of sales data from an electronics store. The dataset, comprising hundreds of thousands of purchases, is broken down by month, product type, cost, purchase address, and more.

## Data Cleaning

The project begins with data cleaning, where I:

* Dropped NaN values from the DataFrame.
* Removed rows based on specific conditions.
* Changed column data types using ```to_numeric```, ```to_datetime```, and ```astype```.


## Data Exploration
Following data cleaning, I explored five high-level business questions:

* Best Month for Sales: Identified the most profitable month and the total earnings.
* Top-Selling City: Determined which city had the highest product sales.
* Optimal Advertisement Timing: Analyzed the best times to display ads for maximum customer purchases.
* Frequently Sold Products Together: Examined which products are commonly purchased together.
* Top-Selling Product: Identified the most sold product and explored reasons for its popularity.

## Key Techniques and Methods

To answer these questions, I employed various Pandas and Matplotlib methods, including:

* Concatenating multiple CSV files into a single DataFrame ```(pd.concat)```.
* Adding new columns.
* Parsing cells as strings to create new columns ```(.str)```.
* Using the ```.apply()``` method for data transformation.
* Performing aggregate analysis with ```groupby```.
* Visualizing results with bar charts and line graphs.
* Labeling graphs for clear interpretation.
