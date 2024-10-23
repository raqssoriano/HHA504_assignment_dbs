# **HHA504 || Working with Managed Databases in Azure and Google Cloud Platform (GCP)**
---

- **📌** This task is part of my assignment focused on managing database services in **`Azure`** and **`Google Cloud Platform (GCP)`**. I am learning how to _*start*_, _*stop*_, and _*monitor*_ database-related services, including **`BigQuery`** and **`MySQL`**.


---

# _*Steps Taken to Complete this Assignment*_

---

## 1. Started and Configured a Managed Database

- ## _*Azure MySQL:*_
  - Navigated to the **`Azure portal`** and created a MySQL flexible server.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/2%20-%20successful%20deployment.png" width="550" />.
    
    ➙ Before I was able to successfully create one, I encountered multiple failed deployments due to reqion/location errors.
    
    ➙ **`South Central US`**: The only region/location that worked after multiple failed deployments.
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/3%20-error%20msg%20in%20most%20regions!.png" width="450" />.

  - The newly created SQL flexible server database and its configuration.
 
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/9%20-%20overview%20-%20properties.png" width="550" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/4%20-%20mysql%20flex%20server%20overview.png" width="550" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/1%20-%20Region%3ALocation%20-%20South%20Central%20US.png" width="550" />.
    
  - Created and added a database.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/7%20-%20add%3Acreate%20database.png" width="550" />.
    
  - Started the database service and noted the connection details.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/8%20-%20connect.png" width="550" />.

- ## _*GCP MySQL:*_
  - Accessed the Google Cloud Console and created a Cloud SQL instance with MySQL.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/1.png" width="300" />.
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/2.png" width="250" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/3.png" width="400" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/4.png" width="300" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/5.png" width="300" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/6.png" width="300" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/7.png" width="300" />.

  - Configured the database instance similar to Azure.
    
  - Start the database service and document the connection details.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/9%20-%20Summary.png" width="300" />.

---

## 2. Monitored Database Services

- ## _*Azure:*_
  - I learned different ways to navigate and monitor the performance and cost of the MySQL database. I explored metrics like CPU usage, memory, and query performance.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/10%20-%20monitor%201.png" width="600" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/11%20-%20monitor%202.png" width="600" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/Azure-SQL/12.png" width="600" />.

- ## _**GCP:**_
  - Used the GCP Console to monitor the Cloud SQL instance and the BigQuery dataset. Paid attention to similar metrics and noted any differences in monitoring tools between the two platforms.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/11%20-%20monitor%201.png" width="600" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/12%20-%20monitor%202.png" width="600" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/13%20-%20monitor%203.png" width="600" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/monitor%20-%20queries%201.png" width="550" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/monitor%20-%20queries%202.png" width="550" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/14.png" width="600" />.

---

## 3. Explored BigQuery (GCP)

  - In GCP, I navigated to BigQuery and created a dataset named **`raqs_query_dataset`**.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/16%20-%20create%20dataset.png" width="400" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/17%20-%20dataset.png" width="300" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/18%20-%20dataset%20created.png" width="550" />.
    
  - Loaded a small sample data file into a table within the dataset (CSV file) and created a table named **`personality-types`**.
  - Link to my chosen dataset: [Kaggle: Personality Types](https://www.kaggle.com/datasets/stealthtechnologies/predict-people-personality-types/data)

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/19.png" width="550" />.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/20%20-%20uploaded%20kaggle%20dataset.png" width="600" />.
    
  - Ran two simple queries against the dataset to retrieve specific data.

    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/21.png" width="600" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/23%20-%20simple%20query%202.png" width="600" />.
    
    <img src="https://github.com/raqssoriano/HHA504_assignment_dbs/blob/main/GCP-SQL/22%20-%20simple%20query%201.png" width="600" />.

---

## 4. Reflections on Managing Databases: Azure vs. GCP

- **📌** _**Setting up and Configurating Databases**_
    
    |       **Azure**              |           **GCP**             |
    |------------------------------|-------------------------------|
    | Azure portal provides a user-friendly interface for configuring databases,      |  GCP offers similar functions, but it provides a more straightforward interface for configuring and managing databases.        |


- **📌** _**Monitoring Database Services**_

  Both Azure and GCP offers robust monitoring tools.

    |       **Azure**              |           **GCP**             |
    |------------------------------|-------------------------------|
    | Azure offers an extensive monitoring for services which includes databases | GCP offers similar strengths for its services |
    | Both Azure and GCP gather different range of metrics and logs related to usage, availability, and performance.  | Additionally, their dashboards are customizable. |
    | Azure provides a centralized view of the costs beyond just database services, which gives me an option to analyze trends and set up budgets. | In my view, GCP offers more detailed billing information and cost breakdowns for the database services created.


- **📌** _**Creating and Making Queries**_

   Both Azure and GCP offer tools for SQL databases.

    |        **Azure**             |            **GCP**            |
    |------------------------------|-------------------------------|
    | Azure can handle SQL queries | GCP also handles SQL queries and offers BigQuery, which can handle large and complex analytical queries. I was able to run queries directly in the GCP console. |



- **📌** Both Azure and GCP provide comprehensive services for setting up, configuring, monitoring, and retrieving data from databases (SQL). The choice will depend on the specific needs of the user. I personally prefer GCP because I find it easier to use and navigate due to its more straightforward interface, making it a little less complicated.
