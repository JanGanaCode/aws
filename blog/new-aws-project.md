Creating a new AWS CDK project via AWS CLI (TypeScript)

To work with the AWS CDK, you must have an AWS account and credentials and have installed [Node.js](https://nodejs.org/en/download/) and the AWS CDK Toolkit.

After installing Node.js, install the AWS CDK Toolkit (the cdk command):

```
npm install -g aws-cdk
```

You also need TypeScript itself (version 3.8 or later). If you don't already have it, you can install it using npm.

```
npm install -g typescript
```

You can create a new AWS CDK project by invoking cdk init in an empty directory.

```
mkdir my-project
cd my-project
cdk init app --language typescript
```
