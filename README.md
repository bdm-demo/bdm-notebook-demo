# bdm-notebook-demo
## Combining data from multiple locations
In this demo we'll show how BDM Notebook can be used for working with **data stored in multiple locations** - in this case on `hdfs` and in `MySQL` database.

### About the data
_Disclaimer: This dataset is completely artificial, it has been generated programatically based on arbitrary input_

The `USERS` table contains records about a students's name, his/her id and a label called category. Value in the 'category' column dependens on which one of 2 classes he/she attends. The `edges.csv` file on the other hand contains records about user connections - each row contains 2 student ids of the students coworking on a project.

Students are allowed to find a colleague for their project not just in the same class they attend, but also in the other class. We'll use this dataset to get an idea about how frequent such cross-class colaborations are.
