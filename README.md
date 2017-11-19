 # rankwatch17_py_scraping
## **Assignment**:
There are two directories named: raw and processed . Raw directory contains files with
random names and extension csv. Each CSV (Comma-Separated value) file has date in its
first column. Write a python script to observe raw directory for any CSV file. This script
will parse it, and push every row into another file with “yyyy-mm-dd-processed.csv”
format where the date format is for the date in first column. For Example:
2017-09-28-processed.csv will be in processed folder and contains all entries with for the
same date.

## **Prerequisite:**
* Python should be installed
* Install pip and psutil(Cross-platform lib for process and system monitoring in Python) 
* To install pip, securely download get-pip.py 
* Then run the following: "python get-pip.py"

### Import these libraries

``` 
import os
import csv
```

### Built with
Used Notepad++ for writing the script.
