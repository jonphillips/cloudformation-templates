# CloudFormation Templates

This repository contains a collection of templates for [AWS CloudFormation](https://aws.amazon.com/cloudformation/) for various use cases.

aws cloudformation create-stack --stack-name EXAMPLE-OF-NAME \
--template-url https://aws-utilities-8dh76.s3.amazonaws.com/Utilities/static-website.yaml \
--parameters ParameterKey=HostedZoneId,ParameterValue=Z2M504VOZU0JNP ParameterKey=DomainName,ParameterValue=WWW.EXAMPLE.COM \
--notification-arns arn:aws:sns:us-east-1:133314201444:static-repo-123 \
--region us-east-1
