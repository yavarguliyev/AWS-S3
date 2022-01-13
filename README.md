# AWS-S3

```javascript
By enterin here: 'https://console.aws.amazon.com/iam/home#/users$new?step=details' fill the inputs then 'Select AWS credential type'.

Next,

Attach existing policies directly,

```

    1. IAMFullAccess
    2. AmazonS3FullAccess
    3. AmazonAPIGatewayAdministrator
    4. AmazonAPIGatewayPushToCloudWatchLogs
    5. AWSCloudFormationFullAccess
    6. AWSLambda_FullAccess

```

Next: Tags,
Next: Review,
Create User.

Then get, Access key ID and Secret access key add them to github repository settings/secrets...

Then go to setup the app...

After pushing wait for deploying in github/actions...

Then go to here: 'https://console.aws.amazon.com/apigateway/main/apis?region=us-west-1'...

If you wanna see the api URL go to here: stages here is the URL 'https://us-west-1.console.aws.amazon.com/apigateway/home?region=us-west-1#/apis/sw1mgu8onb/resources/al221tpfrk'...
```

[Postman documentation]()
