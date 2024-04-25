
# AWS HTTP API
Full CRUD APP in AWS utlizing API gateway , Lambda Funtion , DynamoDB 


## AWS Architecture 
<img src="https://github.com/IbrahimGHO/AWS-HTTP-API/assets/98712253/fb80b678-9284-4412-bf52-5b1dd6ead57b"/>

## Dynamo DB
Creat a table with this name http-crud-tutorial-items with Partition key id
## Lambda

Create a Lambda function with Nodejs x16 Runtime 
Make sure you give it the proper roles to access the Dynamo DB table you can achive that by Creating a new role and add policy template called simple microservices policy 

## API Gateway

Make sure to configure 4 Routes 
GET /items
PUT /items
DELETE /items/id
GET /items/id

then go to integration and ingreate each route with the lambda function 

