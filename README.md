## 🔽 Deployment Guide 
> Step 1: Set up AWS Resources
1. Create an `S3 bucket` for your static files
2. Set up a `CloudFront` distribution pointing to your S3 bucket
3. Create an `IAM` user with permissions for S3 and CloudFront
> Step 2: Configure GitHub Secrets
- `AWS_ACCESS_KEY_ID`: Your AWS IAM user's access key ID
- `AWS_SECRET_ACCESS_KEY`: Your AWS IAM user's secret access key
- `AWS_REGION`: The AWS region of your S3 bucket (e.g., us-east-1)
- `S3_BUCKET_NAME`: The name of your S3 bucket
- `CLOUDFRONT_DISTRIBUTION_ID`: Your CloudFront distribution ID
> Step 3: Commit and Push (branch: main)
```bash
$ git add .
$ git commit -m "Add deployment workflow"
$ git push origin main
```
> Step 4: GitHub Actions Workflow CI/CD

      
## 🔽 CI/CD Pipeline
<img src="https://github.com/user-attachments/assets/e6103651-1b6f-4411-8265-757d50618c40" />


## 🔽 Link
- S3 end-point: http://hyewons-bucket.s3-website.ap-northeast-2.amazonaws.com
- CloudFrount: https://d149xzr8qgtyxl.cloudfront.net

## 🔽 Static Website 
<img src="https://github.com/user-attachments/assets/975b2e28-81fc-499e-88f8-1b283e6b15aa" width="400" height="300" />

