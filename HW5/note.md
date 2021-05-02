# Preparing 
1. Download [20210412_Cloud_Computing_Database_Services.ipynb](https://github.com/sefx5ever/SCU_Cloud_Computing_with_Fintech/blob/main/20210412_Cloud_Computing_Database_Services.ipynb)
2. Install Kit in 20210412_Cloud_Computing_Database_Services
3. Download [MySQL](https://dev.mysql.com/downloads/file/?id=503267)
4. Download [MovieData.zip](https://docs.aws.amazon.com/zh_tw/amazondynamodb/latest/developerguide/GettingStarted.Python.02.html)

# Step
1. Get Token in AWS (Account Details)
2. 案例 1：【S3】上傳 index.html
3. 案例 2：【RDS】完成 CRUD 操作
4. 案例 3：【DynamoDB】完成 CRUD 操作

# 案例 1：【S3】上傳 index.html
1. 利用boto3作為橋樑，並透過 Token 資訊，進行 AWS S3 的連接
2. 藉由迴圈，獲取 S3 Bucket 的所有列表
3. 選擇要上傳文件至指定Bucket

# 案例 2：【RDS】完成 CRUD 操作
1. Create DataBase with RDS
2. Select Engine: MySQL
3. Set up password
4. Select yes for Public Access
5. Connectivity & security -> Endpoint -> host
6. Connect to RDS with mysql.connector.connect()
7. Connect to RDS with MySQL Workbench
8. Using SQL to do CRUD

# 案例 3：【DynamoDB】完成 CRUD 操作
1. 利用boto3作為橋樑，並透過 Token 資訊，進行 AWS DynamoDB 的連接
2. Create Table
3. Load Data
4. Put Data
5. Read Data
6. Update Data
7. Delete Data
