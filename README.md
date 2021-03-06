# Data-Analyst
Python script to analyse online data files and saving them after in SQLite3 database.


"Data Analyst" is a lightweight and very fast Python script to analyse available online datasets from url address directly form clipboard memory.

It has three main task:

- It performs standard analysis for any data in csv format, for example: number of rows, columns, missing values, data types, column names, delimiter, size of the file, downloading time, web domain even first row values etc...

- Evary single analysis is stored in database SQLite3 created automacically if not exists. Then it starts to append rows with new or when same dataset has changed its structure or update existing with faster downloading time, if it has happened. It will also keep original index value, which can be used always for reference to other projects.

- Each time output from analysed data is saved in text file available for quick reference used for example in further analysis. Python script does it usually in less then second, but it is still very handy to have that.

The general idea is to have ability to get quick essential analysis of the file with data and to have a database of datasets, where it can be search later for link to the data with speciffic attributes like with many rows, including speciffic data types, has no missing values and includes column names like latidude, to use for map charts.

*Column names:

['id', 'timestamp', 'domain', 'source', 'file_type', 'size_mb', 't_load_sec', 't_calc_sec', 't_code_sec', 'parameter', 'prmtr_val', 'dt_obj', 'dt_int', 'dt_float', 'row_', 'col_', 'na', 'source_address', 'column_list', 'first_row', 'comment']

![Python output part 1.PNG](https://github.com/arturmark/Data-Analyst/blob/master/Python%20output%20part%201.PNG)

![SQLite3](https://github.com/arturmark/Data-Analyst/blob/master/SQLite3-database%20structure.PNG)

![SQLite3](https://github.com/arturmark/Data-Analyst/blob/master/SQLite3-sample%20values.PNG)

![VS Code](https://github.com/arturmark/Data-Analyst/blob/master/Working%20environment_.png)




