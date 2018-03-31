Project Name: Database Management System (DBMS)


Original code: Please refer to the folders above for the "unimplemented" code. Due to the agreement with the Professor, the implemented code is not public and may be provided upon request. (Please see the bottom of the file for more details.)


Project Description: The project is divided into four parts. Each part is described below:


Part 1: Implement a paged file system and operations of records (in the API data format)

Involved classes in this part: PagedFileManager, FileHandle, RecordBasedFileManager

Key functions implemented by me: insertRecord (insert a record in the heap file),  printRecord (print out a record in the specified format)

Project Report: Please refer to "Project1 Report.pdf", which elaborates on our DBMS's design of Internal Record Format and Data Page Format.

Please refer to the following link for more details:

https://grape.ics.uci.edu/wiki/public/wiki/cs222p-2017-fall-project1-description


Part 2: Implement operations of tables and tuples

Involved classes in this part: RelationManager, RM_ScanIterator 

Key functions implemented by me: updateRecord (update a record in the heap file), readAttribute (read a specific attribute of a tuple)

Project Report: Please refer to "Project2 Report.pdf", which elaborates on our DBMS's design of Catalogue and Heap File Format.

Please refer to the following link for more details:

https://grape.ics.uci.edu/wiki/public/wiki/cs222p-2017-fall-project2-description


Part 3: Implement operations of B+ tree indexes

Involved classes in this part: IndexManager, IX_ScanIterator, IXFileHandle  

Key functions implemented by me: insertEntry (insert an index entry in the index file), printBtree  (print the B+ tree in the JSON format)

Project Report: Please refer to "Project3 Report.pdf", which elaborates on our DBMS's design of Index Entry Format, Index Page Format, and Index File Format.

Please refer to the following link for more details:

https://grape.ics.uci.edu/wiki/public/wiki/cs222p-2017-fall-project3


Part 4: Implement relational operators

Involved classes in this part: RM_IndexScanIterator, Iterator, Filter, Project, BNLJoin, INLJoin, Aggregate 

Key functions implemented by me: BNLJoin (join two tables using Block Nested-Loop Join), Aggregate (calculate MIN, MAX, SUM, AVG, and COUNT of a field)

Project Report: Please refer to "Project4 Report.pdf", which elaborates on the implementation details of each relational operator.

Please refer to the following link for more details:

https://grape.ics.uci.edu/wiki/public/wiki/cs222p-2017-fall-project4


Supplemental Information:

- The project was developed in the "test-driven" method, that is, each part had to pass through a bunch of tests designed by the TA to be considered successful.

- Although the project defined the functions we needed to implement, the design of our DBMS was determined by ourselves.

- The project was co-worked with my teammate, Chun-Kai (Kyle) Chan. "It takes teamwork to make dream work." Without his help the huge project would not have been completed as scheduled. Below is his LinkedIn page:
https://www.linkedin.com/in/chunkai-chan/


How to compile and run in Linux:
Download the files into a folder.
In the terminal, change the directory to that folder (should include makefile).
Type "make" to compile the code.
And then type “./<test_name>” (e.g., “./rbftest1”) to run the test.
Since the code in this repository is "unimplemented", you should see an error message such as "Creating the file failed."
If you have a valid reason to view the implemented code (e.g., you are a recruiter or an interviewer), please contact me at yidarl@uci.edu.
Thank you!

Please refer to the following link for more details:

https://grape.ics.uci.edu/wiki/public/wiki/cs222p-2017-fall-project1-create-project
