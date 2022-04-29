# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template

## setup
- `npm install -g aws-cdk`
- `cdk synth`
- `mkdir resources`
- create file `./resources/widgets.js`
- create file `./lib/widget_service.ts`
- edit file `./lib/aws-typescript-stack.ts`
- `cdk deploy`
- `curl -X GET 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/'`
- `curl -X POST 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/example'`
- `curl -X GET 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/'`
- `curl -X GET 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/example'`
- `curl -X DELETE 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/example'`
- `curl -X GET 'https://1nn56i8rg1.execute-api.us-east-1.amazonaws.com/prod/'`