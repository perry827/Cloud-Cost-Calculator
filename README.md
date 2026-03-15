Cloud Cost Calculator
Overview		
The Cloud Cost Calculator is a full-stack web application that estimates the monthly cost of deploying cloud infrastructure. The tool allows users to configure common cloud resources and receive a detailed cost breakdown based on estimated usage.
This project was built to simulate real-world cloud architecture planning and help engineers understand the financial impact of infrastructure decisions before deploying workloads.
The calculator currently supports several core services from Amazon Web Services, including compute, storage, databases, and serverless workloads.
Features
Estimate monthly cloud infrastructure costs
Configure compute, storage, and database resources
View detailed cost breakdowns by service
Simple and responsive web interface
Backend API for cost calculations
Containerized application for easy deployment
Infrastructure deployment using Infrastructure-as-Code
Supported Cloud Services
The current version estimates costs for the following services:
Amazon EC2 — virtual compute instances
Amazon S3 — object storage
Amazon RDS — managed relational databases
AWS Lambda — serverless compute
Amazon CloudFront — content delivery network
Tech Stack
Frontend
React
Tailwind CSS
Backend
FastAPI
Python
Infrastructure & DevOps
Docker for containerization
Terraform for infrastructure as code
Cloud Platform
Amazon EC2 for backend hosting
Amazon S3 for static site hosting
Architecture
High-level system architecture:
'
