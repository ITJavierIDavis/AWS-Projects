# Serverless Email Marketing Application

## Overview
This project demonstrates how to build a fully automated serverless email marketing system using AWS services. The system enables businesses to send automated email campaigns efficiently without managing servers.

## Technologies Used
- **AWS Lambda** - For executing email sending functions.
- **Amazon SES (Simple Email Service)** - For sending emails.
- **Amazon S3** - For storing email templates.
- **Amazon API Gateway** - For exposing endpoints to trigger emails.
- **Amazon DynamoDB** - For storing subscriber information.

## Features
- Fully serverless email marketing system.
- Automated email scheduling and triggering.
- Easy integration with web applications.
- Scalable and cost-effective.

## Architecture
1. **User submits request**: API Gateway receives the request.
2. **Data stored in DynamoDB**: Subscriber details are stored.
3. **Lambda function triggers SES**: Sends emails based on triggers.
4. **Email templates stored in S3**: Lambda fetches templates before sending.

## Setup Instructions
### Prerequisites
- AWS account with IAM permissions for SES, Lambda, S3, API Gateway, and DynamoDB.
- AWS CLI configured.

### Deployment Steps
1. **Set up SES**
   - Verify your email domain in AWS SES.
   - Configure sending limits.
   
2. **Create S3 Bucket**
   - Store email templates in S3.
   
3. **Create DynamoDB Table**
   - Table Name: `Subscribers`
   - Primary Key: `email` (String)
   
4. **Deploy AWS Lambda Functions**
   - Create a function to fetch subscribers and trigger SES.
   - Set up execution roles with necessary permissions.
   
5. **Set up API Gateway**
   - Create an API endpoint to trigger Lambda.
   
6. **Test the Setup**
   - Use Postman or AWS CLI to invoke API Gateway.
   - Check logs in CloudWatch.

## Usage
- Add subscribers via API.
- Store email templates in S3.
- Trigger email campaigns through API requests.

## Future Enhancements
- Implement email analytics.
- Support for email segmentation.
- UI dashboard for managing campaigns.

## Author
Javier Davis


