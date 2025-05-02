# AWS Lambda + S3 Trigger Lab

This lab demonstrates how to build a serverless workflow using AWS Lambda triggered by file uploads to an S3 bucket.

## 🔧 What I Built
- A Lambda function in Python 3.12 that listens for `PUT` events (file uploads) to S3.
- The function logs the file name and size to AWS CloudWatch.
- Permissions were granted via IAM roles to allow Lambda to read S3 events.

## 🧪 How It Works
1. User uploads a file to an S3 bucket.
2. The upload event triggers the Lambda function.
3. The function logs the file details to CloudWatch logs.

## 🔐 Services Used
- AWS Lambda
- Amazon S3
- IAM (for execution role)
- CloudWatch Logs

## 📷 Screenshots
Check out the screenshot from inside my lab!

## 📌 Skills Demonstrated
- Serverless architecture
- Event-driven development
- AWS IAM roles and permissions
- S3 event handling
