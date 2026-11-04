Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.

Snap Shot 1: Simple Storage Service (S3)
 

Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance



Snap Shots:
<img width="1762" height="830" alt="image" src="https://github.com/user-attachments/assets/2dc54d9e-9c62-44dd-8ba5-323f157efcab" />
<img width="1766" height="835" alt="image" src="https://github.com/user-attachments/assets/513ba75b-6ded-4930-bba0-8139e9f4a6e2" />
<img width="1762" height="835" alt="image" src="https://github.com/user-attachments/assets/38687764-eb14-47ea-8fc8-9da0ef96cb61" />
<img width="1767" height="835" alt="image" src="https://github.com/user-attachments/assets/3e21b5db-5fe2-4633-9d6e-7e00d9491d22" />
<img width="1765" height="836" alt="image" src="https://github.com/user-attachments/assets/7f741f0a-560d-4c3b-a70a-cc9895f888b6" />
<img width="1765" height="828" alt="image" src="https://github.com/user-attachments/assets/6151c7f9-a755-42a8-a63e-bd93b7c64ef4" />
<img width="1762" height="898" alt="image" src="https://github.com/user-attachments/assets/5997b262-8d2e-4002-8ec3-7a6c3de4baf4" />
<img width="1768" height="847" alt="image" src="https://github.com/user-attachments/assets/93760a0e-3ff4-4789-8df3-302e4d78eb21" />
<img width="1771" height="837" alt="image" src="https://github.com/user-attachments/assets/83f1ddf5-2286-46c9-a2fd-065c089e032c" />
<img width="1297" height="621" alt="image" src="https://github.com/user-attachments/assets/361ef3ef-0002-44f2-bf5b-4c1560f8b54f" />
<img width="1298" height="620" alt="image" src="https://github.com/user-attachments/assets/baeaba2d-eab5-4c8b-bc70-0571ba34b50d" />

Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
