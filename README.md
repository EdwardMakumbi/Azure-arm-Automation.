# RandEnt Infrastructure Deployment – Azure ARM Template

## Project Overview
Automated deployment of Rand Enterprises’ infrastructure using Azure ARM templates.  
The goal was to deploy VMs, storage, and networking reliably, reproducibly, and securely, following the principle of least privilege.


## Architecture Summary
- ARM template provisions all resources (VNet, Subnets, VMs, Storage)
- Internal network used to access storage securely
- Role-based access control applied
- Reusable templates for future deployments


## Technologies Used
- Azure Resource Manager (ARM) Templates
- Virtual Network & Subnets
- Azure VMs
- Storage Accounts
- Azure Active Directory (for roles)
- Role-Based Access Control (RBAC)


## Deployment Process
See `deployment-notes/azure-arm-deployment.md`


## Security & Governance
- Least privilege applied
- Internal network connectivity to Storage
- RBAC ensures user permissions are strictly controlled


## Result / Impact
- Fully automated infrastructure provisioning
- Reduced manual errors
- Consistent, secure, and reusable deployments
- Demonstrated practical ARM and Azure network knowledge

## Architecture Diagram
See `diagrams/azure-arm-automation.svg`
