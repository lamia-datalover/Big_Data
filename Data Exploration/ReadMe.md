# The goal of this project 
This PySpark script is designed to handle and analyze a JSON file containing song data from YouTube, stored in an S3 bucket. 
The code performs several operations to explore the structure and contents of the DataFrame created from the JSON file, 
and includes transformations to gain insights into the data.<br>
The script reads a JSON file into a PySpark DataFrame, explores its structure and specific columns, and 
performs various DataFrame operations to understand and analyze the data. It examines the relationship
between the 'pageInfo' and 'items' columns to validate the consistency of the data.<br>
This detailed process helps validate data integrity, provides a clear view of the dataset's structure, 
and allows for deeper analysis of the contents, particularly focusing on the consistency 
between reported totals and actual counts.<br>
