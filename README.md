# India_import_export_analysis
In this project we analyse and create a dashboard on the India's commodity wise import export dataset available in data.gov.in

Link to the dataset:
https://data.gov.in/catalog/principal-commodity-wise-import
https://data.gov.in/catalog/principal-commodity-wise-export

Below are the steps taken in this project
1. Downloading the raw data in csv format
2. Upload the data into S3
3. Establish integration between S3 and snowflake
4. Load the raw data into tables in staging schema
5. Transform the denormlaized data into normalized form using star schema
6. Load the cleansed data into the tables in reporting schema.
7. Integrate snowflake with powerBI and import the tables
8. Build the report

Earlier: I loaded the export data into Amazon RDS and tried to import the table from RDS into Snowflake.
I have also added the python Jupyter notebook used to upload the data from S3 into RDS table
