# GET-Data-From-DynamoDB-Send-SNS
This lambda function code collects data from 2 different dynamoDB database, database1 data is then used to create a post request to AWS SES  and publishes an email to the subscribers of databse 2.
Pease edit this code as neccessary for yopur use case, 
you will need IAM role permissions for lambda Including Dynamodb and SES policies.
Do not forget to set the Environment variables and name your databases and registered SES email.
You will need to update the Region name in the code to match the region your dynamodb is held
