# Cloud Infrastructure Components

Cloud infrastructure is made up of different resources that allow cloud systems to operate and provide services. The KillerCoda Linux environment provides a practical example of how compute, storage, networking, and operating system resources can be investigated and understood.

## Compute Resources

**Purpose:**  
Compute resources provide the processing capability required to perform calculations, execute instructions, run programs, and process workloads. The CPU and its available cores are examples of compute resources that determine how processing tasks are handled by a system.

**Importance in Cloud Computing:**  
Compute resources are essential in cloud computing because applications, websites, and other cloud services require processing power to function. Cloud platforms depend on compute resources to execute workloads and provide services to users. Having appropriate computing capacity helps a cloud environment handle its assigned tasks efficiently.

**KillerCoda Linux Environment:**  
In my KillerCoda Linux environment, the processor represents the compute resource of the cloud server. The `lscpu` command was used to examine information about the processor, including its model and available CPU resources. The environment uses an Intel Xeon E312xx (Sandy Bridge, IBRS update) processor.

## Storage Resources

**Purpose:**  
Storage resources provide the space needed to keep operating system files, applications, documents, and other forms of data. Linux organizes these resources through file systems and mount points so that stored information can be accessed by the system.

**Importance in Cloud Computing:**  
Storage resources are important because cloud applications and services continuously need to save, retrieve, and manage information. Cloud servers also require storage for their operating system and application files. Available storage capacity must therefore be monitored to ensure that the server has enough space for its operations.

**KillerCoda Linux Environment:**  
In KillerCoda, the `df -h` command was used to investigate storage resources. This command displays information such as file systems, their total size, used space, available space, and their mount points. The investigation showed that the environment had 13 GB of available space on its main storage during the observation.

## Networking Resources

**Purpose:**  
Networking resources provide the connections that allow servers, computers, users, and applications to communicate with one another. Network information such as hostnames and IP addresses helps identify systems and enables communication between connected resources.

**Importance in Cloud Computing:**  
Networking is a major part of cloud computing because cloud services are accessed through networks. It enables communication between users and cloud servers and also allows different cloud resources to exchange information. Reliable networking is therefore necessary for cloud-based applications and services to remain accessible.

**KillerCoda Linux Environment:**  
The KillerCoda Linux environment provides networking information that can be examined directly from the terminal. The `hostname` command can be used to identify the name assigned to the server, while `hostname -I` displays its assigned IP address or addresses. These commands demonstrate how a Linux administrator can inspect basic network information of a cloud server.

## Operating System

**Purpose:**  
The operating system acts as the main software layer that manages the hardware and software resources of a server. It controls processes, memory, files, storage, networking, and other system resources while providing an environment where applications and commands can run.

**Importance in Cloud Computing:**  
The operating system is important because cloud servers need a stable environment for managing infrastructure resources and running services. Linux is commonly suited to server environments because it provides command-line tools that allow administrators to inspect and manage system resources.

**KillerCoda Linux Environment:**  
The KillerCoda environment used in the investigation runs Ubuntu 24.04.4 LTS with Linux kernel version 6.8.0-138-generic. Commands such as `cat /etc/os-release` and `uname -r` can be used to identify this information. The Linux terminal also provides the tools needed to investigate the compute, storage, and networking resources available in the environment.
