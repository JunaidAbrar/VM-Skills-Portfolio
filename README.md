KVM-Based Virtual Machine Creation and Management

This project demonstrates the creation and management of KVM-based virtual machines using both GUI and CLI on Ubuntu 22.04. It covers the entire process from system preparation to adding shared folders and connecting external devices. The steps include:

System Preparation:

Update system packages.
Verify if virtualization is enabled.
Install necessary KVM and additional virtualization packages.
Enable and start the virtualization daemon.
Add user to KVM and libvirt groups.
Creating a Virtual Machine:

Download Debian 12.5.0 ISO.
Create a VM using the Virtual Machine Manager GUI.
Setting Up Shared Folders:

Install virtiofsd package.
Create and configure a shared directory.
Modify VM configuration to include the virtiofs filesystem.
Test the shared folder functionality.
Connecting External Devices:

Connect an Android phone to the VM.
Cloning Virtual Machines:

Clone a VM using both GUI and CLI.
Adding Hard Disks to VMs:

Add hard disks to VMs using both GUI and CLI.
Each step is meticulously documented with commands and configuration details, ensuring reproducibility and ease of understanding.

