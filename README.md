
# AWS Resource List Script

## Description
This Bash script automates listing AWS resources in a specified region. It supports services like EC2, RDS, S3, Lambda, and more, ensuring that the AWS CLI is installed and configured before execution.

## Features
- Supports resource listing for the following AWS services:
  - EC2
  - RDS
  - S3
  - CloudFront
  - VPC
  - IAM
  - Route53
  - CloudWatch
  - CloudFormation
  - Lambda
  - SNS
  - SQS
  - DynamoDB
  - EBS
- Checks if AWS CLI is installed and properly configured.
- Lists resources for the specified AWS region and service.

## Usage
Run the script as follows:
```bash
./aws_resource_list.sh <aws_region> <aws_service>
```

### Example:
```bash
./aws_resource_list.sh us-east-1 ec2
```

### Supported Services:
- **ec2**: List EC2 instances.
- **rds**: List RDS instances.
- **s3**: List S3 buckets.
- **cloudfront**: List CloudFront distributions.
- **vpc**: List VPCs.
- **iam**: List IAM users.
- **route53**: List Route53 hosted zones.
- **cloudwatch**: List CloudWatch alarms.
- **cloudformation**: List CloudFormation stacks.
- **lambda**: List Lambda functions.
- **sns**: List SNS topics.
- **sqs**: List SQS queues.
- **dynamodb**: List DynamoDB tables.
- **ebs**: List EBS volumes.

## Prerequisites
1. **AWS CLI**: Ensure that the AWS CLI is installed on your system.
   - [Install the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

2. **AWS Configuration**: Ensure that the AWS CLI is configured with your credentials.
   ```bash
   aws configure
   ```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/GaveenBuddhika/aws_resource_list.git
   ```

2. Navigate to the project directory:
   ```bash
   cd aws_resource_list
   ```

3. Make the script executable:
   ```bash
   chmod +x aws_resource_list.sh
   ```

## Contributing
Feel free to submit issues, fork the repository, and send pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
- **Gaveen Buddhika**
