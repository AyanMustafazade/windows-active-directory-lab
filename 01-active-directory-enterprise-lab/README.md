# Active Directory Enterprise Lab

## Project Overview

This project demonstrates the deployment and administration of a Windows Server Active Directory environment.

The lab covers domain infrastructure, centralized user and group management, DNS, DHCP, Group Policy, access control, file sharing, and IIS web services.

## Lab Environment

- Windows Server
- Windows 10 Client
- Domain: `aztu.local`
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server
- Group Policy Management
- IIS Web Server

## Implementation

### 1. Windows Server Configuration

- Configured server network settings
- Assigned a static IPv4 address
- Configured the server hostname
- Prepared the server for Active Directory deployment

### 2. Active Directory Domain Services

- Installed Active Directory Domain Services (AD DS)
- Promoted the Windows Server to a Domain Controller
- Created the `aztu.local` domain
- Verified Active Directory functionality

### 3. Windows Client Domain Integration

- Configured Windows client networking
- Connected the client to the Domain Controller
- Joined the Windows client to the `aztu.local` domain
- Verified domain authentication

### 4. Organizational Units

Created and managed Organizational Units (OUs) to organize domain resources and users.

### 5. Users & Security Groups

- Created domain user accounts
- Created Security Groups
- Assigned users to appropriate groups
- Managed user account properties
- Tested domain user authentication

### 6. DNS

- Configured DNS services
- Created DNS records
- Tested hostname resolution
- Verified communication between domain systems

### 7. DHCP

- Installed and configured DHCP services
- Configured IP address distribution
- Tested DHCP functionality from client systems

### 8. Group Policy

Created and applied Group Policy Objects (GPOs) to centrally manage domain users and computers.

Policies included:

- CMD restrictions
- PowerShell restrictions
- Task Manager restrictions
- USB/removable storage restrictions

### 9. File Sharing & Permissions

- Created shared folders
- Configured NTFS permissions
- Configured Share permissions
- Implemented group-based access control
- Tested access using domain user accounts

### 10. IIS Web Server

- Installed IIS
- Configured the web server
- Deployed a test web service
- Verified access from the client environment

## Skills Demonstrated

- Windows Server Administration
- Active Directory Domain Services
- Domain Controller Administration
- Active Directory Users and Computers
- Organizational Units
- User & Group Management
- DNS
- DHCP
- Group Policy
- NTFS Permissions
- File Sharing
- IIS
- Windows Networking
- Access Control
- Troubleshooting

## Documentation

The complete lab documentation contains the implementation process, configuration steps, verification results, and screenshots.

## Key Takeaways

This project provided hands-on experience with deploying and administering a Windows enterprise domain environment using Active Directory and related Windows Server services.
