# bdm-notebook-demo
## Combining data from multiple locations
In this tutorial, we'll demonstrate how you can use Oracle Big Data Manager Notebook to work with **data stored in multiple locations** such as the edges.csv file on `hdfs` and the USERS Oracle database table. 

### About the data
_Disclaimer: This dataset is completely artificial. It has been generated programmatically based on some arbitrary input_

The `USERS` table contains records about each Student name, id, and class category. A value of class_0 in the 'category' column indicates that the student is attending class 0 whereas a value of class_1 indicates that the sudent is attending class 1.  

The `edges.csv` file contains many rows (records). Each row contains two columns. Each column represents a student id. The two student ids represent two students who are collaborating on a specific class project. 

We use the `USERS` Oracle database table to lookup the names of the student ids and which classes they attended: class_0 or class_1. 

We'll use this dataset to get an idea how frequent such cross-class collaborations are. 
