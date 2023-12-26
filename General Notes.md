NOTES:

- Consumption based - Pay as you go
- Not all Azure Regions currently support availability zones.  Availability zones are primarily for VMs, managed disks, load balancers and databases.
  
- Virtual networks, Azure Files, Azure VMs, - IaaS
- Azure SQL Databases, Azure App Service, Azure Web Apps service, Azure Kubernetes Service - PaaS
- 

- Governance hierarchy: Azure AD instance > Root Management Group > Management Groups > Subscriptions > Resource Groups > Resources
- Azure support plans: Basic, Developer, Standard, Professional Direct, Premier.
- 

- Resource lock is inherited down
- Tag is not inherited. It can be enforced using Azure Policy.
- Azure ID Connect, Azure ID Connect Cloud Sync - sync from on-premises Active Directory to AAD
- Zone redundant - spans through availability zones automatically.
- Regions, Availability Zones, Datacenters are physical concepts.
- Zonal service- created in specific availablity zone. To create resiliency I need to create another instance in different zone. Example: VM.
- Azure AD - 
