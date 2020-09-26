# Query-Database
The Query Database contains the accession keys along with the corresponding information of 482 attributes for each of the 13,489 stool samples from American Gut Project.

# SYSTEM REQUIREMENTS
To run the Query-Database and its supporting python scripts requires:

* A modern Linux operating system.
* Python3 or greater.

# INSTALLATION

The Query-Database is hosted on GitHub

The Query-Database source code and executables can be obtained via two different methods:

Either clone the repository using git:

`git clone https://github.com/Unsaif/Query-Database`

Or download and extract the zip file using the 'Download ZIP' link of the GitHub project page.

No further installation is necessary. The program can be run from within the cloned repository or from the location that the zip was extracted to.

This document will assume that the Query-Database is located in your home directory in a folder named `/home/your_username/Query-Database`. This location will be referred to from hereon in as 'QUERYDIR'.
If you have placed Query-Database in a different location, use that path in place of 'QUERYDIR'.

# RUNNING THE QUERY-DATABASE

To run the Query-Database, execute command:

`QUERYDIR/query`

If running from within the Query-Database directory:

`./query`

# OUTPUT

The QIIME Pipeline writes output in a plain text format with tab separated columns (.tsv). The output of the Query-Database will appear in the Query-Database directory and will, optionally, contain 0-3 accession files which can be named at the user's discretion:

* The accession file of the test group
    
* The accession file of the control group
    
* The combined accession file of the test and control group
