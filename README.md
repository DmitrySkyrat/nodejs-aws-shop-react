# Task 2 (Serve SPA in AWS S3 and Cloudfront Services)

This is frontend starter project for aws-developer mentoring program.

- [S3 Bucket](http://react-shop-app-cdk-636160606609.s3-website-us-east-1.amazonaws.com/) S3 Bucket URL shows 403 Access Denied error.
- [CloudFront](dp9cxy1jano58.cloudfront.net/) CloudFront URL is provided and opens a static website

## Work has been done

S3 Bucket was created, Application was deployed, CloudFront Distribution and Invalidation created and configured by using AWS CDK. The Application can be built and deployed by running npm script commands.

### `deploy`

Builds the React application and deploys the entire AWS infrastructure (S3 bucket + CloudFront CDN) in one command.

### `cdk:deploy`

Deploys (or updates) the AWS CDK stack to your AWS account.

### `cdk:destroy`

Destroys (removes) all AWS infrastructure created by the CDK stack.
- Deletes the S3 bucket (including all files)
- Deletes the CloudFront distribution
- Removes associated IAM roles and policies