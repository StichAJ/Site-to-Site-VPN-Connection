# AWS Site-to-Site-VPN-Connection
On-Premises and Cloud Platform for Disaster Recovery and Backup Solution (Hybrid/On-Premises and AWS Cloud Platform)

In modern IT infrastructure, secure connectivity between on-premises environments and cloud platforms is essential for seamless operations and disaster recovery. This secure VPN solution connects an on-premises, Data Center-1 with two AWS EC2 Instances Environment—to one AWS EC2 Instance, Data Center-2 for Disaster Recovery and Backup Solution.

Businesses need Site-to-Site VPN Setup:
Secure Data Transfer: Encrypts sensitive information to safeguard against unauthorized access.
Remote Connectivity: Enables secure access to company resources from any location.
Cost-Effective Solution: Reduces the need for costly private networks while improving efficiency and minimizing errors.
Improved Network Integration: Seamlessly bridges on-premises infrastructure with cloud-based services.
Business Continuity: Maintains reliable access to critical applications and data during disruptions.

Data Center 1 (On-Premises - N. Virginia Region)
Internet Gateway – Provides internet connectivity
Availability Zone A
Virtual Private Cloud (VPC)
Public Subnet:
EC2 Instance (Web Server)
NAT Gateway (Network Address Translation for private instances)
Private Subnet:
EC2 Instance (On-premises Test)
AWS Site-to-Site VPN – Secures connectivity to Data Center 2

Data Center 2 (Cloud-Based - N. Virginia Region)
Internet Gateway – Provides internet connectivity
Availability Zone B
Virtual Private Cloud (VPC)
Private Subnet:
EC2 Instance (Cloud Server)
AWS Site-to-Site VPN – Secures connectivity to Data Center 1

Disaster recovery depends on real-time data replication and failover automation. 
✔ On-premises instances continuously sync critical data to AWS Cloud EC2. 
✔ In case of infrastructure failure, AWS Cloud serves as the recovery environment. 
✔ Testing includes validating tunnel connectivity, monitoring logs, and running ping tests between private networks.



This setup is an effective Disaster Recovery and Backup Solution, ensuring secure and seamless integration between your on-premises and cloud environments.
