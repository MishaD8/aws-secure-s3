# 🛡️ AWS Secure S3 Setup

## 📖 Description
This project demonstrates how to create and configure an **AWS S3 Bucket** following security best practices.

## 🎯 Project Goals
- Create a secure S3 bucket using AWS CLI and Python.
- Block public access to the bucket.
- Enforce server-side encryption (SSE).
- Enable CloudTrail logging for bucket actions.

## ⚙️ Technologies Used
- AWS CLI
- Python (boto3 library)
- JSON (for bucket policies)

## 📂 Files
| File | Description |
|---|---|
| secure_s3_setup.py | Python script to create and secure an S3 bucket |
| sample_policy.json | Example of a secure S3 bucket policy |
| README.md | Project documentation |

## 🚀 How to Use
1. Configure AWS CLI with a valid profile.
2. Run the script:  
   `python secure_s3_setup.py --bucket-name my-secure-bucket`
3. Check the bucket security settings via AWS Console or CLI.

## 🔗 Useful Links
- [AWS S3 Security Best Practices](https://docs.aws.amazon.com/AmazonS3/latest/userguide/security-best-practices.html)
- [boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
