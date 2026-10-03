# AWS Smart Retail Cloud Deployment

A cloud application project developed for NIT2113 – Cloud Application Development at Victoria University.

The project deployed a promotional retail website for a fictional Australian retailer, MegaCart, using AWS cloud services.

## Architecture

The solution uses:

- Amazon S3 for static website hosting
- Amazon CloudFront for secure HTTPS content delivery
- Amazon SNS for promotional email notifications
- GitHub Actions for automated deployment
- GitHub Copilot for development assistance

## Architecture Flow

Customer  
↓  
Amazon CloudFront  
↓  
Amazon S3  
→ HTML / CSS / JavaScript website

Marketing / Admin  
↓  
Amazon SNS  
↓  
Email subscribers

## Technologies

- AWS S3
- AWS CloudFront
- Amazon SNS
- AWS IAM
- GitHub Actions
- GitHub Copilot
- HTML
- CSS
- JavaScript

## Key Features

- Static retail website hosted on Amazon S3
- HTTPS delivery through Amazon CloudFront
- HTTP-to-HTTPS redirection
- Promotional notification system using Amazon SNS
- Verified email subscribers
- Automated deployment from GitHub to AWS
- CloudFront cache invalidation after deployment

## My Contribution

My responsibilities included:

- Configuring Amazon CloudFront for secure HTTPS website delivery
- Connecting CloudFront to the Amazon S3 website
- Assisting with S3 public-access permissions and ACL configuration
- Creating the Amazon SNS promotional topic
- Adding and verifying SNS subscribers
- Publishing promotional notifications
- Testing successful email delivery
- Contributing to implementation, testing and technical documentation

## Challenges Solved

The team resolved several cloud-deployment issues, including:

- Incorrect S3 object permissions causing unstyled website content
- IAM access and collaboration permissions
- SNS topic configuration issues
- Secure CloudFront delivery configuration

## Project Outcome

The final solution successfully delivered the MegaCart website through CloudFront over HTTPS and distributed promotional messages to verified subscribers through Amazon SNS.

## Team Project

This project was completed collaboratively with Kevan Ly as part of NIT2113 – Cloud Application Development at Victoria University.

Original shared project repository:
`kevanly-GB/MegaCart_website`
