# AWS Project: How to Create a Static Website for Free Using Amazon S3

## 🚀 Overview
This project focuses on hosting a **fully functional static website** using **Amazon S3**, CloudFront, and Route 53. You will learn how to configure an S3 bucket for web hosting, secure it with SSL, and enable a CDN for faster global access.

## 🎯 Objectives
- Host a **static website** on Amazon S3.
- Configure **CloudFront** for content delivery.
- Secure the site with **SSL/TLS (HTTPS)**.
- Use **Route 53** for domain name management.

## 🔧 AWS Services Used
- **S3** – Object storage for website hosting.
- **CloudFront** – Content Delivery Network (CDN) for performance and security.
- **Route 53** – Domain Name System (DNS) for custom domains.
- **IAM** – Access Management for security.
- **Certificate Manager (ACM)** – SSL/TLS for HTTPS.

## 🏗 Architecture
1. **S3 Bucket:** Hosts the website files (HTML, CSS, JS, images).
2. **CloudFront:** Distributes content globally and enables HTTPS.
3. **Route 53:** Manages the website’s domain name.
4. **IAM Policies:** Secure the S3 bucket and CloudFront distribution.
5. **ACM:** Issues and attaches an SSL certificate to CloudFront.

## 📌 Implementation Steps
1. **Create an S3 bucket** and upload website files.
2. **Enable static website hosting** in the S3 settings.
3. **Set up CloudFront** to distribute content globally.
4. **Request an SSL certificate** from AWS Certificate Manager (ACM).
5. **Configure Route 53** to use a custom domain.
6. **Secure the website** with IAM policies and bucket permissions.

## 🎯 Expected Learning Outcomes
- Learn how to **host and deploy static websites** on AWS.
- Gain experience in **CloudFront caching, security, and HTTPS setup**.
- Understand **DNS management and domain configuration**.

## 📢 Next Steps
After completing this project, explore **serverless functions (AWS Lambda)** and **CI/CD for website deployment**.

---

### **📞 Need Help?**
- Refer to the official [AWS Documentation](https://docs.aws.amazon.com/).
- Reach out via **GitHub Issues** if you encounter problems!

🚀 **Let’s build and deploy a fast, secure, and scalable website using AWS!**
