### AWS Amplify to easily host web page

- Zip html file to upload
- Upload Zip file for hosting

### AWS Lambda for distance caculation

- Create lamda function with Python
- To dos: connecting data base and write results
- Setup test case with test values
- Test function

### Amazon API Gateway to invoke the function

- Create an REST API
- Create methods to call
  - Create Resouce with POST
  - Create method
    - Lambda function
  - Enable CORS
- Deploy to dev stage ()
- Go back to Resources to test

### Amazon DynamoDB to store results

- Create new table and partition key of ID
- Grab ARN ()
- Back to Lambda - configuration
  - add permission and add inline policy

### AWS Identity and Access Maangement for managing access between services

- With the new role created from the lamdba funtion
  - add permission to inline policy
    - add in the dynamodb actions in json format
  - add in the arn link

### AWS Amplify to update the HTML file with the script and link to API Gateway staging
