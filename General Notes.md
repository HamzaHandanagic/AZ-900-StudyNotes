NOTES:

- Consumption based - Pay as you go
- Not all Azure Regions currently support availability zones.  Availability zones are primarily for VMs, managed disks, load balancers and databases.
- Regions, Availability Zones, Datacenters are physical concepts.
- - Zonal service- created in specific availablity zone. To create resiliency I need to create another instance in different zone. Example: VM.
<hr>

- Virtual networks, Azure Files, Azure VMs, - IaaS
- Azure SQL Databases, Azure App Service, Azure Web Apps service, Azure Kubernetes Service - PaaS
- 

- Governance hierarchy: Azure AD instance > Root Management Group > Management Groups > Subscriptions > Resource Groups > Resources. Those are called scopes.
- Each Azure AD is given a single top-level management group called the root management group.
- Governance is inherited down.
- Governance constructs: RBAC (who), Policy (what ), Budget (how much), Resource Locks
- You can apply those constructs on Management Group level, Subscription Level or Resource Group Level
- Resource groups are not boundary of connectivity. It is possible to connect resources in two separate resource groups. Resources in resource group have common lifecycle.

- We want to create things using ARM JSON templates. Everything in Azure is stored in JSON.  We want to provision things using ARM templates because they are declarative.
- How to do it => IMPERATIVE. What is my desired end state => DECLARATIVE.
  
- A blueprint is composed of artifacts. Azure Blueprints currently supports the following resources as artifacts: Resource Groups, ARM template, Policy Assignment, Role Assignment.
- 
<hr>

- Resource lock is inherited down
- Tag is not inherited. It can be enforced using Azure Policy e.g: if resource is missing this tag go and copy it from resource group.
- Azure ID Connect, Azure ID Connect Cloud Sync - sync from on-premises Active Directory to AAD
- Zone redundant - spans through availability zones automatically.


- Azure AD - 
- Azure support plans: Basic, Developer, Standard, Professional Direct, Premier.
