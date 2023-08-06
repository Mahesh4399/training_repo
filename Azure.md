Microsoft Azure 

Azure Architecture 
SQL Database -> ADF -> ADLS Gen2 (Bronze zone, Silver zone, Gold zone) Azure Databricks -> Azure Synapse Analytics -> Power BI

SQL Database             = To store the rawdata or the sink place
ADF                      = To create Pipelines
Azure Databricks         = To do the transformations (Bronze, Silver, Gold)
Azure Synapse Analytics  = To load the transformed data into tables
Power BI                 = To Generate the reports from the tables that are loaded and tro submit for the businees based on requirement.


Azure Cycle
Data Ingestion           = ADF
Transformations          = ADB
Loading the data         = azure Synapse analytics
Reports                  = Power BI
