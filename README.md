# big-data-challenge
Instructions

Level 1


Use the provided schema to create tables in your RDS database.


Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset. Put each dataset into its own notebook.
Note: You could ETL both data sources in a single Colab notebook, but it will be easier to work with these large S3 data sources in separate notebooks.


Be sure to handle the header correctly. If you read the file without the header parameter, you may find that the column headers are included in the table rows.


Complete the following steps for each notebook (one dataset per notebook).


Count the number of records (rows) in the dataset.


Transform the dataset to fit the tables in the schema file. Be sure that the DataFrames match in data type and in column name.


Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Ensure that everything is correct before uploading.
