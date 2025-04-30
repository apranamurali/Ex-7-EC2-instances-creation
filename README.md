#Ex-06-EC2 Instance Creation
NAME:APARNA.M
REG NO :212223220008
Aim
To set up and launch an Amazon EC2 instance, providing on-demand computing services with flexible configurations for application deployment.

Objectives
Log into AWS: Access the AWS Management Console to create and manage resources.
Launch EC2 Instance: Configure the required instance parameters, including OS, storage, instance type, and network settings.
Create Key Pair: Generate a secure SSH key pair for EC2 access.
Configure Network: Adjust the instance’s VPC, subnets, and security groups as needed.
Connect to Instance: Use SSH to establish a connection to the EC2 instance.
Automate EC2 Instance Creation: Set up an Ansible playbook to automate the instance setup.
Monitor Instance State: Track instance states (running, stopped, terminated) and utilize AWS CloudWatch for performance monitoring.
Instructions

Step 1: Log into AWS Account
Open the AWS console and select EC2 under Services.
![image](https://github.com/user-attachments/assets/9e27e245-7413-4e86-bfa8-385e9572022e)


Step 2: Launch an Instance
Click on Launch Instance and configure AMI (Amazon Machine Image) and Instance Type (e.g., t2.micro for free tier).
![image](https://github.com/user-attachments/assets/9ea66c73-52d5-4be9-888a-f6f77427b1a8)


Step 3: Create Key Pair
Generate a key pair in .pem format, which will be downloaded for SSH access.
![image](https://github.com/user-attachments/assets/9b45ae51-b940-4362-8e03-8a570ed4eef8)

Step 4: Configure Network and Storage
Keep network settings default, or customize for VPC, subnets, and security groups.
Choose the EBS storage (up to 30 GB free for eligible free-tier accounts).
![image](https://github.com/user-attachments/assets/cdeb892e-46e3-4e7f-8d19-b7752110aa51)

Step 5: Launch and Connect
Confirm configurations and click Launch Instance.
Connect to the instance using SSH from your terminal with the downloaded key pair.
![image](https://github.com/user-attachments/assets/480cb73f-8309-4296-8838-5cf2a038134b)



  
Results
Successfully created the Elastic Compute Cloud (EC2) instances in this lab.

