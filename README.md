#  Lab 1 - Introduction to AWS Identity and Access Management (IAM)
## Title
Introduction to AWS Identity and Access Management (IAM)

# Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS.
The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

# Prerequisites
Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity
## Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3
## Tasks Performed
Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
Screenshot:
<img width="1267" height="575" alt="image" src="https://github.com/user-attachments/assets/ef10c204-66ed-4e0a-8323-b21e52da15bd" />
## Task 2: Add Users to Groups
Added user-1 to the S3-Support group

Added user-2 to the EC2-Support group

Added user-3 to the EC2-Admin group
## Screenshot:
<img width="1232" height="587" alt="image" src="https://github.com/user-attachments/assets/99b39d2f-9eb2-4521-a8d0-affd8a822f9f" />
<img width="1228" height="557" alt="image" src="https://github.com/user-attachments/assets/d7c666ca-a247-433e-bdf1-fe6890665e16" />
<img width="1227" height="580" alt="image" src="https://github.com/user-attachments/assets/614a9646-8468-4fe6-8df8-8bb27c2e5c04" />
Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3
## Screenshot:
<img width="1278" height="591" alt="image" src="https://github.com/user-attachments/assets/ff836cc6-1671-4609-b6dc-0e7dc173f58f" />
<img width="1268" height="612" alt="image" src="https://github.com/user-attachments/assets/7c143a71-b2be-4208-a0f8-c977788dd291" />
<img width="1257" height="613" alt="image" src="https://github.com/user-attachments/assets/315bc7d0-ed0c-4931-b93a-eec61167af24" />
## Workflow:
Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.
Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.
## Learning Outcomes:
Understood the role of IAM in AWS security.
Learned how IAM users, groups, and policies interact.
Gained practical experience implementing role-based access control.
Verified permission enforcement through real-time service testing.
## Conclusion:
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.

# Author:
Name: SWATHI S(212225040449) Course: Introduction to Cloud Computing





