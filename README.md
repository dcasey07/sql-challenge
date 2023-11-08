# SQL Challenge: Module 9

## Objective

The goal for this challenge was to use PostgreSQL to demonstrate data modeling, data engineering, and data analysis by creating a database using the starter .csv files of employees, department information, and salaries.

### Data Modeling
This project required using an ERD to plot out a coherent schema that properly ties together the various tables using proper primary and foreign keys, for which attributions can be found below.

![](./EmployeeSQL/ERD.png) 

### Data Engineering

After creating a schema, the tables were generated with imported csv files accounting for pre-existing headers. Afterwards, the tables needed to have Alter Table and Add Constraint added to properly reference the foreign keys between the tables according to the schema. Tables were also generated with value limits, whenever possible, to cut down on the overall size of the database. Included below are examples of the code used:

![](./EmployeeSQL/screenshots/create_table_example_screenshot.png) 

![](./EmployeeSQL/screenshots/altertable_addconstraint_screenshot.png) 

### Data Analysis

After properly generating tables using the developed schema, a second query was created to answer the challenge questions. For convenience, screenshots of the code and their corresponding truncated results are included below:

![](./EmployeeSQL/screenshots/data_analysis_1.png) 

![](./EmployeeSQL/screenshots/data_analysis_2.png) 

![](./EmployeeSQL/screenshots/data_analysis_3.png) 

![](./EmployeeSQL/screenshots/data_analysis_4.png) 

![](./EmployeeSQL/screenshots/data_analysis_5.png) 

![](./EmployeeSQL/screenshots/data_analysis_6.png) 

![](./EmployeeSQL/screenshots/data_analysis_7.png) 

![](./EmployeeSQL/screenshots/data_analysis_8.png) 




## Attributions

The ERD was generated using: <br>
- https://app.quickdatabasediagrams.com/<br>
