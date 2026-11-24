# IAM Policy Assignment

## INTRODUCTION

In AWS Identity and Access Management (IAM), IAM policy assignment refers to attaching a JSON-formatted permission policy to an IAM identity, such as a user, group, or role, to specify what actions are allowed or denied on target AWS resources and under which conditions. 
For example, you can attach a policy restricting a user to read-only operations on a specific Amazon S3 bucket.

## KEY POLICY TYPES AND STRUCTURAL ELEMEMTS COVERED IN THIS MODULE INCLUDE:

AWS Managed Policies: Pre-written, non-editable permission policies maintained by AWS for common use cases, such as AmazonEC2FullAccess.

Customer Managed Policies: Custom, reusable JSON policies authored and edited by your team to match organizational requirements, such as allowing EC2 access only in us-east-1.

Inline Policies: Non-reusable policies embedded directly into a single IAM user, group, or role, such as granting one developer access to a test S3 bucket.

Permission Policies: The umbrella category encompassing AWS managed, customer managed, and inline policies used to grant permissions in AWS.

IAM Policy JSON Structure: Every policy defines a Version (typically "2012-10-17") and one or more Statement blocks containing Effect ("Allow" or "Deny"), Action (API operations such as s3:GetObject and s3:ListBucket), Resource (target ARNs such as arn:aws:s3:::my-app-data and arn:aws:s3:::my-app-data/*), and an optional Condition block.

### WATCH VIDEO WALKTHROUGH HERE: https://youtu.be/OMyRRMWgZGA
