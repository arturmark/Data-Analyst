# Data-Analyst
Python script


"Data Analyst" is a light and very fast Python script to analyse online available datasets from url address directly form clipboard memory.

It has three main task:

    It performs standard analysis for any data in csv format, for example: number of rows, columns, missing values, data types, column names, delimiter, size of the file, downloading time, web domain even first row values etc...

    Evary single analysis is stored in database SQLite3 created automacically if not exists. Then it starts to append rows with new, when same dataset has changed its structure or update existing with faster downloading time, if it has happened. It will also keep original index value, which can be used always for reference to other projects.

    Each time output from analysed data is saved in text file available for quick reference used for example in further analysis. Python script does it usually in less then second, but it is still very handy to have that.

The general idea is to have ability to get quick essential analysis of the file with data and to have a database of datasets, where it can be search later for link to the data with speciffic attributes like with many rows, including speciffic data types, has no missing values and includes column names like latidude, to use for map charts.
