# Building an ETL pipeline using SSIS
ETL Project Using ITI Database and Test Database



## First Package
Designing Package to transfer Department data From [ITI DB] to [Test Db]. 

## Second Package 
Designing Package to transfer Student data (St_id, St_Fname, St_lname, St_address) From [ITI DB] to new Delimited file “Student.txt”.

## Third Package
Designing Package to transfer Student data from [ITI DB] to [Test DB] with the following Criteria:
-	Merging the first name and last name to be one field [Full name].
-	Making a ful backup for [Test DB]
-	On error  displaying message box “error occurred”

## Fourth Package
-	Selecting Course data with topic name From ITI DB
-	Sort Course data by Crs_name Descending. 
-	Crs_name should appear in lower case. 
-	Split Course data into 3 files:
i.	File1.txt contains Course data with Course Duration<30 hours.
ii.	File2.txt contains Course data with Course Duration=30 hours.
iii.	File3.txt contains Course data with Course Duration>30 hours.

## Fifth Package
Merging file1.txt and file2.txt to be one file using Union and Merge component

