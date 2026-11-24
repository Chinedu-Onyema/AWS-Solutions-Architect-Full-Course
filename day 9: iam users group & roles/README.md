# IAM Users, Groups, and Roles

## INTRODUCTION

AWS Identity and Access Management (IAM) is the access control service in AWS that governs who can authenticate and what resources and actions they are permitted to use within an AWS account. 
Acting like the security guard of your cloud environment, IAM enforces security, granular control, auditing, and least-privilege access.

## CORE IAM BUILDING BLOCKS COVERED IN THIS MODULE INCLUDE:

IAM Users: Represent individual people or identities with their own login credentials, such as an IAM user granted permissions to manage S3 buckets.

IAM Groups: Collections of IAM users that share inherited permissions, for example, a "Developers" group granted access to EC2 and RDS while excluding S3 bucket access.

IAM Roles: Act like temporary access passes not tied to a single user, commonly assumed by applications, AWS services, or external entities, such as attaching an S3ReadOnlyRole to an EC2 instance so it can read from S3 without storing permanent credentials on the server.

### WATCH VIDEO WALKTHROUGH HERE: https://youtu.be/yf9RKZ7Fl-8

