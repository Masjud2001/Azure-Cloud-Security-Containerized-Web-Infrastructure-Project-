🚀 Project Overview
I designed and deployed a secure Microsoft Azure cloud infrastructure using multiple Linux virtual machines, network security controls, and containerized applications. The environment was built as a personal cybersecurity lab to practice cloud security, Docker containerization, and network hardening techniques.

🏗️ Architecture Components

🔹 Virtual Machines (Linux)

•	Jump Box (Bastion Host) – Secure administrative access point

•	Web-1 – Web server running containerized application

•	Web-2 – Web server for redundancy and load balancing

🔹 Networking & Security
•	Configured Azure Network Security Groups (NSGs) to enforce least-privilege inbound and outbound traffic rules
•	Reduced public attack surface by restricting direct access to internal servers
•	Implemented Azure Load Balancer to distribute traffic across Web-1 and Web-2 for high availability

🔹 Docker & Containerization
•	Built and deployed a containerized web application using Docker
•	Managed Docker containers on Linux VMs to ensure isolated and consistent deployments
•	Used containers for hosting a practice website for cybersecurity testing

🔐 Security & Validation
•	Configured secure administrative access via Jump Box
•	Tested connectivity and verified open ports
•	Validated access controls and firewall rules
•	Ensured internal servers were not directly exposed to the public internet

🧪 Purpose of the Lab
This lab environment was developed to:
•	Practice cloud security architecture
•	Learn container security basics
•	Understand Azure networking and load balancing
•	Perform system hardening and access control testing
•	Gain hands-on experience with Linux server administration

🛠️ Technologies Used
•	Microsoft Azure
•	Linux (Ubuntu)
•	Docker
•	Azure Virtual Machines
•	Azure Load Balancer
•	Azure Network Security Groups (NSG)
•	Cloud Networking & Security Concepts

📚 Learning Outcomes
•	Secure cloud infrastructure design
•	Bastion host configuration
•	Containerized application deployment
•	Network segmentation and traffic filtering
•	High availability and redundancy implementation

📌 Author
Munshi Abdul Masjud
Cybersecurity & Networking Student


