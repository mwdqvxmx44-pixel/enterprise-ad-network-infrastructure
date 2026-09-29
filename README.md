# Enterprise Active Directory & Multi-Site Network Topology

## Overview
Design and implementation of a 7-site enterprise network infrastructure and Active Directory domain (`letsgetstarted.local`) for a simulated enterprise environment.

## Key Architecture & Features
* **Multi-Site WAN Topology:** Connected Dallas HQ with 6 regional sites (Chicago, Atlanta, San Francisco, Austin, Seattle, Milwaukee) using firewalls and switches configured with MAC address binding port security.
* **Identity & Access Management:** Built domain hierarchy in Active Directory, automated bulk user provisioning with PowerShell, and configured GPOs for password enforcement and session timeouts[cite: 1].
* **Storage & File Security:** Configured role-based access control (RBAC) and granular NTFS permissions for executive data shares[cite: 1].
* **Disaster Recovery:** Formulated a high-availability DR strategy featuring multi-region data replication and automatic failover between Seattle and Atlanta data centers[cite: 1].

## Technologies Used
* **OS & Directory Services:** Windows Server (AD DS, DNS, DHCP, GPO), PowerShell[cite: 1]
* **Networking & Hardware:** Cisco Switches, Firewalls, Oracle VirtualBox[cite: 1]
* **Security & Database:** Role-Based Access Control (RBAC), Transparent Data Encryption (TDE)[cite: 1]
