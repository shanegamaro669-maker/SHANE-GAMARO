
# Checkpoint 3 – Identify Cloud Infrastructure Components

## Introduction

Cloud infrastructure is made up of several components that work together to provide computing services. In the KillerCoda Linux environment, examples of these components can be identified through system and network commands.

---

## 1. Compute Resources

### Example

The Linux environment provides a virtual CPU/processor with:

* **CPU Model:** `[Enter CPU model]`
* **Number of CPU Cores:** `[Enter number of cores]`

### Purpose

Compute resources provide the processing power needed to run applications, execute commands, and perform calculations. The CPU processes instructions and allows the Linux operating system and applications to operate.

### Importance in Cloud Computing

Compute resources are essential in cloud computing because cloud applications need processing power to run. Cloud providers can allocate virtual CPUs to users based on their workload requirements. Resources can also be increased or decreased as needed.

### Relation to KillerCoda

The KillerCoda environment provides a virtual Linux server with allocated CPU resources. Commands such as `lscpu` and `nproc` can be used to identify the available processor and number of CPU cores.

---

## 2. Storage Resources

### Example

The Linux environment contains virtual disk storage with a capacity of:

* **Disk Capacity:** `[Enter disk capacity]`
* **File Systems:** `[Enter relevant file systems]`

### Purpose

Storage resources are used to store the operating system, applications, configuration files, and user data. Linux organizes this storage through file systems and mount points.

### Importance in Cloud Computing

Storage is important because cloud servers need persistent space for operating systems, applications, databases, and other data. Cloud environments can provide different types and amounts of storage depending on the requirements of an application.

### Relation to KillerCoda

The KillerCoda Linux server uses virtual disk storage that can be examined with commands such as `lsblk` and `df -h`. The `findmnt` command can also show which file systems are mounted and where they are available in the Linux directory structure.

---

## 3. Networking Resources

### Example

The Linux environment has networking resources including:

* **Hostname:** `[Enter hostname]`
* **IP Address:** `[Enter IP address]`
* **Network Interface:** `[Enter interface if identified]`

### Purpose

Networking resources allow the Linux server to communicate with other computers, servers, and services over a network. An IP address identifies the server on the network, while network interfaces provide the connection.

### Importance in Cloud Computing

Networking is essential in cloud computing because cloud servers need to communicate with users, applications, databases, and other cloud services. Proper networking allows applications to be accessed remotely and enables communication between different infrastructure components.

### Relation to KillerCoda

The KillerCoda Linux environment has a network connection and an assigned IP address. The hostname and IP address can be identified using the `hostname` and `hostname -I` commands. These resources allow the virtual server to communicate within the KillerCoda environment.

---

## 4. Operating System

### Example

The Linux environment uses:

* **Operating System:** `[Enter OS name and version]`
* **Kernel Version:** `[Enter kernel version]`

### Purpose

The operating system manages the computer's hardware and provides an environment for applications and users. The Linux kernel manages resources such as the CPU, memory, storage, and networking.

### Importance in Cloud Computing

An operating system is important because cloud-based virtual machines require software that manages their hardware resources and provides services for applications. Linux is widely used in cloud computing because it is flexible, efficient, and supports many server applications and development tools.

### Relation to KillerCoda

KillerCoda provides a Linux-based cloud server environment. The operating system and kernel can be identified using commands such as `cat /etc/os-release` and `uname -r`. The Linux operating system manages the virtual CPU, memory, storage, and networking resources provided to the environment.

---

## Summary

The KillerCoda Linux environment demonstrates the four major cloud infrastructure components discussed in Chapter 2:

| Component            | Example in KillerCoda                 | Main Purpose                                 |
| -------------------- | ------------------------------------- | -------------------------------------------- |
| Compute Resources    | Virtual CPU and CPU cores             | Processes instructions and runs applications |
| Storage Resources    | Virtual disk and mounted file systems | Stores the OS, applications, and data        |
| Networking Resources | IP address and network interface      | Enables communication with other systems     |
| Operating System     | Linux and Linux kernel                | Manages resources and runs applications      |

These components work together to create a functional cloud computing environment. The Linux server provided by KillerCoda demonstrates how compute, storage, networking, and the operating system are combined to provide a virtual cloud infrastructure.
