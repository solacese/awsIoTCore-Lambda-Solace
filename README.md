# awsIoTCore-Lambda-Solace
IoT Device Provisioned/Managed by AWS Iot Core invokes a Lambda function to trigger publish to Solace

This repository holds code samples for using AWS lambda function to publish virtual sensor streams to Solace Event Broker. The lambda function may itself be triggered by a API Gateway/IoT Enterprise Button. Thr purspose of the demo is to show case distribution of sensor telemetry directly to Solace Event Broker and IoT device Management via AWS IoT Core.

### Demo Setup

- Provision IoT button device provisioned using AWS IoT Core/Click.
- Provision AWS lambda function (PublishToSolace)
- Create a Trigger for Lambda Function via API Gateway
- Configure IoT Button click tovoke End point configured in API Gateway.

### Prerequisistes
Hardware needed: 
- AWS IoT Enterprise Button








