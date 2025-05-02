![Screenshot 2025-05-02 120411](https://github.com/user-attachments/assets/daa75c9e-f977-4514-8bfb-70f40c296050)
![Screenshot 2025-05-02 120242](https://github.com/user-attachments/assets/cbba5314-4d25-4bab-bd2a-cbf72b5df3fa)
![Screenshot 2025-05-02 120059](https://github.com/user-attachments/assets/a8db13a1-1330-4f48-a047-88b421ae7d4b)
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
