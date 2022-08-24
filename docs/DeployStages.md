# Deploy proccess stages

### 1) Database
testing the database connection at aws RDS
![image](https://user-images.githubusercontent.com/106440455/186283487-7cf6aaf9-042f-4935-98f6-a96c973bb3a7.png)

----

### 2) s3 Bucket
After S3 Bucket creation and setting the Static website Enabled
![image (3)](https://user-images.githubusercontent.com/106440455/186283650-78e31e38-1479-4899-8c97-38d95afe7933.png)

----

### 3) ElasticBeanstalk
#### Adding Environment variables to the ElasticBeanstalk after creation
Include all the needed variables to connect DB
![image (6)](https://user-images.githubusercontent.com/106440455/186283826-94e640d0-9041-4aec-87dc-c106622e0299.png)

----

#### Checking the ElasticBeanstalk health after adding all variables
checking the EB health after adding the Environemts to connect DB
![image (5)](https://user-images.githubusercontent.com/106440455/186283949-e05ff9cc-e1a5-46cc-a467-e8c038597bd3.png)

### 4) BackEnd Runtime
Checking the URL of the BackEnd server ( **[Live link to server](http://udagram-api-dev.eba-yuhybq3f.us-east-1.elasticbeanstalk.com/)** )
![image (7)](https://user-images.githubusercontent.com/106440455/186284123-4fde7362-aa4c-4c15-b054-ae19a7609548.png)

### 5) FrontEnd connected with BackEnd
Connecting to the S3 website after connecting API with FrontEnd and DB
![image (1)](https://user-images.githubusercontent.com/106440455/186284290-5934a741-b0eb-42f6-8832-403f111035bd.png)

### 6) Create the Github Repo
Add all files into repo after build and commit it to github 
![image](https://user-images.githubusercontent.com/106440455/186284414-741ef7d1-2b18-4d59-8708-215363bfa6f7.png)


### 7) CircleCi
Added all files to the CircleCi and setup the project with the needed Environment variables
#### Checking CircleCi Environment list
![image](https://user-images.githubusercontent.com/106440455/186418698-8e2687f1-5f24-4f9c-87c4-427b99c81abb.png)

#### Checking CircleCi Build
![image](https://user-images.githubusercontent.com/106440455/186284730-bdde5412-979f-4c04-88c0-52be1adeae97.png)

#### Checking CircleCi Deploy
![image](https://user-images.githubusercontent.com/106440455/186284748-ab5b6c80-7330-4fee-8419-7d88e186ec38.png)

#### Last CircleCi Status
![image](https://user-images.githubusercontent.com/106440455/186284765-fc86c104-758a-4070-a04a-cc8ba3fbb368.png)
