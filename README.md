# Cloud Resume Challenge

A cloud-native resume website built on AWS as part of the 
Cloud Resume Challenge.

🌐 **Live site:** [bernardtetteh.cloud](https://bernardtetteh.cloud)

---

## Architecture

This project uses a fully serverless architecture on AWS:

- **S3** — Hosts the static resume website
- **CloudFront** — CDN for fast, secure content delivery
- **Route 53** — Custom domain DNS management
- **API Gateway** — REST API endpoint for visitor counter
- **Lambda (Python)** — Serverless function to read/write visitor count
- **DynamoDB** — NoSQL database to store visitor count

---

## Features

- Static website hosted on S3 with CloudFront distribution
- Custom domain with HTTPS via Route 53 and ACM
- Live visitor counter powered by Lambda and DynamoDB
- Infrastructure built and managed through the AWS Console

---

## Documentation

Full project documentation is available in the `/docs` folder:
[Cloud Resume Project Documentation](Cloud%20Resume%20Project%20Documentation%20.pdf)

---

## Author

**Bernard Tetteh**  
AWS Certified Solutions Architect – Associate  
AWS Certified Cloud Practitioner  
[LinkedIn](https://www.linkedin.com/in/bernardtettehb49t)
