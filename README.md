# Project Name: AWS Static Website Hosting

## Description
This project utilizes AWS Static Website Hosting to deploy and host a static website. Static website hosting is a simple and cost-effective solution for hosting websites that consist of HTML, CSS, JavaScript, and other static files, without the need for server-side processing.

## Setup Instructions
1. **AWS Account Creation:** If you haven't already, create an AWS account
2. **AWS Console Access:** Log in to the AWS Management Console.
3. **Static Website Hosting Configuration:**
   - Navigate to the Amazon S3 console.
   - Create a new S3 bucket with the same name as your domain or subdomain.
   - Upload your website files to the S3 bucket.
   - Enable static website hosting for the bucket and specify the index document.
   - Add Bucket policy to only read the objects from the bucket
4. **Domain Configuration (Optional):**
   - Configure DNS settings, create DNS record to point your domain or subdomain to the S3 bucket endpoint.
   - Once record is added to the hosted zone, we can open the site using the new record created : http://mysitedemo.razinscloud.link
