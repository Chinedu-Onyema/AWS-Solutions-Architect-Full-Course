# The Principle of Least Privilege in AWS IAM

## INTRODUCTION

The Principle of Least Privilege (POLP) in AWS Identity and Access Management (IAM) means granting users, groups, and roles only the minimum permissions necessary to complete their tasks, and nothing more, via IAM policies. 
Instead of assigning broad administrative access by default, permissions are scoped strictly to what a role or identity actually requires.

## KEY PRACTICES AND SECURITY BENEFITS COVERED IN THIS MODULE INCLUDE:

Restrict Access & Scope by Task: Avoid granting full admin rights unless required; tailor policies to specific duties such as read-only S3 access or starting/stopping EC2 instances without allowing volume deletion. For instance, a data analyst querying DynamoDB should receive only

Temporary Credentials & Ongoing Audits: Favor time-limited access through IAM roles and AWS STS where possible, and periodically review and trim unused permissions.

Security & Compliance Value: Least privilege reduces blast radius and accidental changes if credentials are compromised, helps satisfy regulatory frameworks like GDPR or HIPAA by restricting data access to authorized personnel, and mitigates insider threats and human error.

### WATCH VIDEO WALKTHROUGH HERE: https://youtu.be/yf9RKZ7Fl-8
