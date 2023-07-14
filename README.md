# infrastructure

# Setup instructions using CloudFormation

* Create user with programatic access
* Create a profile in Amazon cli using the user credentials generated (Access key Id and Secret Access key) ex: aws configure --profile dev
* Create a CloudFormation template in YAML format with all the required parameters for VPC, Subnet, InternetGateway, RouteTable
* Create a stack using CloudFormation and Amazon cli ex: aws cloudformation create-stack --stack-name myvpc --template-body file://csye6225-infra.yml ParameterKey=key1,ParameterValue=value1 --profile demo
* Stack can be deleted using aws cloudformation delete-stack --stack-name myvpc --profile dev 

# Serverless and WebApp repos

[Click here for Serverless repo](https://github.com/SaiChandGhanta/3-user-file-hosting-serverless)

[Click here for WebApp repo](https://github.com/SaiChandGhanta/1-user-file-hosting-webapp)
