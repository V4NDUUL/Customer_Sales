# Customer_Sales

Customer
Bill Date
Part #
Bill Qty
Cost
Price
Data Exploration
The first step is to load the data and perform some initial exploration. We read the data into a pandas DataFrame and display the first few rows to get an idea of the structure of the dataset.

import pandas as pd

# Load the data from Excel
df = pd.read_excel

# Display the first few rows of the data
print(df.head())


# Load the data from Excel
df = pd.read_excel

# Display the first few rows of the data
print(df.head())
Data Preprocessing
In this section, we perform various preprocessing steps to prepare the data for analysis and customer segmentation. The steps include:

Filtering the data based on a specific criterion (e.g., specific Part # containing ':DF')
Separating the 'Customer' column into individual locations
Creating separate DataFrames for each customer type (location)
Adding suffixes to each DataFrame to distinguish columns from different locations
Customer Segmentation
Once the data is preprocessed, we perform customer segmentation based on the different locations. 


For each location, a separate DataFrame is created, and the suffixes are added to the columns to differentiate between locations.

Merging DataFrames
After customer segmentation, the individual DataFrames are merged into a single DataFrame called merged_data.

Exporting Results
Finally, the results of the customer segmentation are exported to an Excel file named Final_Output.xlsx.

Feel free to explore the Jupyter Notebook for a more detailed analysis and explanation of each step.

Contributing
If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. Your contributions are highly appreciated.
