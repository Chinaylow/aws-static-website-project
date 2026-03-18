# AWS Static Website Hosting with CloudFront

## Live Demo
🚀 https://d1p29wxr8d99k.cloudfront.net

## Overview
This project demonstrates how to deploy a static website using Amazon S3 and distribute it globally using Amazon CloudFront with HTTPS enabled 

## Architecture
S3 (Origin) -> CloudFront (CDN) -> Users

## Services Used
- Amazon S3
- Amazon CloudFront
- IAM

## Key Features
- Static website hosting using S3
- Global content delivery using CloudFront
- HTTPS enabled through CloudFront
- Improved performance through caching at edge locations

## What I Did
- Created and configured an S3 bucket for static website hosting
- Uploaded website content using index.html
- Configured bucket policy for public read access
- Enabled static website hosting on the S3 bucket
- Created a CloudFront distribution
- Connected CloudFront to the S3 website endpoint
- Verified successful deployment using the CloudFront domain

## Screenshots

### Website live via CloudFront
![Website live via CloudFront](IMG_6110DD3A-1566-49DB-A46D-E799F117FD2F.jpeg)

### S3 Website Endpoint
![S3 Website Endpoint](IMG_21B6E60A-32D2-4A31-86AB-5F66BF082652.jpeg)

### Bucket Policy
![Bucket Policy](IMG_6651.jpeg)

### Static Website Hosting Enabled
![Static Website Hosting Enabled](IMG_6650.jpeg)

### S3 Objects
![S3 Objects](IMG_6649.jpeg)

### CloudFront Distribution
![CloudFront Distribution](IMG_3AE3C381-0D26-4B30-B794-59ACEF18CE4F.jpeg)

## Security Note
Sensitive information has been excluded or anonymised where appropriate.
This project was completed using an IAM user rather than the AWS root account.
