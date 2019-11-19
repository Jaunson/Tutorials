#  ETL ( Extract, Transform, Load) & Programmatic Solutions
ETL generically refers to the process of taking some data from source systems, (such as your CRM, ERP, or Marketing stack) transforming said data, and then loading it to some end system / application. These files focus on moving data, creating automation, and useful tricks to increase your productivity.

**Extract**

Taking data from a source system
- Building pipelines to pull data from some source system(s) 
- Considerations around volume, speed (performance), cost

**Transform**

Manipulating Data for some end purpose, common transformations can include:
- Aggregation 
- Applying logic or calculations
- Joins, sorts, or pivots
- Applying data validation

**Load**

Loading or sending the data to some end system or application
- Output to a data warehouse
- Generating  flat files
- Updating / Creating tables in a database 

ETL is typically the domain of a data engineer, since there are usually mission critical considerations around volume, speed, and cost of shuttling data around large enterprise systems. However, today it is not uncommon to see various developer positions that typically deal with creating automation around smaller volumes of data / non-critical systems.


![ETL](https://www.altexsoft.com/media/2019/06/word-image-29.png)
