![project-Architecture](https://github.com/user-attachments/assets/c1f5cdf0-1a39-4aae-858a-e60a4b5a8c7a)

**Project Title: Secure VPC Setup with EC2 Instances on AWS**

**Project Description:**

**Design and Configure VPC:** Created a custom VPC with specified IP ranges, and configured both public and private subnets to meet the project’s requirements.

**Network Security Implementation:** Set up network ACLs to control inbound and outbound traffic, ensuring secure communication across the VPC. Configured EC2 security groups to define the traffic allowed for instances based on ports and protocols.

**Provision EC2 Instances:** Launched EC2 instances in both public and private subnets, setting up security groups with appropriate traffic rules and configuring IAM roles for access control.

**Networking and Routing:** Configured an internet gateway for internet access for public subnet instances and set up a NAT Gateway in the public subnet for private subnet instances to access the internet.

**SSH Key Pair and Access Control:** Generated and securely stored SSH key pairs for instances to ensure controlled access. Configured the EC2 instances to only allow SSH access using the generated key pair. Managed IAM policies for further access control to AWS resources.

**Website Hosting in Private Subnet:** Successfully hosted a website inside the private subnet with an index.html page. This setup ensured that the website could only be accessed internally or via a secure jump host in the public subnet.

**Testing and Validation:** Verified the network setup by SSHing into EC2 instances and testing the connectivity between instances in different subnets. Ensured that security group rules and network ACLs were correctly implemented.

**Skills Gained:**

**VPC Configuration:** Learned how to create and configure a custom VPC and subnets for different networking requirements.

**Network Security:** Gained experience in configuring security groups and network ACLs for controlling traffic flow.

**EC2 Setup and Management:** Developed skills in provisioning EC2 instances and applying appropriate security measures.

**Routing and Internet Access:** Configured route tables, NAT Gateway, and Internet Gateway for secure and efficient routing.

**Access Control:** Managed IAM roles and SSH key pairs to control access and maintain security best practices.

**Web Hosting in a Private Subnet:**  Acquired experience hosting a website in a private subnet, ensuring secure and isolated access.


