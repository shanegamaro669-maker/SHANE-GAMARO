
# Checkpoint 4 – Cloud Provider Comparison

## Introduction

Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP) are major public cloud providers. Although they use different product names, all three provide similar core infrastructure services for computing, storage, networking, and identity and access management.

## Cloud Infrastructure Service Comparison

| Infrastructure Component                 | AWS                                                                                                                            | Microsoft Azure                                                                                                                | Google Cloud Platform                                                                                                       |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| **Compute**                              | **Amazon EC2 (Elastic Compute Cloud)** – provides virtual servers that can be used to run applications and workloads.          | **Azure Virtual Machines** – provides scalable virtual machines running Windows or Linux.                                      | **Compute Engine** – provides virtual machines running on Google's infrastructure.                                          |
| **Storage**                              | **Amazon S3 (Simple Storage Service)** – object storage for storing and retrieving data.                                       | **Azure Blob Storage** – object storage designed for large amounts of unstructured data.                                       | **Cloud Storage** – managed object storage using buckets to store data as objects.                                          |
| **Networking**                           | **Amazon VPC (Virtual Private Cloud)** – provides logically isolated virtual networks, subnets, routing, and network security. | **Azure Virtual Network (VNet)** – provides private networking for Azure resources and communication with other networks.      | **Google Cloud VPC (Virtual Private Cloud)** – provides scalable networking for VMs, containers, and other cloud workloads. |
| **Identity and Access Management (IAM)** | **AWS IAM** – manages identities, authentication, roles, and permissions for AWS resources.                                    | **Microsoft Entra ID + Azure RBAC** – manages identities and controls access to Azure resources through roles and permissions. | **Google Cloud IAM** – manages access to Google Cloud resources by assigning roles and permissions to principals.           |

### Service Equivalents

The services are broadly equivalent in purpose:

* **AWS EC2 ↔ Azure Virtual Machines ↔ Google Compute Engine**
* **Amazon S3 ↔ Azure Blob Storage ↔ Google Cloud Storage**
* **Amazon VPC ↔ Azure Virtual Network ↔ Google Cloud VPC**
* **AWS IAM ↔ Microsoft Entra ID/Azure RBAC ↔ Google Cloud IAM**

AWS documentation identifies EC2 as a compute service and S3 as object storage, while Amazon VPC provides logically isolated virtual networks. AWS IAM controls authentication and authorization for AWS resources.

Azure documentation describes Virtual Machines as on-demand, scalable computing resources. Azure Blob Storage is its cloud object-storage solution, while Azure Virtual Network provides private networking for Azure resources. Microsoft Entra ID manages identities and access to applications, data, and resources, with role-based access control for permissions.

Google Cloud documentation describes Compute Engine as a virtual-machine computing and hosting service. Cloud Storage provides scalable managed object storage, and Google Cloud VPC provides networking for Compute Engine, GKE, and other workloads. Google Cloud IAM controls which identities have which roles and permissions on resources.

---

# Guide Questions

## 1. Which cloud provider offers the broadest range of services? Explain your answer.

**AWS** is generally considered to offer the broadest range of cloud services. AWS officially states that it provides **over 200 services** covering areas such as compute, storage, databases, analytics, networking, security, developer tools, and enterprise applications.

## 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products? Why?

I would recommend **Microsoft Azure** for an organization that primarily uses Microsoft products. Azure integrates closely with Microsoft's ecosystem, including Windows Server, Microsoft Entra ID, Microsoft 365, and other Microsoft technologies, making identity management and hybrid integration easier.

## 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

**Google Cloud** is widely recognized for its strengths in AI, machine learning, and Kubernetes. Google Cloud provides AI/ML services and Google Kubernetes Engine (GKE), while its VPC documentation specifically describes networking support for GKE workloads.

## 4. What similarities did you observe among the three cloud providers?

All three providers offer equivalent fundamental infrastructure services, including virtual machines, cloud storage, virtual networking, and identity/access management. Although the product names and implementation details differ, the basic purpose is similar: providing scalable computing resources, storing data, connecting cloud resources, and controlling access to infrastructure.

---

# Official Documentation References

### Amazon Web Services (AWS)

* [AWS Overview and Services Documentation](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html?utm_source=chatgpt.com)
* [Amazon EC2 Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html?utm_source=chatgpt.com)
* [Amazon S3 Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html?utm_source=chatgpt.com)
* [Amazon VPC Documentation](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html?utm_source=chatgpt.com)
* [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html?utm_source=chatgpt.com)

### Microsoft Azure

* [Azure Virtual Machines Documentation](https://learn.microsoft.com/en-us/azure/virtual-machines/overview?utm_source=chatgpt.com)
* [Azure Blob Storage Documentation](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction?utm_source=chatgpt.com)
* [Azure Virtual Network Documentation](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview?utm_source=chatgpt.com)
* [Microsoft Entra ID Documentation](https://learn.microsoft.com/en-us/entra/identity/?utm_source=chatgpt.com)

### Google Cloud Platform (GCP)

* [Compute Engine Documentation](https://docs.cloud.google.com/compute/docs?utm_source=chatgpt.com)
* [Cloud Storage Documentation](https://docs.cloud.google.com/storage/docs?utm_source=chatgpt.com)
* [Google Cloud VPC Documentation](https://docs.cloud.google.com/vpc/docs?utm_source=chatgpt.com)
* [Google Cloud IAM Documentation](https://cloud.google.com/iam/docs/overview?utm_source=chatgpt.com)

## Conclusion

AWS, Microsoft Azure, and Google Cloud provide the same fundamental building blocks required to create cloud infrastructure. Their differences are mainly in service names, features, integrations, and specialized capabilities, so understanding the equivalent services makes it easier for a cloud engineer to work across different cloud platforms.
