# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
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


## OUTPUT:
<img width="1920" height="1200" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/7bac9d90-e759-4e73-8844-20b4af35ccfc" />

<img width="1920" height="1200" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/bb61ec67-fde1-40ac-910f-f869fe1522f5" />

<img width="1920" height="1200" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/5a555dcf-8c01-4367-8c44-1a786d82811e" />

<img width="1920" height="1200" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/49042baa-9315-4589-908d-eb0a026d0257" />

<img width="1920" height="1200" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/92866204-6f3f-4eb9-aa2e-60d578120ad4" />

<img width="1920" height="1200" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/adddb9b2-c9ef-468c-a6a7-3d1aecfd9bbe" />

<img width="1920" height="1200" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/896e938b-32e9-4683-8ccc-bc2d3b76996a" />

<img width="1920" height="1200" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/8962548d-2ba9-4218-b4ef-8d9f6ce886cf" />

<img width="1920" height="1200" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/0e2efa60-84f9-418e-b386-3105c5ea90a8" />

<img width="1920" height="1200" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/6d20886a-4efe-4589-a35d-d788eef655c3" />

<img width="1920" height="1200" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/530935cc-0d83-4676-a267-8f6616f1b501" />

<img width="1920" height="1200" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/3eb16476-ec38-47a4-8df4-162ea878bffe" />

<img width="1920" height="1200" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/0dfb600e-23c5-44b2-a0ca-48973b499a8a" />

<img width="1920" height="1200" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/ccbd39ef-73df-4feb-b00e-bc74b25ab556" />

## NAME: Mopuri Saradeepika
## reg no:212224040201

Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
