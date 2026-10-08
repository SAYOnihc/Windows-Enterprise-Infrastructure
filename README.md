# PromisedLand.com Data Center Deployment Proposal

## Why I Created This Proposal

I created this project as a hands-on Windows Server home lab. Instead of only reading about server administration, I practiced building the services an organization would depend on, including Active Directory, Group Policy, DNS, DHCP, Hyper-V, storage management, and cloud integration.

Working through the project helped me practice managing users, computers, policies, virtual machines, and network services from a centralized Windows Server environment. It also gave me a practical way to connect classroom concepts to the kind of systems an IT department manages every day.

The goal was to propose a secondary data center for PromisedLand.com, a company supporting hybrid call centers across the United States and Canada. The facility would need to support employees, servers, applications, shared files, remote work, and future growth.

This project gave me the opportunity to connect the different parts of an IT environment. Instead of treating servers, users, storage, security, and cloud services as separate topics, I considered how they would work together in a real business. The sections below explain what I worked with and the problems each technology is intended to solve.

## Project Overview

This proposal outlines the design of a secondary data center for PromisedLand.com in Independence, Missouri. The facility will support hybrid call centers across the United States and Canada.

The proposed data center will occupy approximately 15,000 square feet and support about 50 employees. Its design focuses on reliable server management, secure user access, virtualization, cloud integration, storage, networking, and business continuity.

## Site Information

- **Organization:** PromisedLand.com
- **Project:** Secondary data center deployment
- **Location:** Space Center Executive Park
- **Address:** 601M Route 291, Suite 200, Independence, Missouri 64056
- **Facility size:** 15,000 square feet
- **Initial workforce:** 50 employees
- **Service area:** United States and Canada
- **Server platform:** Windows Server 2022

## Project Goals

The proposed facility would provide centralized management, secure access, virtualization, cloud support, organized networking, scalable storage, and reliable services for hybrid call center operations.

## Proposed Server Roles and Features

Windows Server 2022 will serve as the primary server operating system. The following roles and features are recommended:

- Active Directory Domain Services
- Group Policy Management
- DNS Server
- DHCP Server
- Hyper-V
- File and Storage Services
- Network Policy Server
- IP Address Management

Together, these services provide a centralized foundation for managing employees, computers, authentication, networking, and shared resources.

## Cloud Computing and Virtualization

PromisedLand.com should use virtualization to run multiple virtual machines on capable physical servers. Hyper-V Manager on Windows Server 2022 would support local and remote virtual machines for software testing, performance analysis, and changing business needs.

Virtualization reduces the need for separate physical machines. The proposal also recommends Microsoft Azure as part of a hybrid server model to extend storage and computing resources into the cloud.

## IP Address Management and Domain Controllers

IP Address Management can help administrators organize, assign, and track addresses. Domain controllers provide centralized authentication and directory information so account, policy, and computer changes can be applied consistently.

## Hardware and Software Requirements

The facility will require capable physical servers, racks, cabling, network equipment, storage, backup systems, power, cooling, and organized airflow. Careful planning will improve performance, reliability, and maintenance.

## DNS Implementation and Security

DNS allows users and applications to access services by name instead of long IP addresses. DNS Manager can maintain internal name resolution, while DNSSEC, cache locking, socket pooling, and related policies can strengthen security.

## Active Directory and Group Policy

Active Directory centralizes account information, authentication, and access control. Group Policy Objects can enforce password security, file access, Windows settings, user restrictions, and computer policies across the organization.

## Hybrid Server Management

Using Microsoft Azure alongside Windows Server 2022 would combine local infrastructure with cloud resources. PromisedLand.com should evaluate storage, compute, backup, identity, and security needs before selecting a pricing tier.

## Storage and File Services

Windows Server 2022 File and Storage Services can provide centralized file storage. Storage pools, virtual disks, Disk Management, thin provisioning, and mirrored storage can be used to organize capacity and improve flexibility or redundancy.

## Business Value

This design gives PromisedLand.com a structured way to support employees and hybrid call centers. Centralized identity, virtualization, cloud integration, organized networking, security policies, and storage planning create a foundation for growth.

## Conclusion

PromisedLand.com should move forward with a Windows Server 2022 data center supported by Active Directory, Group Policy, Hyper-V, DNS, DHCP, IPAM, file services, storage management, and Microsoft Azure integration.

Together, these technologies provide centralized administration, stronger security, flexible computing, organized storage, and dependable support for the company’s hybrid call center operations.

## What I Learned

This project helped me understand how much planning goes into a data center before the first server is installed. Hardware, operating systems, networking, storage, security, and cloud services all affect one another.

I learned how Windows Server roles such as Active Directory, DNS, DHCP, Hyper-V, and Group Policy can work together as one centralized management system. I also gained a better understanding of how virtualization and Azure can support flexibility without requiring every workload to run on separate physical hardware.

Most importantly, I learned to evaluate technology based on business needs. A good infrastructure plan should make work easier for employees, protect company information, support future growth, and remain manageable for IT staff. That way of thinking is something I can carry into future system administration, networking, and infrastructure projects.

## Project Information

- **Prepared for:** PromisedLand.com
- **Course:** IT 135-03P
- **Prepared by:** Christian Guerrero and Salcedo Tongco
- **Presented to:** Randy Burnham
- **Date:** July 2024
- **Location:** Independence, Missouri
