# Step 1: Create a sql database with the ability to use both SQL and Microsoft Entra authentication to login. Create for development workload environment, select locally redundant backup storage
![alt text](lab5-db-server1.png)
Password: Matthew1

![alt text](lab5-db1.png)
![alt text](lab5-db2.png)

# Step 2: Login to the database using  SQL Server Management Studio (SSMS) or Azure Data Studio using both Microsoft authentication to install and sql login to the database created in step 1
## SQL conection
![alt text](lab5-SSMS-pre-SQL-connection.png)
![alt text](lab5-SSMS-post-SQL-connection.png)

## Microsoft Entra id connection
![alt text](lab5-SSMS-pre-Entra-connection.png)
![alt text](lab5-SSMS-post-Entra-connection.png)

# Step 3: Delete sql database and any other resources created
![alt text](lab5-delete-all.png)