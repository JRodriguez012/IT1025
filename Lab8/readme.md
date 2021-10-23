## Javi Rodriguez / October 21, 2021

## Executive Summary 
Lab 8 explores data, how data is stored, how data can be accessed and modified with SQL, and the ethics of collecting data. There are distinctions between the terms data, information, and knowledge. We store data in relational databases which are tables of related data points. To access or modify these data points, we can use Structured Query Language (SQL). Lastly, we explore the ethical and legal concerns over collecting data. Legislative acts like COPPA, FERPA, and HIPAA place legal restrictions on the type of data that can be collected and shared.

## Data, Information and Knowledge
### Compare and contrast data, information and knowledge
Data are the raw facts that often do not have context. Data can be quantitative, a value that can be measured, or qualitative, a description. Information is processed data that has context, relevance, and purpose. Information typically manipulates data to see trends in patterns in the data. Knowledge is a perception about the relationships among relevant facts. Knowledge is information that facilitates action.

### Relational Data
#### Primary Key: The primary key for the customers table would be a customer ID. The primary key for the orders table would be an order number.
#### Relationship between customers and orders: The customers and orders tables would be related by a common customerID field because orders have to be purchased by a customer.
#### Foreign key of orders table: The foreign key for the orders table is the customerID field as it connects to the primary key of the customers table.
### Field Data Types
It is important to properly define the data type of a field so that we can properly and efficiently process the data. A data type tells the database what functions can be performed with the data. For example, mathematical functions can only be performed on number data types. Another reason to define the data type is so that the proper amount of storage space is allocated for the data.

### Big Data
#### Four "V"s of Big Data
The four "V"s of big data are volume, variety, velocity, variability. Volume is related to the enormous size of big data. Variety refers to heterogeneous sources of both structured and unstructured data. Data can be in the form of spreadsheets, audio, pictures, videos, etc. Velocity refers to the speed at which data is generated and processed. Variability is the inconsistency which is shown by data, hampering the process of managing data effectively.
#### Technology Driving the need for Big Data
Technology such as search engines and social media platforms have significantly increased the need for big data. These technologies process hundreds of terabytes of data every day that includes text, photos, videos, audio, etc.

## Structured Query Language (SQL) 
### RDBMS and SQL
Relational Database Management System (RDBMS) is the basis for SQL. RDBMS uses database objects called tables to store data. A table is a collection of related data entries that is broken up into smaller entries called fields. Structured Query Language (SQL) is a standard language that is used to retrieve data from and manipulate data in relational databases. SQL is the language used to access and interact with RDBMS.
### Relationship, Primary and Foreign Keys

## SQL Injections
SQL injections are a security threat because they can be used to access data inside or destroy your database. SQL injections use web page inputs to place malicious code in SQL statements. To reduce threats from SQL injections, use SQL parameters. SQL parameters are values that are added to an SQL query at execution time, in a controlled manner. SQL parameters are checked by the SQL engine to ensure they are treated literally, not as part of SQL to be executed.
## Ethical and Legal Implications
### Code of Ethics
A code of ethics establishes guidelines for what is considered acceptable behavior among a professional or social group. The Association for Computing Machinery (ACM) created a code of ethics to identify common issues among and provide ethical instructions for computing professionals.
### Intellectual Property
A trademark is a word, phrase, logo, shape, or sound that identifies a source of goods or services. Trademarks are intended to protect intellectual property and protect consumers from being deceived by someone disguised as a more well known company. My svg image was automatically copyrighted when I created it, but it would be important to register for a copyright if I intend to use my svg image for commercial purposes. A registered copyright is needed to take legal action against someone who used the copyrighted work without permission.
### Information Collection
The Children's Online Privacy Protection Act (COPPA) restricts websites from collection information from children under the age of thirteen without parental consent. These websites must also make a good faith effort to determine the age of someone using the website. The Family Educational Rights and Privacy Act (FERPA) protects the privacy of student education records. This law specifies that parents have a right to their child's educational until that child reaches the age of eighteen or attends school beyond the high school level. Educational institutions that collect student information are at risk of improperly disclosing that information because of digital technologies. The Health Insurance Portability and Accountability Act (HIPAA) gives patients the right to control their medical records and requires health care providers who maintain this information to receive permission to share these records. Now that this information is shared electronically, it is extremely important to protect these systems.
## Conclusion
The use of data in computing is exponentially expanding. It is important to be able to understand databases and how to work with them to store, access, and manipulate data. The most interesting part of this lab to me was learning and working with SQL. I have heard of SQL many times before but never knew exactly what it was used for. I am looking forward to using SQL in future projects.
