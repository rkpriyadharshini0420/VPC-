# Ex.4 Deployment and configuration of a Private Cloud  in AWS
## NAME: PRIYADHARSHINI R K
## REG NO: 212223040155

## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
## Procedure:
1. Plan Your VPC:

● Determine your needs:

Define your use case, including application requirements, security needs, and
compliance standards.

● Plan IP address ranges:

Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:

Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.

● Plan internet connectivity:

Determine if you need public internet access and how to configure it.

● Define security:

Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

2. Create Your VPC:

•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

•	 Choose "Create VPC": Initiate the VPC creation process.

•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

•	Create subnets: Define subnets within your VPC to isolate different parts of your	network.

•	Create route tables: Specify how traffic is routed within and outside the VPC.

•	 Create security groups: Define access control rules for your resources.

3. Deploying Resources:

•	Launch EC2 instances: Create and launch virtual machines within your VPC.

•	 Set up RDS instances: Deploy databases for your applications.

•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.

•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

4.Managing and Monitoring:

•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.

•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.

•	Implement security best practices: Regularly review and update your security
configuration.

•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

## Output:

 

Snapshot 1: Create VPC
![image](https://github.com/user-attachments/assets/dfe62cbc-80e4-4eb5-8b33-90527670eb38)

 
Snapshot 2: Configuring Subnets
 

![image](https://github.com/user-attachments/assets/c1649946-832a-4361-9854-49d3b5c03510)

Snapshot 3: Configure Subnets

 ![image](https://github.com/user-attachments/assets/22063a5b-c835-48ec-81cc-dbf20fa969af)


Snapshot 4: Setting Internet gateway

 ![image](https://github.com/user-attachments/assets/158d7523-6c8c-46cf-988a-dcca75a7f1cc)

Snapshot 5: Setting Internet gateway

![image](https://github.com/user-attachments/assets/a6ebe384-89e5-4d89-a8dd-8b5e12736966)

Snapshot 6: Setting Internet gateway

 ![image](https://github.com/user-attachments/assets/fcc6e690-7c43-46b0-a81b-c751a635308c)

Snapshot 7: Creating route table

 
![image](https://github.com/user-attachments/assets/5d53f42e-4f35-408d-a257-3d45186a8f31)

Snapshot 8: Configuring route table

![image](https://github.com/user-attachments/assets/a3aaf26b-6fba-4a43-9d1b-c4e9c02b1dcf)

 
Snapshot 9: Editing routes

 ![image](https://github.com/user-attachments/assets/5229f971-7150-4d90-8671-2824ea2f60af)

Snapshot 10: Creating route table

![image](https://github.com/user-attachments/assets/4c1e8154-75c8-49db-a63a-d1c11388b7f1)

## Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
