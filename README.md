# udacity-IaC

This project is part of the Cloud DevOps Engineer Nanodegree Program at Udacity. It deploys a highly available web app using CloudFormation. The application code is deployed from the S3 bucket using IAM role.

## Pre-requisites

* [Amazon Web Services (AWS) account](http://aws.amazon.com/).
* [AWS Command Line Interface](https://aws.amazon.com/cli/) installed on your computer.

## Setup

Deploy

```bash
./create.sh $STACK_NAME $TEMPLATE_BODY $PARAMETERS
```

Update:

```bash
./update.sh $STACK_NAME $TEMPLATE_BODY $PARAMETERS
```

Delete:

```bash
./delete.sh $STACK_NAME
```
