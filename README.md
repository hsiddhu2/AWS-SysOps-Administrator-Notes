# AWS-SysOps-Administrator-Notes

These are notes creating while I was preparing for AWS Certified SysOps Administrator - Associate

## AWS Accounts Fundamentals

AWS accounts setup - 

1. To secure the root account user, Set MFA using any virtual MFA device like authenticator, duo etc. 
2. Create a new identity/user (using IAM) in the general account. Assign this user the full adminatration access to control general AWS Account. 
3. As a best practice, a root user account should not be used for anything apart from setting a brand new AWS account. 