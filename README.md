# ws-s3-website-hosting


Host a Website on Amazon S3

Project Overview

This project demonstrates how to host a static website using Amazon S3. The website includes an index.html file as the main webpage and an image folder containing assets referenced within the HTML.

What is Amazon S3?

Amazon S3 (Simple Storage Service) is a scalable cloud storage service that allows users to store and retrieve data securely. It provides high availability, durability, and cost-effective storage, making it useful for website hosting, backups, and data storage.

Steps to Set Up an S3 Bucket

Create an S3 Bucket

Chose a unique bucket name (e.g., nextwork-website-project-pushpendu).

Selected Mumbai region for faster access based on my location.

Configured the bucket settings and disabled ACLs for better security.

Upload Website Files

Uploaded index.html as the main webpage.

Uploaded an unzipped folder containing image assets.

Enable Static Website Hosting

Navigated to the Properties tab in the bucket settings.

Enabled Static website hosting and set index.html as the default document.

Set Permissions for Public Access

Initially, encountered an Access Denied error.

Resolved by updating the bucket policy to allow public read access.

Bucket Website Endpoint

Once static website hosting was enabled, Amazon S3 generated a bucket endpoint URL to access the hosted site:
👉 http://nextwork-website-project-pushpendu.s3-website.ap-south-1.amazonaws.com

Unexpected Challenge

One thing I didn't expect was the Access Denied error when first visiting the bucket endpoint. This was due to ACLs being disabled, preventing public access. I resolved this by updating bucket permissions and modifying the bucket policy.

Time Taken

This project took approximately 20-30 minutes, including setup, file uploads, and troubleshooting permissions issues.

Conclusion

Amazon S3 provides an easy and efficient way to host a static website. By following these steps, you can deploy a website on AWS with scalable and reliable cloud storage.

NextWork.org - Everyone should be in a job they love.
Check out NextWork for more projects!

