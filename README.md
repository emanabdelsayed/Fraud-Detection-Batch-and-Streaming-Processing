# Fraud_Transactions_Data_Pipline
#### Samsung Innovation Campus Final project

In this project, We designed and implemented a robust data pipeline that integrates data from multiple sources (relational databases, CSV files, and real-time streams) into a unified, structured Hive table on HDFS. The data pipeline ingests transactional data, which is further analyzed using Hive queries and visualized through a Power BI dashboard. Additionally, We developed machine learning models to detect fraudulent transactions, showcasing the power of big data analytics and AI in addressing real-world business challenges.

### Here is our DataFlow:

<img src="Data flow.jpg">

<br>

## Now, Let’s dive deeper into how the data pipeline operates:

### Data Sources:
<ol>
  <li>
    Maria DB
    <p>Transactions data are placed in transactions table at Mariadb.</p>
  </li>
  
  <li>
    CSV File
    <p>Transactions CSV File on the local disk contains transaction data.</p>
  </li>
  
  <li>
    Streams Of Data
    <p>Python Application Produce transactions data into our kafka topic.</p>
  </li>
</ol>