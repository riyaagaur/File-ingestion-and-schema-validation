###File ingestion and schema validation

Take any csv/text file of 2+ GB of your choice. 

Try different methods of file reading eg: Dask, Modin, Ray, pandas and present your findings in term of computational efficiency

Perform basic validation on data columns : eg: remove special character , white spaces from the col name

Create a YAML file and write the column name in YAML file. 

Validate number of columns and column name of ingested file with YAML.

Write the file in pipe separated text file (|) in gz format.

Create a summary of the file:

Total number of rows,

total number of columns

file size
