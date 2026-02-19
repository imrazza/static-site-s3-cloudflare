Static Website Deployment on Amazon S3 using
GitHub Actions
Project Overview
This project demonstrates hosting a static website using Amazon S3 Static Website Hosting with
automated deployment via GitHub Actions CI/CD. Whenever changes are pushed to the main
branch, the website is automatically deployed to S3.
Architecture
GitHub Repository → GitHub Actions (CI/CD) → Amazon S3 (Static Website Hosting)
Technologies Used
• Amazon S3
• GitHub Actions
• AWS IAM
• HTML & CSS
Implementation Steps
• Created an S3 bucket and disabled block public access.
• Enabled Static Website Hosting with index document set to index.html.
• Added public read bucket policy for website access.
• Configured GitHub Actions workflow for automated deployment.
• Stored AWS credentials securely as GitHub Secrets.
Live Website
Website URL (HTTP): http://static1234.com.s3-website-region.amazonaws.com
Project Outcome
• Static website successfully hosted on Amazon S3.
• Automated CI/CD pipeline implemented using GitHub Actions.
• Secure AWS credential management via GitHub Secrets.
• Cloud-based deployment workflow established.
