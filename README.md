# Data-Transformation-in-Excel-1
This data transformation briefly works through a process of loading excel formats directly from a folder. each folder contains same information with equal of number columns. The idea is to create an ETL process that loads data from a folder, transforms it and append them together into a consolidated table. 

#### Excel file folder showing sales information for different sales person in different region. Additionally a random file of different file format

![](folder_look.png)

#### The file contains sales information of different sales person
![](actual_look.png)

#### Loaded view of folder and the different file formats available
![](file_formats.png)

#### Filtered view showing only needed xls formats
![](xls_format.png)

#### After keeping only xls format files, other unwanted columns are removed. Additionally a new custom column is created using the M code: Excel.workbook([content]) which returns the data in the content column
![](m_code_function.png)

####
