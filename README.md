# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template


# WooCommerce Infrastructure

This project defines the infrastructure for a custom WooCommerce-based product using AWS CDK in TypeScript.

## Getting Started

To deploy this infrastructure, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/1-woocommerce-project.git

Install dependencies:
npm install
Deploy the stack:
cdk deploy
Access the deployed resources:

Once the stack is deployed, you can access the resources such as the S3 bucket, RDS database, and EC2 instance using the outputs printed by the CDK.

Architecture Overview
This infrastructure includes the following components:

VPC: A Virtual Private Cloud with 3 availability zones.
S3 Bucket: An S3 bucket to store files.
RDS Instance: A MySQL database instance with specified configurations.
EC2 Instance: An EC2 instance for running the WooCommerce application.
Prerequisites
Before deploying this infrastructure, make sure you have:

An AWS account.
AWS CLI configured with necessary permissions.
Node.js and npm installed.
License
This project is licensed under the MIT License.


Please find Infrastructure Diagramm as ArchitechtureDiagram!





