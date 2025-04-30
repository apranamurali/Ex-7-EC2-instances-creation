Ex-06-EC2 Instance Creation
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
vcc1

Step 2: Launch an Instance
Click on Launch Instance and configure AMI (Amazon Machine Image) and Instance Type (e.g., t2.micro for free tier).
vcc2

Step 3: Create Key Pair
Generate a key pair in .pem format, which will be downloaded for SSH access.
vcc3

Step 4: Configure Network and Storage
Keep network settings default, or customize for VPC, subnets, and security groups.
Choose the EBS storage (up to 30 GB free for eligible free-tier accounts).
vcc4

Step 5: Launch and Connect
Confirm configurations and click Launch Instance.
Connect to the instance using SSH from your terminal with the downloaded key pair.
vcc5

Results
Successfully created the Elastic Compute Cloud (EC2) instances in this lab.

