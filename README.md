# Cloud-Optimized-Data-Ecosystem-Project-Integration

This repository has the knime workflows for extracting data from Yelp and NFT Sales.

Project Title: Establishing a Data Table of Yelp and Sales Data of a Particular NFT on MongoDB Cloud Cluster and generating insights through Knime.

Software Used: Python, MongoDB, Knime

Approach: 

Step 1: **Setup MongoDB Clusters**

**_Yelp Data Loading_**

The yelp data was loaded from another MongoDB Cluster. It was extracted using Knime and was loaded into my personal cluster using the Knime Workflow.

**_NFT Sales Data Loading_**

Setting up an API link been my python instance to Flipside data access endpoint to extract data from flipside. Additionally, the MongoDB cluster was linked to my instance as well to facilated data loading. Post which created the exact query to extract the data based on project name in my case it was "Pudgy Penguins". The extracted data was in json format, which was converted to a dataframe and was eventually loaded into the MongoDB cluster using the pre-established connection.

Step 2: **Knime Workflow Setup**

Post the data setup 2 Workflows have been made one for the Yelp DataBase, the other for the NFT Sales Insights.

All the files are available in the repository for further understanding.

Below are the screenshots of the workflows for reference.

Yelp_Insights_knime: ![image](https://github.com/panshul24/Cloud-Optimized-Data-Ecosystem-Project-Integration/assets/68370779/71f14e07-9470-4198-82f4-0ed97bf20bc8)

NFT_SalesInsights_Knime:![image](https://github.com/panshul24/Cloud-Optimized-Data-Ecosystem-Project-Integration/assets/68370779/75f160af-eb50-4913-91ca-c3d2b463d456)

PanshulSaraswat_Yelp: ![image](https://github.com/panshul24/Cloud-Optimized-Data-Ecosystem-Project-Integration/assets/68370779/4413688a-354a-4d37-81f9-cf7e844af5e2)


