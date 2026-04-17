# MSFabric_ETL_Dataflow-Gen2_-_Pipeline
ELT using Dataflow Gen2 and Data Pipeline
Fabric Labs:

> Pipelines

- create LH
- import "FactInternetSales" into Lakehouse using "Dataflow Gen2"

> Lakehouse > Get Data > New Dataflow Gen2> 

(import ProductKey, SalesOrderNumber and SalesAmount)


> Create a pipeline
- Create a dataflow inside the pipeline to import the "DimCustomer" Spreadsheet


> if the Dataflow activity is successful (and only if it is successful), 

the pipeline should then run another dataflow to import the "DimSalesTerritory" spreadsheet.

Run the pipeline

Check that the data has been loaded into the lakehouse (it may take a while for it to be fully processed)
