# aws-serverless-task-api
serverless Task API using AWS Lambda, API Gateway, and DynamoDB
# Serverless Task Management API (AWS)

# Overview
This project is a serverless CRUD API built using AWS services. It allows users to create, read, and delete tasks.




# Architecture
- API Gateway → Handles HTTP requests
- AWS Lambda → Runs backend logic
- DynamoDB → Stores tasks



# API Endpoints
- POST /tasks → Create a task
- GET /tasks → Get all tasks
- DELETE /tasks/{id} → Delete a task



# Testing Evidence

## POST Request
![POST Request](post-request-reqbin.png)

---

## GET Request
![GET Request](get-request.png)

---

## DynamoDB Table
![DynamoDB Table](dynamodb-tasks.png)

---

## Lambda Function
![Lambda Function 1](lambda-code-1.png)
![Lambda Function 2](lambda-code-2.png)
![Lambda Function 3](lambda-code-3.png)

---

## API Gateway Routes
![API Gateway Routes](api-gateway-routes.png)
 # Result
The API successfully stores and retrieves data using AWS serverless architecture.



 What I Learned
- How to use AWS Lambda
- How API Gateway connects to Lambda
- How DynamoDB stores data
- How to build a serverless backend
