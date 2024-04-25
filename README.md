# File Shares and Security Permissions Management (in progress)

## Overview
This project is created to display a practical understanding of network access control and security protocols by managing permissions on file shares.

## Environments and Technologies Used
- **Windows Server 2022**: Used for hosting file shares and managing permissions
- **Network File Sharing and Security**: Configuration of share and NTFS permissions

## High-Level Configuration Steps
1. **Setup File Shares on Windows Server**:
   - Create shared folders and configure share permissions.
2. **Configure Security Permissions**:
   - Manage NTFS permissions to control access to files and directories.
3. **Test Access Controls**:
   - Verify that the permissions and shares work as expected across different user accounts.

## Detailed Configuration and Testing Steps

### Step 1: Setup File Shares
- **Create Shared Folders**:
  - On your Windows Server, create new folders that will be shared across the network.

- **Configure Share Permissions**:
  - Right-click on the folder, go to Properties -> Sharing -> Advanced Sharing, and set the share permissions for user groups.

### Step 2: Configure Security Permissions
- **Set NTFS Permissions**:
  - In the folder properties, navigate to the Security tab and configure NTFS permissions to specify what actions different users or groups can perform on folder contents.

- **Security Groups for Access Control**:
  - Utilize Active Directory to create and manage security groups that help in applying permissions to a broader range of users efficiently.

### Step 3: Test Access Controls
- **Access Tests with Different User Accounts**:
  - Log in from different user accounts to test whether the access restrictions set through share and NTFS permissions are working correctly.

## Conclusion
Effective management of file shares and security permissions is crucial for protecting sensitive information and ensuring that only authorized users can access specific network resources. This project illustrates the steps necessary to configure robust access controls on Windows Server.

## Connect with Me
- **LinkedIn:** [Chazz Conino](https://www.linkedin.com/in/chazz-c-382a75122/)
