# AWS Cloud Portfolio

A personal portfolio website built with HTML, CSS and JavaScript and deployed on Amazon Web Services (AWS).

## 🌐 Live Website

https://d3epyof2g78zgv.cloudfront.net

## ☁️ AWS Architecture

User → Amazon CloudFront → Private Amazon S3 Bucket

The website files are stored in an Amazon S3 bucket and delivered securely to users through Amazon CloudFront.

## 🛠️ Technologies Used

- Amazon Web Services (AWS)
- Amazon S3
- Amazon CloudFront
- HTML
- CSS
- JavaScript
- Git
- GitHub

## 🔐 Cloud Configuration

- Deployed static website files to Amazon S3.
- Configured a private S3 origin.
- Configured Amazon CloudFront to deliver the website over HTTPS.
- Used Git and GitHub for source-code management.
- Tested and troubleshot the deployment to ensure the website was accessible through CloudFront.

## 📸 Deployment Evidence

### Amazon S3

The website files deployed to my Amazon S3 bucket.

![Amazon S3 Bucket](screenshots/s3-bucket.png)

### Amazon CloudFront

CloudFront distribution used to deliver the website.

![Amazon CloudFront Distribution](screenshots/cloudfront-distribution.png)

### Live Website

The completed portfolio running through the CloudFront distribution.

![Live AWS Portfolio](screenshots/live-website.png)

## 📚 What I Learned

Through this project, I gained hands-on experience deploying a static website using AWS.

I learned how Amazon S3 can be used to store website files and how Amazon CloudFront can securely distribute that content over HTTPS.

The project also gave me practical experience with cloud deployment, troubleshooting, Git and GitHub.
