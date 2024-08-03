# Azure ELT(Extract, Load and Transform)

The project was built to extract data from github into azure and making it available for further analysis. Tools used for this project:
1. Azure Data Factory
2. Azure datalake Gen2
3. Databricks
4. Azure Synapse serverless SQL

   
## The Architecture
![Flowchart - Data Architecture](https://github.com/user-attachments/assets/c5427fec-dcde-434b-9be1-4b57eb36e166)


- Github served as the source, olympics data was extracted from github

- Azure Datafactory was used to extract the olympics csv file from github and moved to Azure Datalake Gen2
  
  Pipeline created for the extraction
  ![Screenshot_3-8-2024_173117_adf azure com](https://github.com/user-attachments/assets/84176879-2903-4060-8621-1ee9c5d9d0da)

  Datasets
  ![Screenshot_3-8-2024_173428_adf azure com](https://github.com/user-attachments/assets/246831f1-7253-4c5c-a9cc-f91645e4eab1)

 Linked Services
 ![Screenshot_3-8-2024_173645_adf azure com](https://github.com/user-attachments/assets/10dfe2a0-fba8-4d5c-8203-dd5307c00df1)





