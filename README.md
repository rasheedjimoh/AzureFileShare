# Azure File Share Integration into our environment

## Introduction
This lab aims to provide hands-on experience in integrating Azure storage accounts with corporate network domains, enabling efficient file sharing and access management. We navigate through essential steps, including configuring permissions, utilizing PowerShell scripts and leveraging Azure resources to establish seamless connectivity between storage accounts and domain networks.

![Screenshot 2024-02-09 004159](https://github.com/rasheedjimoh/AzureFileShare/assets/157264080/bb511455-fe43-4822-a045-d208d1acc07d)

 By mastering these techniques, We will gain valuable insights into optimizing storage solutions within Azure environments while reinforcing key concepts in access control and network integration.
 
 ### Let's break it down:

**Storage Account**: Think of it as a digital warehouse where you can store your company's files and data in the cloud.

**Domain**: This is like the digital neighbourhood where all your company's devices and users live. Connecting your storage account to the domain means making it part of your company's network, so people in your company can easily access the files stored there.

**Script**: A script is like a set of instructions for your computer to follow. In this case, it's a set of instructions to connect your storage account to the company's domain.

**Permissions**: Permissions determine who can do what with the storage account. For example, who can view files, who can edit them, etc.

**Azure AD**: This is Microsoft's service for managing user identities and access to resources like the storage account.

**Module**: This is a package of code that adds specific functionality to your computer. In this case, it's a package of code to help manage Azure resources.

**Resource Group**: This is a way to organize and manage your Azure resources together, like grouping your storage account with other related resources.

**Contributor Role**: This is a level of access in Azure that allows someone to manage resources within a resource group, like adding or removing them.

**Importing Module and Downloading Script**: These are steps to get the necessary tools and scripts onto your computer to manage the storage account.

**Roles and Permissions (Storage File Data SMB Share Reader/Contributor)**: These are specific permissions needed to work with the files in the storage account.

**Mounting Network Drive**: This means making the storage account appear as a drive on your computer, so you can easily access the files stored there.

**SMB 1.0/CIFS File Sharing Support**: This is a feature that needs to be turned on in Windows to enable certain types of file sharing.

**NTFS Permissions**: These are permissions specific to Windows file systems, determining who can access or modify files at a low level.

---------------

![Screenshot 2024-02-09 011411](https://github.com/rasheedjimoh/AzureFileShare/assets/157264080/4c0e650b-e05c-4426-8f66-72b4513d9d6d)




--------


![Screenshot 2024-02-08 223124](https://github.com/rasheedjimoh/AzureFileShare/assets/157264080/fa94d143-ca90-48a9-b997-0de50730be18)


  
## Technologies/Stacks
- VirtualBox as Hypervisor Type 2
- Azure Active Directory / EntraID
- Windows Server 2022 (DC): Mydomain's Domain Controller/ Active Directory
- Azure File Share
- Azure
- PowerShell
- SMB(Server Message Block)

![Screenshot 2024-02-09 004122](https://github.com/rasheedjimoh/AzureFileShare/assets/157264080/75332747-c89c-4226-b2f4-3538c3d3ce09)


![Screenshot 2024-02-09 042311](https://github.com/rasheedjimoh/AzureFileShare/assets/157264080/4f574d13-ab2b-4f00-88db-5ba4aaf5757c)



## Conclusion
In conclusion, this mini project has demonstrated the effective integration of Azure storage with our corporate network, enabling secure file sharing and streamlined access management. Moving forward, these advancements promise heightened efficiency and collaboration within our organization, underscoring the value of leveraging technology to drive business objectives.
