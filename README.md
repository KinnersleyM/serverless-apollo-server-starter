# Serverless Node.js Starter

A Serverless starter for Apollo Server. This is an extension of the popular [Serverless Node.js Starter](https://github.com/AnomalyInnovations/serverless-nodejs-starter) repo.

It has been modified to let you deploy [Apollo Server](https://www.apollographql.com/docs/apollo-server/deployment/lambda) to AWS Lambda. It also includes [GraphQL Playground](https://www.apollographql.com/docs/apollo-server/deployment/lambda/#setting-up-graphql-playground).

This starter includes the [serverless-bundle](https://github.com/AnomalyInnovations/serverless-bundle) plugin which allows for the following features:

- Webpack bundling for smaller package sizes and faster cold starts.
- ES7 syntax features including `import` and `export`

### Requirements

- [Install the Serverless Framework](https://serverless.com/framework/docs/providers/aws/guide/installation/)
- [Configure your AWS CLI](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

### Installation

Install the Node.js packages

```bash
$ npm install
```

### Usage

Deploy your project

```bash
$ serverless deploy
```

Deploy a single function

```bash
$ serverless deploy function --function graphql
```

### Find out more

You will find a lot more information from the [Serverless Node.js Starter](https://github.com/AnomalyInnovations/serverless-nodejs-starter) repo.
