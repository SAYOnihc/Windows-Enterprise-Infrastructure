# Windows Server Administration Home Lab

## Project Summary

I built this Windows Server home lab to practice managing the core systems an IT department supports every day. I configured centralized user management, security policies, storage, DNS, remote administration, network access, data protection, virtualization, and performance monitoring.

The lab models a business environment for PromisedLand.com. Each configuration decision connects to a practical goal: protecting company information, controlling access, supporting employees, and keeping infrastructure manageable as the organization grows.

## Project Demonstration

[![Watch the Project Demonstration](https://img.youtube.com/vi/0uhvytfR-aw/maxresdefault.jpg)](https://youtu.be/0uhvytfR-aw)

## What I Configured

### Active Directory

Created organizational units, users, and security groups for CRM, Infrastructure, Operations, and Application teams. Assigned users to groups based on job responsibilities to support organized, role-based administration.

### Group Policy and Security

Configured password complexity and auditing for account logons, logon events, and system events. Disabled guest access, blocked anonymous account discovery, and prevented usernames from appearing at sign-in.

### File Storage Services

Created a `Promised Land` storage pool with thin-provisioned virtual disks for the CRM, Infrastructure, Operations, and Application teams. Each team received a 10 GB simple volume.

### DNS

Configured forward and reverse lookup zones, DNS forwarders, and domain name resolution. Reviewed DNS protection features such as socket pooling to reduce exposure to malicious traffic.

### Virtualization

Prepared Hyper-V Manager for virtual machine administration. Virtualization allows multiple workloads to run on shared physical hardware and provides a flexible environment for testing and future expansion.

### PowerShell and Remote Management

Used PowerShell and WinRM to review remote management and support user account administration. This provides a faster way to manage accounts without relying entirely on graphical tools.

### Network Policy Server

Configured network policies for domain user VPN access and stronger authentication requirements using passwords, certificates, or smart cards.

### Data Protection

Applied Windows security settings through Group Policy to reduce unauthorized discovery and access. These controls help protect account information and server resources.

### Performance Monitoring

Configured Performance Monitor counters for memory and network activity. These metrics help identify resource pressure, unusual behavior, and future capacity needs.

## Skills Demonstrated

- Windows Server administration
- Active Directory and role-based access
- Group Policy security and auditing
- DNS zones and forwarders
- Storage pools and thin provisioning
- Hyper-V virtualization
- PowerShell and WinRM
- Network Policy Server
- Security hardening
- Performance monitoring

## Why This Project Matters

This project demonstrates that I can build more than isolated configurations. I can organize users, apply security controls, manage infrastructure, troubleshoot administrative requirements, and connect technical decisions to business needs.

## What I Learned

I learned how Windows Server roles work together as one manageable environment. I also learned that effective system administration requires planning across identity, security, storage, networking, remote access, and performance.

## Evidence

The video demonstration documents the configurations described above. Remove passwords, personal information, private addresses, and other sensitive data before publishing.
