## Static Website Deployment on AWS using Terraform

### Introduction
This repository contains Terraform code and instructions to deploy a static website on AWS using Terraform. The deployment process involves creating an S3 bucket, making it public, uploading website files, enabling static website hosting, and finally deploying the website.

### Project Overview
This project aims to deploy a static website on AWS infrastructure using Terraform. The website consists of HTML, CSS, and JavaScript files that are hosted on an S3 bucket and made accessible to the public.

### Steps to Deploy

1. **Define AWS Provider**
   - Configure the AWS provider in Terraform to specify the AWS region and authentication credentials.

2. **Create S3 Bucket**
   - Use Terraform to create an S3 bucket that will host the static website files.

3. **Making Bucket Public**
   - Configure the S3 bucket policy to make it publicly accessible.

4. **Creating Index HTML using ChatGPT**
   - Generate the website's index.html file using ChatGPT or manually create HTML files for the website content.

5. **Upload Object in S3 using Terraform**
   - Use Terraform to upload website files (HTML, CSS, JavaScript).

6. **Enabling Static Website Hosting on S3**
   - Configure the S3 bucket to enable static website hosting.

7. **Website Deployment**
   - Once the static website is hosted on the S3 bucket, it will be accessible via the provided endpoint URL.

### Conclusion
By following the steps outlined in this README, you can deploy a static website on AWS using Terraform efficiently. This approach offers scalability, reliability, and cost-effectiveness for hosting static content on the AWS cloud platform.
