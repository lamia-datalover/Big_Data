# Goal of the mini-project :
The code outlines a data processing workflow using PySpark to handle a dataset from an AWS S3 bucket. 
# Steps of this project :
<b>Load Data from S3:</b><br>
- Import necessary functions from PySpark.<br>
- Define the file path to the dataset stored in an S3 bucket.<br>
- Load the CSV file into a PySpark DataFrame with headers and schema inferred from the data.<br>
<br>
<b>Initial Data Exploration:</b><br>
- Display the first five rows of the DataFrame to get a quick look at the data.<br>
- Print the schema of the DataFrame to understand the data types of each column.<br>
- Generate descriptive statistics for the DataFrame and convert it to a pandas DataFrame for better readability.<br>
<br>
<b>Missing Values Analysis:</b><br>
- Using pandas, create a DataFrame that counts missing values for each column in the playlog.<br>
<br>
<b>Duplicate Records Handling:</b><br>
- Check if the count of rows in the DataFrame equals the count of rows after removing duplicates to detect any duplicates.<br>
- Calculate the number of duplicate rows.<br>
<br>
<b>Data Ordering and Cleaning:</b><br>
- Order the DataFrame by the timestamp column in ascending order and display the first five rows.<br>
- Count the number of rows with a negative timestamp, which are considered problematic.<br>
- Collect rows with negative timestamps for further analysis (potentially to investigate issues).<br>
<br>
<b>Final Row Count of Cleaned Data:</b><br>

Calculate and display the count of rows in the cleaned DataFrame to confirm the removal of unwanted records.<br>
<br>
This workflow provides a robust approach to data loading, exploration, and cleaning, crucial for preparing the data for further analysis or machine learning tasks.
