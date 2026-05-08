# Task 2 (Serve SPA in AWS S3 and Cloudfront Services)

This is frontend starter project for aws-developer mentoring program.

- [S3 Bucket](http://react-shop-app-cdk-636160606609.s3-website-us-east-1.amazonaws.com/) S3 Bucket URL shows 403 Access Denied error.
- [CloudFront](dp9cxy1jano58.cloudfront.net/) CloudFront URL is provided and opens a static website

### `deploy`

Builds the React application and deploys the entire AWS infrastructure (S3 bucket + CloudFront CDN) in one command.

### `cdk:deploy`

Deploys (or updates) the AWS CDK stack to your AWS account.

### `cdk:destroy`

Destroys (removes) all AWS infrastructure created by the CDK stack.
- Deletes the S3 bucket (including all files)
- Deletes the CloudFront distribution
- Removes associated IAM roles and policies