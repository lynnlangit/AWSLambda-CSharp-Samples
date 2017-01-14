# AWSLambda-CSharp-Samples
community code samples authored by SoCal Developers at 'cook and code'

Challenge: Build a community website (for SoCal Code Camp) using AWS C# Lambdas and other services for a serverless pattern
***

**Goals: **

* Write and deploy an AWS Lambda using C#
* Build a simple serverless application using AWS pattern 
* Use S3, Lambda (C#), DynamoDB, API Gateway

* * *
**Env Prep**

* Local OSX
    * Dev Env - VSCode adding C# extensions
    * .NET Core - https://www.microsoft.com/net/core#macos
    * AWS SDK and cli w/profiles
* AWS
    * Using AWS account - in AWS region [your region]
    * IAM users
        * Username:[your username]
        * Public Key: [your public key]
        * Private Key: [your private key
        * Group membership: [Administrators] NOTE: reduce permission for production
    * S3 buckets
        * s3:\\[your-bucket]\
        * s3:\\[your-bucket-2]\
    * GitHub Repo - this one

* * *
**Sprints**

* Python POC
    * Use AWS console and Python Lambda sample 'Hello Lambda' to build, deploy and test
    * Update code and repeat
    * Pull down code, package locally and upload
* C# POC
    * Do same steps as above using sample link
* Build simple Rekognition Application using pattern in Python 
* Translate Lambda to C# and build same application test
* Optimization and Security
    * Create non-admin IAM user (assign correct permissions) and test
    * Script setup steps
    * Optional - Use AWS CI/CD pipeline to push source code to GitHub
* Other Items
    * Explore Lambda deployment 'helpers', i.e. 'serverless-framework' / 'claudia.js'

* * *
**Link and Samples**

* Squirrel Bin (reference architecture) - _here_ (https://aws.amazon.com/blogs/compute/the-squirrelbin-architecture-a-serverless-microservice-using-aws-lambda/) 
* Hello Lambda / Python -- _here_ (http://docs.aws.amazon.com/lambda/latest/dg/getting-started-create-function.html)
* Blog post - C# support for Lambda -- _here_ (https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* C# Lambda programming model -- _here_ (http://docs.aws.amazon.com/lambda/latest/dg/dotnet-programming-model.html)
* Create a C# Lambda deployment package via the .NET Core cli - _here_ (http://docs.aws.amazon.com/lambda/latest/dg/lambda-dotnet-coreclr-deployment-package.html)
* Simple Mood Detector / Python - _here_ (http://www.awsomeblog.com/simple-mood-detector-powered-amazon-rekognition-aws-step-functions/) and GitHub sample _here_ (https://github.com/osalkk/simple-mood-detector) 
* GitHub C# AWS Lambda example - _here_ (https://github.com/guitarrapc/AWSLambdaCSharpIntroduction)
* GitHub C# AWS Lambda Kinesis S3 notification - _here_ (https://github.com/marking/cslambda)

* * *
Next Steps: Find sample for Serverless Code Camp Website using C# AWS Lambda Pattern
Features (listed in priority order)

1. Home page - static content
2. User Login
3. Speaker Info 
    1. Display from database
    2. Input into database
4. Abstract Info
    1. Display from database
    2. Input into database
5. Schedule Info
    1. Display from database
    2. Input into database
6. Admin Login
    1. Approve abstract
    2. Match approved abstracts to open session times
7. Other
    1. Display advertiser information
    2. Add OAuth 2.0 login (i.e. GitHub, etc..)

* * *

