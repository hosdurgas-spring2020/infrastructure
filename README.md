# Infrastructure
We are building the network Stack using Amazon Cloud Formation

## AWS Cloudformation
AWS CloudFormation provides a common language for you to model and provision AWS and third party application resources in your cloud environment. AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts. This gives you a single source of truth for your AWS and third party resource

## Commands to Run 
Create Stack
```
aws cloudformation create-stack \
  --stack-name csye6225demo \
  --parameters file:://parameters.json \
  --template-body file://networking.json
```
Delete Stack

``` 
aws cloudformation delete-stack --stack-name csye6225demo ```
