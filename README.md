"# Shell-Scripting-Project" 
# AWS Resource Listing Script

## Overview

This Bash script automates the process of listing all the resources in an AWS account across various services. It supports a wide range of AWS services, allowing users to quickly gather information about their AWS resources in a specific region.

## Supported Services

The script currently supports the following AWS services:

1. EC2
2. RDS
3. S3
4. CloudFront
5. VPC
6. IAM
7. Route53
8. CloudWatch
9. CloudFormation
10. Lambda
11. SNS
12. DynamoDB
13. EBS

## Prerequisites

- **AWS CLI**: Ensure that the AWS CLI is installed on your system. You can install it by following the instructions [here](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

- **AWS CLI Configuration**: Ensure that the AWS CLI is configured with your credentials. You can configure it by running:

  ```bash
  aws configure
