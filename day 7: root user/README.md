# The AWS Root User

## INTRODUCTION
The AWS root user is the single, initial login identity created when an AWS account is established, tied to the account's registration email address and password. 
Because it holds unrestricted access to every resource, billing setting, and account configuration, regardless of IAM policies, it is a high-risk identity that should be protected with Multi-Factor Authentication (MFA) and reserved strictly for critical account-level tasks rather than everyday engineering work.

## KEY TAKEAWAYS FROM THIS MODULE INCLUDE:
Core Characteristics: There is only one root user per AWS account, linked to the registration email, with unlimited permissions and full billing control; a compromise gives attackers complete control over the account.

Root-Only / Restricted Tasks: Certain actions cannot be performed even by an IAM user with AdministratorAccess, including changing the account name, root email, root password, or root access keys; permanently closing the account; updating payment methods or tax details; modifying AWS Organizations consolidated billing; subscribing to or changing AWS support plans; enabling/disabling AWS Regions or S3 Object Lock; and recovering locked-out IAM access.

Security Best Practices: Enable MFA immediately, store root credentials securely, avoid using the root user for daily operations, and delegate routine administrative and developer tasks to least-privilege IAM users and roles.

### WATCH VIDEO WALKTHROUGH HERE: https://youtu.be/QnHeKGksZ-U

