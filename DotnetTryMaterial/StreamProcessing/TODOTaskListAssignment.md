# TODO List Task Assignments

In our TODO List application each task in a TODO list can be assigned to a user. We want to use a Lambda function
to notifiy users when they have been assigned a task. To implement this we need to implement the following steps.

* Enable a DynamoDB Stream for our TODOList table
* Write and Deploy a Lambda function
* Configure DynamoDB Stream as a source for Lambda function

<!-- Generated Navigation -->
---

* [What is a serverless application?](../WhatIsServerless.md)
* [Common AWS Serverless Services](../CommonServerlessServices.md)
* [TODO List AWS Services Used](../TODOListServices.md)
* [Using DynamoDB to store TODO Lists](../DynamoDBModule/WhatIsDynamoDB.md)
* [Using Lambda to Handle Service Events](../StreamProcessing/ServiceEvents.md)
  * **TODO List Task Assignments**
  * [Enable DynamoDB Stream](../StreamProcessing/EnableDynamoDBStream.md)
  * [Assign Task Lambda Function](../StreamProcessing/LookAtLambdaFunction.md)
  * [Deploy Lambda Function](../StreamProcessing/DeployLambdaFunction.md)
  * [Setting up Amazon Simple Email Service (SES)](../StreamProcessing/SettingUpSES.md)

Continue on to next page: [Enable DynamoDB Stream](../StreamProcessing/EnableDynamoDBStream.md)
