# TSA
QB64 Time Series Analysis

TSA is a menu-driven app that enables analysis of multiple columns of time series data.

TSA is programmed to read a standard CSV (comma separated values) file that may have been created in Microsoft EXCEL, Google SHEETS, or a text editor and saved in CSV format as a UNICODE TEXT DOCUMENT with file type specified as .DAT, e.g., filename.DAT.

TSA is dimensioned for a maximum of 20 columns and 1200 rows of data. In a file readable by TSA, column headings are separated by commas in the first row and data are separated by commas in subsequent rows:
    ROW 1:              HEADER1,HEADER2,HEADER3
    ROW 2:              1000.0,2000.0,3000.0
    ROW 3:              4000.0,5000.0,6000.0
                                 .
                                 .
    ROW LAST:           9799.9,9899.9,9999.9
The number of columns in a filename.DAT file is determined by the number of comma-separated headings in the first row. TSA will discover the number of subsequent data rows (up to 1000) in the data file.
