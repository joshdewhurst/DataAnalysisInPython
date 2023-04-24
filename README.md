# DataAnalysisInPython

## Project: Analyzing Sales Data for an E-commerce Store

### Problem Statement:
A fictional e-commerce store has provided us with their sales data for the past year. The data includes information on sales revenue, products sold, customer demographics, and shipping information. Our task is to analyze the data and provide insights on the following questions:

1. What is the overall revenue for the year?
2. What were the top-selling products?
3. What was the average order value?
4. What is the customer demographics like?
5. What was the shipping cost distribution?
6. Can we identify any trends or patterns in the sales data?

### Libraries Used:
For this project, we will be using the following libraries:

- Pandas: for data manipulation and analysis
- NumPy: for numerical computing
- Matplotlib: for data visualization

### Functions:

#### Loading the Data:

We will start by loading the data into a Pandas DataFrame using the `read_csv()` function:

```python
import pandas as pd

# Load the data from a CSV file
sales_data = pd.read_csv("sales_data.csv")
