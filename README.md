# Microsoft-Azure-Fundamentals-resource

* This repository contain resources of Azure fundamentals exam. 
* Hashnode Blog on Microsoft Azure exam (my experience)

## 3 resources which I used for preparing
1. Microsoft Learn Section ( from its website itself)
2. Udemy course
3. ExamTopics for question practice.


# Some Interview Questions For Azure Role:
## Q1. In Azure Cloud Service, What are the Cloud Servise Role?
* Azure Cloud Servise is an example of a Plateform as a Service (PaaS). The Cloud Servise are hosted on virtual machine (VMs).
* You have more controls over the VMs.
* You can install your own software on VMs that use Azure Cloud Servises and you can access them remotely.
* Azure Cloud Servise role are of two types:
1. Web Role
2. Worker Role

### Web Role: 
* It automatically deploys and host your apps through Internet Infra Service (IIS).
* A web role is basically used to deploy a website, usinglanguage supported by the IIS plateform likePHP, .NET etc
* It is configured and customised to run web application.
### Worker Role:
* It does not use IIS, and run your app standalone.
* A worker role is more like a helpto the web role.
* It is used to execute background process unlike the web role which is used to deploy the website.
* 
## Q2. What are Azure VMs?
* Azure VMs image servise instances that provide on-demand & scalablecomputing resources with used based pricing.

## Q3. What is Azure Managed Disk ?
* AMD are block level storage volumes that are managed by Azure and used with Azure VMs.
* Managed Disk are like a pgysical disc in an on-promises server but virtualised.
* With Managed Disc, all you have to do is specify the
- Disk size
- Disk type
- And provision the Disk

* Once you provision the disk, Azure handle the rest. The availability type of disk are:
- Ultra Disk
- Premium solid-state drives (SSD)
- Standard SSD
- Standard Hard Disk drive (HHD)

## Q4. What is Azure Virtual Network (VNet)
* Azure VNet is a network or environment that can be used to run VMs and applications in the cloud.
* When it created, the service and VMs within the azure network interact securily with each-other.

## Q5. What is VNet Peering?
* VNet peering enable you to seamlessly connect two or morevirtual network in Azure.

## Q6. What is NSG?
* A Network Security Group contains security rules that  allow or deny inbound network traffic to or outbound network traffic from, server types of Azure resources.

## Q7. What is Azure AD?
* Azure Active Directory is a cloud based identity and access management servise.
* This service helps your employees access external resources, such as Microsoft 365, Azure Portal and thousands of other SaaS applications.
