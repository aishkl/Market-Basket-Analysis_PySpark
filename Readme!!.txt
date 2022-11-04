
------------------------------------------------------------------
              STEPS TO RUN : MARKET BASKET ANALYSIS 
------------------------------------------------------------------


1. We referenced the datasets mentioned in the file which were uploaded in google drive and databrick's DBFS filestore.
	a. The datasets aisles, departments, products, order_product_train can be accessesd automatically as they are in public google drive.
	b. The datasets orders and order_product_prior had compatibility issues due to large size and had to imported in Databricks environment manually. You can upload these
	two datasets in "/FileStore/tables/" for executing the code without any dataset path issues.
	c. The integration of all datasets gives a dataset of 3.25 GB, a sample of the integrated data is included in the "Datasets/SampleData" folder.
3. Attached .pdf files of notebook executions for evaluation of input and outputs.



---------------------------------------------------------------
             LINK TO DATA SOURCE 
---------------------------------------------------------------

Link- https://www.instacart.com/datasets/grocery-shopping-2017 