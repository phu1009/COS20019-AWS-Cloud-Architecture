# COS20019 – Cloud Computing Architecture on AWS

Individual assignments for **COS20019 Cloud Computing Architecture** at Swinburne University of Technology (Hanoi), Semester 1 2025. Each assignment deploys a PHP "Photo Album" web application on Amazon Web Services and documents the architecture, configuration and testing in a report.

| Report | Topic | Period |
| --- | --- | --- |
| [Assignment 1b](docs/Assignment1b_PhotoAlbum_EC2_RDS_S3.pdf) | Photo Album deployed in a custom VPC: EC2 web server, RDS MySQL database, S3 photo storage, security groups / NACLs, phpMyAdmin | Submitted 20 Feb 2025 |
| [Assignment 2](docs/Assignment2_Scalable_Serverless_Architecture.pdf) | Highly available version: custom AMI + launch template, Auto Scaling group across two AZs behind an Application Load Balancer, `CreateThumbnail` AWS Lambda function, IAM roles, S3 bucket policy, NACLs | Mar 2025 |

## AWS services used
VPC · subnets & route tables · Internet Gateway · EC2 (Apache/PHP) · AMI & launch templates · Auto Scaling · Application Load Balancer · RDS (MySQL) · S3 · Lambda · IAM · Security Groups / NACLs

## Related certifications
AWS Academy Graduate – **Cloud Foundations** and **Cloud Architecting** badges (March 2025).

## Notes
- The Photo Album PHP code and the Lambda deployment package were starter material provided by the unit, so they are not republished here; this repository contains my architecture reports.
- The Assignment 1b report is dated by the submission date printed on its cover page (20/02/2025), because the file itself was re-saved later. Other commit dates reflect the original file modification dates of the coursework; the repository itself was published on GitHub in November 2026.
