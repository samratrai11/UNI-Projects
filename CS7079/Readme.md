Data Warehousing and Big Data 
The aim of this coursework is to design, implement, and test a data warehouse based on a given business case scenario, to export data from it and ingest it for further processing on a Big Data platform. It is individual coursework. 


Coursework Specification: 
CASE STUDY SCENARIO: ABC Consumer Electronics Outlet Ltd. 
ABC Consumer electronics Outlet Ltd is a multi-channel retailer of consumer electronics, which was founded in 1986. It operates from six stores located in and around London. It also conducts online business across UK and Europe. Currently, the company offers more than ten thousand products organised in about ten categories and in more than 200 brands. These figures are a snap shot at a time. The number of products varies continuously as new product lines are introduced and old products are discontinued. 
Consumer electronics retail industry is very dynamic and competitive. Retailers are always under huge pressure to invest in new information and communication technologies to gain competitive advantages and optimise business processes. 
ABC Consumer Electronics Outlet Ltd has already invested in information and communication technologies to support its business processes. The company is using a cloud based software called Vend to support many of its retail activities. It is also using Linnworks to automate its online business and Xerox to support its finance department. These software applications are generating a huge transactional data every day. The generated datasets are stored and managed separately by each software application. 
Managers at ABC Consumer electronics Retail Company are struggling to produce reports and perform analysis that would enable them to provide information for their decision-making activities. That is why a business analyst recommended to the company to design and implement a data warehouse that will meet all reporting and analysis requirements. 

The business analyst team has conducted business requirements gathering and produced a business requirements document. The description, reporting and analysis requirements of only one business area are presented below. The data warehousing solution will focus only on inventory management business process. 


Inventory Management: 
Inventory management is one of the most important business processes of a company. Its main goal is to produce a good purchase order plan to ensure that product items are available when they are needed. Currently, the company is facing problems in controlling over-stocks and under-stocks of product items. Reducing over-stocks and under-stocks will have a big role in increasing revenue and customer satisfaction. 

There are three main business activities: 
1.	Sending purchase orders to suppliers when there are product items with minimum levels of inventory. For each sent purchase order, the ordered quantity, sent date, product and supplier details are recorded. 
2.	Receiving purchase orders and storing stocks in appropriate locations. For each received purchase order, the ordered quantity, received quantity, received date, product and supplier details are recorded. 
3.	Controlling and maintaining stocks which involves adding new products and adjusting stock levels of existing products. The details of each product are recorded including the current stock level. 

Managers responsible for managing inventory are demanding to meet the following reporting and analysis requirements: 
•	A daily stock levels of all products for the last month. 
•	A weekly report of all products with minimum stock levels. 
•	Analysing stock levels by brand or product type or supplier 
•	Daily and weekly sent and received stock orders for the last four weeks. 
•	Analysing received stock orders by supplier and by month. 

Description of Data Sources: 
As mentioned in the above, ABC Consumer Electronics Outlet Ltd depends on various software applications such as Vend, Linnworks, and Xerox to support its daily business activities. For this coursework, only data source from Vend is considered. The data source includes supplier details, product details and details about stock movements from suppliers to warehouse location. A sample of data will be provided either as flat files or relational tables. It is part of your task to understand the structure of suppliers, products, and stock movements. 
 

PART A – Group Work:
1. Analysis & Design of Dimensional Data Model 
1.1 Identify and define the grain (detail level) of three different central fact tables to represent the three main business activities of the inventory management business area. 
1.2 Identify dimensions of each central fact table based on the available data source that will meet the reporting and analysis requirements mentioned in the business case scenario. 
1.3 Identify attributes of dimensions and measures of fact tables based on the available data source descriptions that will meet the reporting and analysis requirements mentioned in the business case scenario. . 
1.4 Use simple star schema to define the structure that shows how the fact tables are related to their dimensions. Create a graphical representation of the four simple star schemas in one page. 

PART B – Individual Work: Continues on Part A; the final report has to include Part A and Part B together. 

2. Create a Relational Database to store dimensions and fact tables using Microsoft SQL Server Management Studio. 
2.1 Create a database.
2.2 Create dimension tables
2.3 Create fact tables.
2.4 Add appropriate primary keys and foreign keys constraints. 

3. Migrate test data from the data warehouse to an Apache Hadoop platform for further analysis of Big Data using Hortonworks Data Platform (HDP) 
3.1 Populate the data warehouse database with some test data.
3.2 Export the data warehouse database data into an external data file. 
3.3 Migrate the data file from the file system to Apache HDFS. 
3.4 Create a suitable data structure for loading the data file into HIVE 
3.5 Demonstrate the use of Apache Pig for manipulating the loaded data 

4. Written Report 
The report, which you will submit, should be well written, structured and well- presented and it must include: 
•	An introduction section that summarise the objectives of the course work and business case scenario.  
•	The Analysis and design of a dimension data model.
•	The implementation and testing of the data warehouse (include screen shots 
to show SQL commands and their results).
•	The implementation and testing of the BigData storage on HDFS (including 
the Pig commands and their results). 
•	Provide a personal reflective conclusion of what you have learnt from your 
overall coursework. 


