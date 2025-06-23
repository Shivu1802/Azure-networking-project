Mini Project: Secure Static Website Hosting on Azure with Subnets, VM, Firewall & Bastion

_____________________________________________________________________________________
Objective: 

To design and deploy a secure and scalable static website on Microsoft Azure using services like Azure Storage, Virtual Network (VNet), Subnets, Virtual Machines (VM), Firewall, and Bastion Host to control access and enforce security.

_____________________________________________________________________________________
1. Cost Analysis
    * Estimated monthly cost calculated before deployment.
    * Free tier and student subscription benefits were utilized where applicable.

_____________________________________________________________________________________
2. Creating the Virtual Network
    * Created a Virtual Network named StudentVNet.
    * Address space: 10.0.0.0/16 assigned.
    * Region selected: Central India.

_____________________________________________________________________________________
3. Subnet Configuration
    Created 3 subnets:
    * Web Subnet – for hosting the static website.
    * Bastion Subnet – for secure SSH access.
    * Firewall Subnet – for network security and filtering.

_____________________________________________________________________________________
4. Deploying the Virtual Network
    * VNet successfully deployed.
    * Subnets were verified and connected properly.

_____________________________________________________________________________________
5. Creating Virtual Machine
    * Linux VM created inside the Web Subnet.
    * Used for website hosting and backend access.
    * NSG rules were updated to allow web traffic.

_____________________________________________________________________________________
6. Implementing Firewall Policy
    * Azure Firewall configured to allow only specific IPs and ports.
    * URL filtering enabled for enhanced security.
    * Rules defined to restrict unnecessary inbound/outbound traffic.

7. Bastion Host Deployment
(Image not separately uploaded but explained)

Azure Bastion configured in the Bastion Subnet.

Secure RDP/SSH access without public IP.

8. Uploading HTML Page
Static HTML page uploaded to Azure Storage (Web-enabled).

Verified in the browser using public endpoint.

9. Overall Network Diagram
Visual representation of the architecture:

Storage

VM

Subnets

Bastion

Firewall

10. Final Deployment Verification
Successful deployment message confirmed.

Static site working.

Firewall, NSG, and Bastion verified.

Conclusion:
Static website was securely hosted on Azure.

Subnetting and firewall policies ensured isolation and access control.

Azure Bastion provided secure VM access without exposing public IPs.

