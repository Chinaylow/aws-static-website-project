# AWS Static Website Hosting with CloudFront

## Overview
This project demonstrates how to deploy a static website using Amazon S3 and distribute it globally using Amazon CloudFront.

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
![Website](IMG_6110DD3A-1566-49DB-A46D-E799F117FD2F.jpeg)

### S3 Website Endpoint
![S3 Endpoint](IMG_6650.jpeg)

### Bucket Policy
![Bucket Policy](IMG_6651.jpeg)

### Static Website Hosting Enabled
![Static Hosting](IMG_3AE3C381-0D26-4B30-B794-59ACEF18CE4F.jpeg)

### S3 Objects
![Objects](IMG_6649.jpeg)

## Security Note
Sensitive information has been excluded or anonymised where appropriate.
This project was completed using an IAM user rather than the AWS root account.
