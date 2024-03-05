Steps to Build the Project:

Create a DynamoDB table to store the items.
Build a Lambda function to handle the CRUD operations on the DynamoDB table.
Create an API Gateway RESTful API to interact with the Lambda function.
Use S3 to store and host the web application's static files (HTML, CSS, and JavaScript).
Create a CloudFront distribution to serve the S3-hosted static files with low latency.
