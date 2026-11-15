# AWS IAM – Groups and Permissions Management

## Overview
This project demonstrates how to create IAM groups, assign users, attach permission policies, and verify access using the AWS IAM Policy Simulator.

## Objective
To understand AWS Identity and Access Management (IAM) and how group-based permissions simplify user administration and improve security.

## AWS Services Used
- AWS Identity and Access Management (IAM)
- IAM Users and User Groups
- AWS Managed Policies
- IAM Policy Simulator
- Amazon S3

## Implementation Steps

1. Created IAM users:
   - Developer1
   - Auditor1

2. Created IAM groups:
   - Developers
   - Auditors

3. Assigned users to their respective groups.

4. Attached permission policies:
   - Developers – PowerUserAccess
   - Auditors – ReadOnlyAccess

5. Verified group membership and attached permissions.

6. Tested permissions using the IAM Policy Simulator.

## Permission Testing Results

| IAM User | S3 Action | Result |
|---|---|---|
| Developer1 | ListAllMyBuckets | Allowed |
| Developer1 | CreateBucket | Allowed |
| Auditor1 | ListAllMyBuckets | Allowed |
| Auditor1 | CreateBucket | Denied |

## Conclusion

Successfully created IAM groups, assigned users, attached appropriate permission policies, and verified access using the IAM Policy Simulator.

This practical demonstrates how group-based permission management simplifies administration and provides controlled access to AWS resources.

## Author
Srikari

## Technologies
AWS | IAM | Amazon S3 | Cloud Computing
