Successfully completed a DataStage course at ITI, where I gained proficiency in IBM's InfoSphere DataStage for ETL tasks. Under the guidance of Eng. Salma Khaled, we extensively explored the intricacies of ETL processes, with a focus on constructing efficient pipelines for data extraction, transformation, and loading.
Our project was a practical application within the retail industry, centered around the implementation of a star-schema data warehousing flow.
We meticulously executed the ETL process, extracting data from the OLTP system, performing essential transformations, and subsequently loading the transformed data into the Retail_Data_Mart.
Furthermore, leveraging DataStage, we conducted comprehensive analysis on the established data mart, addressing critical business queries and deriving actionable insights.


Project Description:
Retail industry scenario In this scenario, we use a “real world” retail industry scenario to demonstrate a typical star-schema data warehousing flow using IBM InfoSphere DataStage. Hopefully, you can then extrapolate/customize this process flow to address the unique star-schema data warehousing requirements of your organization.
Our scenario assumes a fictitious national department store which decides to build a star-schema based sales analysis data warehouse with the dimensions of customer, store, product, Over time, dimension attributes are expected to change, and the requirement is to preserve versions of these changes in the star-schema data warehouse in order to deliver accurate results with queries that relate to prior versions of dimension attributes. The data source for the star-schema is an OLTP system.

First task involves the following actions:
a. Designing the star-schema
b. Populating the dimension tables and fact table
c. Setting up for the recurring tasks.

we have three dimensions product, retail, customer , fact table “transactions” 
![Screenshot 2024-03-28 043004](https://github.com/RadwaEsamiel/DataStage-ETL-Retail-Analytics/assets/151566696/1e93e369-9d55-49b6-be12-64aba7b0bd18)


Project Requirements
1. State the modeling process, translate the logical data model to a physical data model “Done by me “I made this step and load samples into files in attached files



2. Using ETL tool , we need to create ETL solution to load this data into files or data bases based on business need ,you should read source data and make transformation on it to serve business need
Questions:

1)
Need data mart that display each transaction for each customer based on type of customer “citizen” or “foreign” with information of it information of product and information of stock which buy with name file “RETAIL_DATA_MART” with transformation upper case of all customer name column

![Screenshot 2024-03-27 232128](https://github.com/RadwaEsamiel/DataStage-ETL-Retail-Analytics/assets/151566696/3fc8176a-64ba-400f-93f4-def8628a3028)




3. based on question 1 read data mart “ACTIVATIONSALES_DATA_MART”
Then answer the following business need:
• Display count of all transaction for each employee for each store

![Screenshot 2024-03-27 232110](https://github.com/RadwaEsamiel/DataStage-ETL-Retail-Analytics/assets/151566696/311f781f-f860-4b62-97c5-60e1112fd224)



• Display max profit made by which customer type. Illustrate: customer type “foreign” make 5 transactions, customer type “citizen” makes 3 transactions.
So, max profit made by foreign customers.Named DataMart “ACTIVATIONSALES_DATA_MART”
• Based on which customer make profit , give them Bouns
Equation = Annual_Income * SpendingScore * 100

![Screenshot 2024-03-28 024351](https://github.com/RadwaEsamiel/DataStage-ETL-Retail-Analytics/assets/151566696/d71f1c2f-e856-4ce5-a8d0-830ebbeabd8f)



