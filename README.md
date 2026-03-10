# cloud-security-implementation
Task 4

COMPANY: CLOUDTECH IT SOLUTIONS

NAME: NEHA SATPUTE

INTERN ID: CTIS5002

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

In this task, I implemented basic cloud security using Identity and Access Management (IAM) in Amazon Web Services. The main objective of this task was to understand how user access and permissions can be controlled in a cloud environment to improve security and prevent unauthorized actions.

First, I logged into the AWS Management Console using the root account and navigated to the IAM service. IAM allows administrators to manage users, roles, and permissions securely within the AWS environment. After opening the IAM dashboard, I created a new user who would have limited access to specific services instead of full administrative permissions.

While creating the user, I enabled the option for AWS Management Console access so that the user could log in through the AWS web interface. A secure password was generated for the user account. After creating the user, the next step was to assign permissions. Instead of granting full access to all AWS services, I attached the AmazonS3FullAccess policy to the user. This policy allows the user to manage and interact only with the Amazon S3 service.

Amazon S3 is a cloud storage service used to store and manage files in buckets. By assigning only the S3 access policy, the user is restricted to working only with storage resources and cannot modify other AWS services such as EC2, networking, or IAM.

After completing the configuration, I logged out from the root account and logged in using the newly created IAM user credentials. I verified that the user was able to access the S3 service but could not access other services, which confirmed that the permissions were successfully restricted.

Through this task, I learned how IAM policies help implement cloud security by controlling user access and applying the principle of least privilege.

output

<img width="1882" height="818" alt="Image" src="https://github.com/user-attachments/assets/983c80de-1235-46aa-bcaf-dbe3dcabb668" />

<img width="1872" height="787" alt="Image" src="https://github.com/user-attachments/assets/4778e221-0ed7-4530-a201-d0a17efad073" />

<img width="1902" height="760" alt="Image" src="https://github.com/user-attachments/assets/f643b0f1-4b8a-4365-8eba-abf06bc3034e" />

<img width="1871" height="791" alt="Image" src="https://github.com/user-attachments/assets/f66b542a-910a-4b08-b325-339e4b26e6d7" />

<img width="1871" height="791" alt="Image" src="https://github.com/user-attachments/assets/61dde1db-1cc7-4902-9ac6-19050a79a4bc" />
