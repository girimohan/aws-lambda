# AWS Lambda Function for Image Processing

This AWS Lambda function processes images immediately after they are uploaded to an S3 bucket and logs their metadata to Amazon CloudWatch Logs.

## Getting Started

Follow these steps to set up and use the Lambda function:

### Prerequisites

- AWS account with permissions to create Lambda functions, S3 buckets, and CloudWatch Logs.

### Installation

1. Clone this repository.
2. Deploy the Lambda function code to your AWS Lambda environment.
3. Configure an S3 bucket to trigger the Lambda function on object create events.

### Usage

- Upload an image to the configured S3 bucket.
- Check CloudWatch Logs for the Lambda function to view image metadata.


