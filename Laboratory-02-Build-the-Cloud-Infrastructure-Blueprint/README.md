# Cloud Infrastructure Laboratory

## Mission Overview

This laboratory focuses on investigating and understanding a Linux-based cloud server environment. The activities involve examining the server infrastructure, identifying its cloud components, researching major cloud providers, and documenting the technical findings.

The laboratory provides practical experience with basic cloud infrastructure concepts and Linux system administration commands.

## Objectives

The main objectives of this laboratory are:

* Investigate the Linux environment provided by KillerCoda.
* Identify the operating system and kernel version.
* Examine CPU, memory, storage, and networking resources.
* Identify the major components of cloud infrastructure.
* Compare equivalent services offered by AWS, Microsoft Azure, and Google Cloud.
* Practice using Linux commands to gather system information.
* Develop technical documentation using Markdown.
* Improve cloud infrastructure and Linux administration skills.

## Cloud Infrastructure Components

The following cloud infrastructure components were identified during the laboratory:

### Compute Resources

The Linux server provides virtual CPU resources used to execute commands, applications, and workloads. CPU model and the number of available CPU cores were identified using Linux system commands.

### Storage Resources

The server provides virtual disk storage for the operating system, applications, configuration files, and data. Disk capacity and mounted file systems were examined using Linux storage commands.

### Networking Resources

Networking resources allow the cloud server to communicate with other systems. The server's hostname and IP address were identified during the investigation.

### Operating System

The laboratory environment uses a Linux operating system. The operating system and kernel manage the server's hardware resources and provide the environment required to run applications and services.

### Cloud Provider Services

The laboratory also compared equivalent infrastructure services from:

| Component  | AWS        | Microsoft Azure                 | Google Cloud     |
| ---------- | ---------- | ------------------------------- | ---------------- |
| Compute    | Amazon EC2 | Azure Virtual Machines          | Compute Engine   |
| Storage    | Amazon S3  | Azure Blob Storage              | Cloud Storage    |
| Networking | Amazon VPC | Azure Virtual Network           | Google Cloud VPC |
| IAM        | AWS IAM    | Microsoft Entra ID / Azure RBAC | Google Cloud IAM |

## Tools Used

The following tools were used during the laboratory:

* **KillerCoda** – Cloud-based Linux laboratory environment
* **Linux Terminal** – Used to execute system investigation commands
* **Markdown** – Used to create technical documentation
* **AWS Documentation** – Used to research AWS infrastructure services
* **Microsoft Azure Documentation** – Used to research Azure infrastructure services
* **Google Cloud Documentation** – Used to research Google Cloud infrastructure services

## Linux Commands Executed

The following Linux commands were used to investigate the cloud server:

```bash
# Operating System
cat /etc/os-release

# Kernel Version
uname -r

# CPU Information
lscpu

# Number of CPU Cores
nproc

# Memory Information
free -h

# Disk Information
lsblk

# Mounted File Systems
df -h
findmnt

# Hostname
hostname

# IP Address
hostname -I
```

These commands were used to collect information about the server's operating system, kernel, CPU, memory, storage, file systems, hostname, and network configuration.

## Skills Learned

Through this laboratory, the following skills were developed:

* Basic Linux system administration
* Linux command-line usage
* System hardware and resource identification
* Disk and file-system investigation
* Basic network configuration investigation
* Cloud infrastructure identification
* AWS, Azure, and Google Cloud service comparison
* Technical documentation using Markdown
* Reading and interpreting cloud provider documentation
* Understanding the relationship between Linux resources and cloud infrastructure

## Challenges Encountered

One challenge was understanding how physical infrastructure concepts such as CPU, memory, storage, and networking are represented as virtual resources in a cloud environment.

Another challenge was identifying equivalent services between AWS, Azure, and Google Cloud because each provider uses different product names for similar functionality. Reviewing the official documentation helped clarify the differences and similarities between the platforms.

A further challenge was interpreting the output of Linux commands such as `lscpu`, `lsblk`, `df`, and `findmnt`. Repeatedly reviewing the command output helped improve familiarity with Linux system information.

## Conclusion

This laboratory provided practical experience investigating a cloud-based Linux environment and connecting Linux system resources to fundamental cloud infrastructure concepts. It also demonstrated that major cloud providers offer similar core capabilities while using different service names and implementations.

The activities strengthened Linux administration, cloud infrastructure, research, and technical documentation skills.

