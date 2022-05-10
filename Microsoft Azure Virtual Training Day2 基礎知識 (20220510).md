# Microsoft Azure Virtual Training Day2 基礎知識 (20220510)

## Azure Security Center
* Azure Security Center is a monitoring service that provides threat protection across both Azure and on-premises datacenters.
* Provides security recommendations
* Detect and block malware
* Analyze and identify potential attacks
* Just-in-time access control for ports
![](https://i.imgur.com/qJVAEw4.png)

## Azure Security Center - capabilities
1. Policy Compliance: Run policies across management groups, subscriptions, or tenants.
2. Continuous Assessments: Assess new and deployed resources to ensure that they are configure properly.
3. Tailored Recommendations: Recommendations based on existing workload with instructions on how to implement them.
4. Threat Protection: Anaylze attempted threats through alerts and impacted resource reports.

## Azure Sentinel
* Azure Sentinel is a security information management (SIEM) and security automated response (SOAR) solution that provides security analytics and threat intelligence across an enterprise.
* Connector and Integrations:
    * Office 365
    * Azure Active Director
    * Azure Advanced Threat Protection
    * Microsoft Cloud App Security


## Azure Key Vault
* Azure Key Vault stores application secrets in a centrailzed cloud location in order to securely control access premissions and access logging.
* Secrets management
* Key management
* Certificate management
* Storing secrets backed by hardware security modules (HSMs)
![](https://i.imgur.com/gfZ8wX0.png)


## Azure Dedicated Host
* Azure Dedicated Host provides physical servers that host one or more Azure virtual machines that is dedicated to a single organization's workload.
* Benefits:
    * Hardware isolation at the server level
    * Control over maintenance event timing
    * Aligned with Azure Hybrid Use Benefits
![](https://i.imgur.com/BjkLu4x.png)

## Defense in depth
* A layered approach to securing computer systems.
* Provides multiple levels of protection.
* Attacks against one layer are isolated from subsequent layers.
![](https://i.imgur.com/OTFs3X9.png)


## Shared Security
* Migrating from customer-controlled to cloud-based datacenters shifts the responsibility for security.
* Security becomes a shared concern between cloud providers and customers.
![](https://i.imgur.com/GEJmwQe.png)


## Network Security Groups (NSGs)
* Network Security Groups (NSGs) filter network traffic to and from Azure resources on Azure Virtual Networks.
* Set inbound and outbound rules to filter by source and destinition IP address, port, and protocol.
* Add multiple rules, as needed, within subscription limits.
* Azure applies default, baseline security rules to new NSGs.
* Override default rules with new, higher priority rules.
![](https://i.imgur.com/4j12quB.png)


## Azure Firewall
* A stateful, managed Firewall as a Service (FaaS) that grants.denies server access based on originating IP address, in order to protect network resources.
* Applies inbound and outbound traffic filtering rules
* Built-in high availabilty
* Unrestricted cloud scalability
* Uses Azure Monitor logging
* Azure Application Gateway also provides a firewall, Web Application Firewall (WAF). WAF provides centrailized, inbound for your web applications.
![](https://i.imgur.com/q1qxNvO.png)


## Azure Distributed Denial of Service (DDoS) protection
* DDoS attacks overwhelm and exhaust network resources, making apps slow or unresponsive.
* Sanitizes unwanted network traffic before it impacts service availability.
* Basic service tier is automatically enabled in Azure
* Standard service tier adds mitigation capabilities that are tuned to protect Azure Virtual Network resources.
![](https://i.imgur.com/HmHAaOW.png)

## Defense in Depth Reviewed
### Combining network security solutions
* NSGs with Azure Firewall to achieve defencse in depth.
* Perimeter layer protects your network boundaries with Azure DDoS Protection and Azure Firewall.
* Networking layer only permits traffic to pass between networked resources with Network Security Group (NSG) inbound and outbound rules.

## Compare Authentication and Authorization
### Authentication
* Identifies the person or service seeking access to a resource.
* Requests legitmate access credentials.
* Basic for creating secure identity and access control principles.
![](https://i.imgur.com/17DWt0e.png)

### Authorization
* Determines an authenticated person's or service's level of access.
* Defines which data they can access, and what they can do with it.
![](https://i.imgur.com/KMCxkOo.png)


## Azure Multi-Factor Authentication
* Privdes additional security for your identities by requiring two or more elements for full authentication.
* Something you know.
* Something you possess.
* Something you are.
![](https://i.imgur.com/hw3kA0x.png)


## Azure Active Directory (AAD)
* Azure Active Directory (AAD) is Microsoft Azure's cloud-based identity and access management service.
* Authntication (employees sign-in to access resources).
* Single sign-on (SSO).
* Application management.
* Business to Business (B2B).
* Business to Customer (B2C) identity services.
* Device management.


## Conditional Access
* Conditional Access is used by Azure Active Directoyr to bring signals together, to make decisions, and enforce organizational policies.
* User or Group Membership
* IP Location
* Device
* Application
* Risk Detection
![](https://i.imgur.com/YiJwzbX.png)


## Explore Role-based access control (RBAC)
* Fine-grained access maangement.
* Segregate duties within the team and grant only the amount of access to users that they need to perform their jobs.
* Enables access to the Azure portal and controlling access to resources.
![](https://i.imgur.com/ctK4xfv.png)


## Resource locks
* Protect your Azure resources from accidental deletion or modification.
* Manage locks at subscription, resource gorup, or individual resource levels within Azure Portal.
![](https://i.imgur.com/NPT13D9.png)


## Tags
* Privdes metadata for your Azure resources.
* Logically organizes resources into a taxonoy.
* Consists of a name-value pair.
* Very useful for rolling up billing information.
![](https://i.imgur.com/K37jozh.png)


## Azure Policy
* Azure Policy helps to enforce organizational standards and to assess compliance at -scale. Provides governance and resource consistency with regulatory compiance, security, cost, and management.
* Evaluates and identifies Azure resouces that do not comply with your policies.
* Provides built-in policy and initiative definitions, under categories such as Storage, Networking, Compute, Security Center, and Monitoring.
![](https://i.imgur.com/NZ2WoOo.png)


## Azure Blueprints
* Azure Blueprints makes it possible for development teams to rapidly build and stand up new environments. Development teams can quickly build trust through organizational compliance with a set og built-in components (such as networking) in order to speed up development and delivery.
    * Role Assignments
    * Policy Assignments
    * Azure Resources Manager Templates
    * Resource Groups
![](https://i.imgur.com/m8XdWbf.png)


## Cloud Adoption Framework
* The One Microsoft approach to cloud adoption in Azure.
* Best practices from Microsoft employees, partners, and customers.
* Tools, guidance, and narratives for strategies and outcomes.
![](https://i.imgur.com/palxowp.png)


## Security, Privacy, and Compliance
* Security: Secure by design. With built in intelligent security, Microsoft helps to protect against known and unknown cyberthreats, using automation and artificial intelligence.
* Privacy: We are committed to ensuring the privacy of organizations through our contractial agreements, and by providing user control and transparency.
* Compliance: We respect local laws and regulations and provide comprehensive coverage of compliance offerings.

## Compliance Terms and Requirements
* Microsoft provides the most comprehensive set of compliance offerings (including certifications and attestations) of any cloud service provider. Some compliance offerings include.
![](https://i.imgur.com/t8OhXMK.png)


## Microsoft privacy statement
* The Microsoft privacy statement provides openness and honesty about how Microsoft handles the user data collected from its products and services.
* The Microsoft privacy statement explains:
    * What data Microsoft processes.
    * How Microsoft processes it.
    * What purposes the data is used for.


## Trust Center
* Learn about security, privacy, compliance, policies, features, and practices across Microsoft's cloud products.
* The Trust Center website provides:
    * In-depth, expert information.
    * Curated lists of recommended resources, arranged by topic.
    * Role-specific information for business maangers, administrators, engineers, risk assessors, privacy officers, and legal teams.


## Azure Sovereign Region (US Government services)
* Meets the security and compliance needs of US federal agencies, state and local governments, and their solution providers.
* Azure Government:
    * Seperate instance of Azure.
    * Physically isolated from non-US government deployments.
    * Accessible only to screened, authorized personnel.
    * Example: FedRAMP, NIST 800.171 (DIB), ITAR, IRS 1075


## Azure Sovereign Region (Azure China)
* Microsoft is China's first foreign public cloud service provider, in compliance with government regulartions.
* Azure China features:
    * Physically separated instance of Azure cloud services operated by 21Vianet.-
    * All data stays with China to ensure compliance.

## Factors affecting costs
1. Resource Type
2. Services
3. Location
4. Bandwidth
5. Reserved Instances
6. Azure Hybrid Use Benefit

## Pricing Calculator
* The Pricing Calculator is a tool that helps you estimate the cost of Azure products. The options that you can configure in the Pricing Calculator vary between products, but basic configuration options include:
    * Region
    * Tier
    * Billing options
    * Support options
    * Programs and offers
    * Azure dev/test pricing
![](https://i.imgur.com/pDRWwTg.png)


## Total Cost of Ownership Calculator
* A tool to estimate cost savings you can realize by migrating to Azure.
* A report comapres the costs of on-premises infrastructures with the costs of using Azure products and services in the cloud.


## Azure Cost Management
* Reporting - billing reports
* Data enrichment
* Budgets - set spend budget
* Alerting - when cost exceed limits
* Recommendation - cost recommendations


## Minimizing Costs
![](https://i.imgur.com/PI89ciW.png)


## Service Level Agreements (SLAs)
* Service Level Agreements (SLAs) describles Microsoft's commitments for uptime and connectivity.
*  SLAs are based on individual products and services.
*  Detailede agreements on the service provided, and any expections to the SLA.
*  Freee and preview features/services do not off SLAs.
![](https://i.imgur.com/NCkHnjR.png)


## SLAs for Azure products and services
* Performance targets are expressed as uptime and connectivity gurantees.
* Performance-targets range from 99% to 99.999%.
* If a service fails to meet the guarantees, a percentage of the monthly service fees can becredited.
![](https://i.imgur.com/50dsxOK.png)


## Actions that affect SLAs
### Lower your SLA
* Adding more services
* Choosing free or non-SLA services
### Raise your SLA
* Availabilty Zones
* Redundant systems
#### Many factors can raise or lower your SLA. Design decisions based on business goals will drive your SLA goals.


## Azure Preview Program
* With Azure previews, users can test beta and other pre-release features, products, services, software, and regions to provide feedback.
* Public Preview: all Azure customers can evaluate the new features.
* Generally available (GA): after public preivew is completed, anll customers can use the feature, and region availability will vary.


## Monitoring service and feature updates
* Azure updates provides information about the Azure products, services, and features, in addition to product roadmaps and availability.
* View detials about all Azure updates and their status.
* Browse and search for updates.
* Subscribe to Azure update notifications by RSS.


