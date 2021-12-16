# citrus-shop-modeling

## What's it?

That's modeling of web-site citrus.ua (you can join this site by link in repo description) 

## Purpose 

This project was created as a homework at Plovdiv University

## Structure 

```
├── database-modeling                    
│   ├── conceptual_model.drawio         
│   ├── datawarehouse_model.drawio         
│   ├── logical_model.drawio               
│   └── physical_model.drawio
│
└──transact-sql-database
    ├── TablesDefinition.sql   
    ├── TriggersFunctionsProcedures.sql 
    └── power_bi.pbix   
```

### database-modeling 

Folder which contains all database models which are implemented by draw.io, and represent database,I'm going to show you later . Here you can install it to open diagrams on your machine https://github.com/jgraph/drawio-desktop/releases/

#### conceptual_model.drawio

A conceptual model is a representation of a system. It consists of concepts used to help people know, understand, or simulate a subject the model represents. The main goal is to represent the life cycle of the app. 

<img width="1060" alt="Screen Shot 2021-12-17 at 0 11 22" src="https://user-images.githubusercontent.com/77781886/146456398-652f8b74-8da2-42c7-973e-f20fbfd7c1b0.png">

#### datawarehouse_model.drawio

Data warehouse modeling is the process of designing the schemas of the detailed and summarized information of the data warehouse. The goal of data warehouse modeling is to develop a schema describing the reality, or at least a part of the fact, which the data warehouse is needed to support.

#### logical_model.drawio 

Logical model's goal is to define how a system has to be implemented and is not specific to a database

#### physical_model.drawio

Physical models represent how the system will be implemented to a specific database management system, so these models are designed for business purposes.


### transact-sql-database

In this folder we will store query for  **T-SQL** database,  which is going to be representation of citrus.ua database 

#### TablesDefinition.sql

Here we have query for creating database tables

#### TriggersFunctionsProcedures.sql 

Here we have query for creating triggers, functions and procedures, for database, you could create with query in **transact-sql-database/TablesDefinition.sql** 

#### power_bi.pbix

Here we have PowerBI file.For starting it up,you should install it here https://www.microsoft.com/en-us/download/details.aspx?id=58494 

The file contains 3 diagrams :

- Stacked column chart diagram (KIDS_QUANTITY by FIRST_NAME)
- Round diagram (PRICE_WITHOUT_SALE by FIRST_NAME)
- Map diagram (COUNTRY by FIRST_NAME)
