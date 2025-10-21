🎯 Objective

To understand how cloud virtual machines operate by creating, configuring, and connecting to a cloud-based server instance using a free-tier account.
This project demonstrates the implementation of Infrastructure-as-a-Service (IaaS) using AWS EC2.

🖥️ Project Overview

This project involves deploying an Ubuntu 22.04 LTS virtual machine on AWS EC2 within the US East (N. Virginia) region.
The instance was configured using the e2-micro type (free-tier eligible) and accessed remotely through AWS Console SSH for testing and verification.

⚙️ VM Configuration

Operating System: Ubuntu 22.04 LTS

Region: US East (N. Virginia) – us-east-1

Instance Type: e2-micro (1 vCPU, 1 GB RAM, Free Tier Eligible)

🧭 Steps to Launch the Ubuntu Instance
1️⃣ Login to AWS Console

Logged into the AWS Management Console

Navigated to EC2 under the Compute section.

2️⃣ Launch a New Instance

Clicked Launch Instance and provided a name (e.g., Ubuntu-VM).

Selected Ubuntu Server 22.04 LTS (Free Tier Eligible) as the Amazon Machine Image (AMI).

Chose e2-micro as the instance type.

3️⃣ Configure Key Pair

Created a new key pair (ubuntu-key.pem) for secure SSH access.

Downloaded and saved the key file for authentication.

4️⃣ Network & Security Settings

Configured the security group to allow:

SSH (Port 22) – for remote terminal access.

HTTP and HTTPS (optional) – for future web access.

5️⃣ Launch the Instance

Clicked Launch Instance to deploy the VM.

Waited until the instance state showed Running.

6️⃣ Connect via AWS Console

Clicked SSH → Open in Browser Window from the EC2 console.

Accessed the Ubuntu server directly through the browser-based terminal.

7️⃣ Verify Connection

Ran basic Linux commands in the browser SSH terminal:

uname -a
ls
whoami


Confirmed that the VM was active and fully accessible.

8️⃣ Stop or Terminate Instance

After testing, stopped the instance from the EC2 Dashboard to save free-tier credits.

📸 Deliverables

Screenshot of the running VM instance in the AWS console.

Screenshot of the browser-based SSH terminal session showing command execution.

💡 Learning Outcomes

Learned to launch and configure cloud virtual machines.

Gained hands-on experience with AWS Console SSH access.

Understood the basics of IaaS: scalability, remote access, and resource management.

Practiced secure management and monitoring of EC2 instances.
