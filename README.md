# cross-account-lambda access securely

## Destination Account

### 1. Create STS assume role

![image](https://user-images.githubusercontent.com/112694225/205645188-37c07722-301e-496d-bf2a-67599dbb6647.png)

### 2. Assign policies to invoke Lambda Function in Destination account

![image](https://user-images.githubusercontent.com/112694225/205645215-38ca3b70-5241-400a-b5a0-b0af4c7fc3fd.png)

### Note: Created Cloudformation template for reference `destinationaccount.yaml`

![image](https://user-images.githubusercontent.com/112694225/205645529-5e7d2644-7e4d-48b9-9bcf-f0bfc52e0af9.png)

## Source/Central Account

### 1. Provide DestinationLambdaARN

### 2. Provide DestinationRoleArn

### Note: Created Cloudformation template for reference `sourceaccount.yaml`

![image](https://user-images.githubusercontent.com/112694225/205646018-ecd49f29-dc7c-48db-a285-120b9d931574.png)


