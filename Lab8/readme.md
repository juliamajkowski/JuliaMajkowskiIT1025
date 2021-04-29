# Executive Summary
The purpose of this lab is to describe various database models and practice querying a database with SQL (structured query language). Additionally, recognizing key ethical and legal implications regarding information systems is reviewed.
## Data, Information, and Knowledge
### Relational Data
Data are raw facts which may be devoid of context or intent. Information is a form of fata which is processed giving it context, relevance, and purpose. Knowledge is beliefs or perceptions about relationships regarding information that facilitate action. 

When creating a database, there are several different factors that go into it. First, a primary key is needed, for example in a database for customer orders, the primary key might be customer names. The relation between the customer and the orders is through the connection of the specific customer and their specific order. The foreign key, or what connects the customer and order tables, might be an order number which is uniquely assigne dto each customer's order. In this scenario, the order table would likely have a date/time field. This is important because the data type tells the database what can be done with the data itself, and so that the proper amount of storage is saved in order to store the data. 
### Big Data
There are 4 V's that are important in big data. First, the volume or size of the data that is being considered. Second, the variety of data due to the number of possiblities such as emails, photos, or PDFs. Third, velocity or the speed of data generation and processed. Finally, variability or the inconsistency that can be shown by the data over time. All of these thing shave to be taken into consideration when creating storage for big data. The need for big data storage has grown over time due to things like the stock exchange and social media websites and it will continue to grow with their usage. 
## Structured Query Language 
RDBMS or relational database managment systems is the basis for SQL. All daya is stored in tables which is then broken up into smaller fields. This is related to SQL because SQL is is a language used for acessing and manipulating databases such as the RDBMS. 

In the lab diagram, two tables that are related are the customers and employees. The connection between them would be that each order is put together by a specific employee who has their own ID. The primary key for these would be employee ID and custoemr ID. The foreign key would be the order ID which is what connects the two tables. 
