# dynamic_synapse_pipeline
Using NYC Taxi Data. I have create three layers on azure datalake :- bronze ,silver and golden layer. 
The bronze layer holds raw data, silver layer holds transformed data and gold layer holds transformed and aggregated data ready to be consumed by BI tools or Reporting.
All initial work to create external tables ,views and stored procedure were done manually. The next step is to create dynamic synapse data pipelines using variables and parameter's and run the pipelines using triggers
