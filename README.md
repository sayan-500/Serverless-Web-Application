## Serverless Web Application Workshop

The application architecture uses [AWS Lambda][lambda], [Amazon API Gateway][api-gw], [Amazon S3][s3], [Amazon DynamoDB][dynamodb], [Amazon Cognito][cognito], and [AWS Amplify Console][amplify-console]. Amplify Console hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser via S3. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a  persistence layer where data can be stored by the API's Lambda function.

