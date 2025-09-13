# SSIS_ETL_Pipeline
This is an ETL project in SSIS.
It takes CSV files from a folder, adds extra columns, creates new values, and then loads everything into a new folder.

What’s inside:
Flat File Source → reads data from CSVs
Lookup/Joins → adds extra info to the data
Derived Columns → creates new column values
OLE DB Destination → saves data into the database
Error Output → keeps track of invalid rows
