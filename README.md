# Business-Intelligence-Data-Warehousing
In this repository, I share an End-to-End BI &amp; DW project done during my studies at IE University:

The dataset is an event log that describes the process of how an incident within the ServiceNow Solution for Incident Management System is reported, processed and managed within an IT company. The data is collected from an audit system for one instance of the ServiceNow platform for Year 2016 (https://www.servicenow.com/products/incident-management.html).

When an incident happens, the IT company needs to correct failures as soon as possible to minimize the impact on normal business operations.

The business objective is to help the IT company reduce the completion time for incident resolution (Ticket Completion Time). The analytic method investigates into the repetitive incident categories, resolution steps, and task overload during the processes.

## 1. Data Warehouse Modeling
The goal here is to  present a design of a data warehouse/data mart for an IT Operations Log System. The main executed task were: 

**A. Dataset analysis:**
- Analyze the dataset: Review the fields of the dataset and its definition, understand the meaning of all of them and define user requirements considering the context of the dataset. 
- Detect potential data quality issues such as: missing values, incomplete values, errors. Make a decision for each one of these data quality issues. 
- Detect duplicates. 

**B. Data Warehouse approach selection:**
Select between using a corporate information, multidimensional approach or data vault approach.

**C. Data Warehouse design:**
Identify the entities based on the selected approach (fact tables, dimension tables, and metrics). Implement the design with MySQL Workbench as we did during the sessions.

**Tools used:**
- Database: MySQL
- Database Modeling: MySQL Workbench

![DW Star Schema](/1_Data_Warehouse_Modeling/DW_Schema.jpg)
