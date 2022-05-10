# Microsoft Azure Virtual Training Day1 基礎知識 (20220509)

## What is cloud computing ?
* Cloud Computing is the delivery of computing services over the internet, enabling faster innovation, flexible resources, and economies of scale.

## Public Cloud
* Owned by cloud services or hosting provider.
* Provides resources and services to multiple organizations and users.
* Accessed via secure network connection (typically over the internet).

## Private Cloud
* Organizations create a cloud environment in their datacenter.
* Organization is responsible for operating the services they provide.
* Does not provide access to users outside of the organization.

## Hybrid cloud
* Combines Public and Private cloud to allow applications to run in the most appropriate location.

## Cloud model comparison
### Public Cloud
* No capital expenditures to scale up.
* Appliactions can be quickly provisioned and deprovisioned.
* Organizations pay only for what they use.
### Private Cloud
* Hardware must be purchased for start-up and maintenance.
* Organizations have complete control over resources and security.
* Organizations are responsible for hardware maintenance and updates.
### Hybrid Cloud
* Provides the most flexiblity.
* Organizations determine where to run their applications.
* Organizations control security, compliance, or legal requiremnents.


## Cloud Benefits - Objective Domain
* Identify the benefits of cloud computing such as High Availability, Scalability, Elasticity, Agility, and Disaster Recovery.
* Identify the differences between Capital Expenditure (CapEx) and Operational Expenditure (OpEx).
* Describe the consumption-based model.

## Cloud Benefits
1. High Availability
2. Scalability
3. Global reach
4. Agility
5. Fault tolerance
6. Elasticity
7. Customer latency capability
8. Predictive cost considerations

## Compare CapEx vs. OpEx
### Capital Expenditure (CapEx)
* The up-front spending of money on physical infrastructure.
* Costs from CapEx have a value that reduces over time.
### Operational Expenditure (OpEx)
* The spending and billing of services or products as needed.
* Expense are deducted in the same year.

## Consumption-based model
Cloud service providers operate on a consumption-based model, which means that end users only pay for the resources that they use. Whatever they use is what they pay for.
* Better cost prediction
* Prices for individual resources and services are provided
* Billing is based on actual usage

## Cloud Services - Objective Domain
* Describe infrastructure-as-a-Service (IaaS)
* Describe Platform-as-a-Service (PaaS)
* Describe Software-as-a-Service (SaaS)
* Identify a service type based on a use case
* Describe the shared responsiblity model

## Infrastructure as a Service (IaaS)
* Build pay-as-you-go IT infrastructure by renting servers, virtual machines, storage, networks, and operating systems from a cloud provider.
![](https://i.imgur.com/2vcIIgK.png)

## Platform as a Service (PaaS)
* Provides environment for building, testing, and developing software applications; without focusing on managing underlying infrastructure.
![](https://i.imgur.com/2y79ETZ.png)

## Software as a Service (SaaS)
* Users connect to and use cloud-based apps over the internet: for example, Microsoft Office 365, email, and calendars.
![](https://i.imgur.com/PQBeMc4.png)

## Cloud Service comparison
### IaaS
* The most flexible cloud service.
* You configure and manage the hardware for your application.
* e.g. Virtual Machine
### PaaS
* Focus on application development.
* Platform management is handled by the cloud provider.
* e.g. Container
### SaaS
* Pay-as-you-go pricing model.
* Users pay for the software they use on a subscription model.
* e.g. Microsoft Office 365

## Shared responsibility model
![](https://i.imgur.com/hlfL54x.png)

## Regions
* Regions are made up of one or more datacenters in close proximity.
* Provide flexiblity and scale to reduce customer latency.
* Preserve data residency with a comprehensive compliance offering.

## Region Pairs
* At least 300 miles of separation between region pairs.
* Automatic replication for some services.
* Priortized region recovery in the event of outage.
* Updates are rollout sequentially to minimize downtime.

## Availability zones
* Provide protection against downtime due to datacenter failure.
* Physically separate datacenters within the same region.
* Each datacenter is equipped with independent power, cooling, and networking.
* Connected through private fiber-optic networks.
![](https://i.imgur.com/VeYusf3.png)
### Availability Options
![](https://i.imgur.com/SXNIqRu.png)

## Azure Resources
* Azure resources are components like storage, virtual machines, and networks that are available to build cloud solutions.
![](https://i.imgur.com/c0tVF0N.png)


## Resource group
A resource group is a container to manage and aggregate resources in a single unit.
* Resources can exist in only one resource group.
* Resources can exist in different regions.
* Resources can be moved to different resources groups.
* Applications can utilize multiple resource groups.
![](https://i.imgur.com/XUCO7hl.png)

## Azure Resource Manager
* The Azure Resouce Manager (ARM) provides a management layer that enables you to create, update, and delete resources in your Azure subscription.
![](https://i.imgur.com/s4xJIF7.png)

## Azure Subscroptions
An Azure subsription provides you with authenticated and authorized access to Azure accounts.
* Billing boundary: generate separate billing reports and invoices for each subscription.
* Access control boundary: manage and control access to the resources that users can provision with specific subscriptions.
![](https://i.imgur.com/MCeoc7e.png)

## Azure compute services
* Azure compute is an on-demand computing service that provides computing resources such as disks, processors, memory, networking, and operating systems.
![](https://i.imgur.com/9BgCgih.png)

## Azure virtual machine
* Azure Virtual Machine (VM) are software emulations of physical computers.
* Includes virtual processor, memory, storage, and networking.
* IaaS offering that provides total control and customization.

## Azure App Services
* Azure App Services is a fully maanged platform to build, deploy, and scale web apps and APIs quickly.
* Works with .NET, .NET Core, Node.js, Java, Python, or php.
* PaaS offering with enterprise-grade performance, security, and compliance requirements.

## Serverless Computing
### Azure Functions
* Event based code running your service and not the underlying infrastructure.
### Azure Logic Apps
* Automate and orchestrate編排 tasks, business processes, and workflows to integrate apps.
![](https://i.imgur.com/ORbdcOD.png)

## Azure Container Services
* Azure Containers are a light-weight, virtualized environment that does not require operating system management, and can respond to changes on demand.
### Azure Container Instances
* A PaaS offering that runs a container in Azure without the need to manage a virtual machine or additional services.
### Azure Kubernetes Service
* An orchestration service for containers with distributed atchitectures and large volumes of containers.

## Windows Virtual Desktop
* Windows Virtual Desktop is a desktop and app virtualization that runs in the cloud.
* Create a full desktop virtualization environment without having to run addtional gateway servers.
* Publish unlimited host pools to accommodate diverse workloads.
* Reduce costs with pooled, multi-session resources.
![](https://i.imgur.com/0PbHTGw.png)

## Azure networking services
### Azure Virtual Network (VNet)
* Enables Azure resources to communicate with each other, the internet, and on-premises networks.
![](https://i.imgur.com/jIpfLIe.png)
### Virtual Private Network Gateway (VPN)
* Used to send encrypted traffic between an Azure virtual network and an on-premises location over the public internet.
![](https://i.imgur.com/PD0KSXg.png)
### Azure Express Route
* Extends on-premises networks into Azure over a private connection that is facilitated by a connectivity provider.
![](https://i.imgur.com/uVmq9lp.png)


## Azure database services
### Azure Cosmos Database
* Is a globally-distributed database service that elastically and independently scales throughput and storage.
### Azure SQL Database
* Is a relational database as a service (DaaS) based on the latest stable version of the Microsoft SQL Server database engine.
### Azure Database for MySQL
* Is a fully-managed MySQL database service for app developers.
### Azure Database for PostgreSQL
* Is a relational database service based on the open-source Postgres database engine.


## Azure SQL Managed Instance
* Azure SQL Managed Instance allows existing SQL Server customers to lift and shift their on-premises applications to the cloud with minimal application and database changes.
* Fully managed and evergreen platform as a service.
* Preserves all PaaS capabilities (automatic patching and version updates, automated backups, and high availability)
* Exchange existing licenses for discounted rates on SQL Managed Instance using the Azure Hybrid Benefit
![](https://i.imgur.com/ASO7O7K.png)

## Explore Azure Marketplace
* Azure Marketplace allows customers to find, try, purchase, and provision applications and services from hundreds of leading service providers, which are all certified to run Azure.
* Open source container platforms.
* Virtual machine and database images.
* Application build and deployment software.
* Develop tools.
* And much more, with 10,000+ listings.


## Azure Internet of Things
* Internet of Things (IoT) is the ability for devices to gamer and then relay information for data analysis.
### Azure IoT Central
* Is a fully managed global IoT SaaS solution that makes it easy to connect, monitor, and manage IoT assets at scale.
### Azure IoT Hub
* Is a managed service hosted in the cloud that acts as a central message hub for bi-directional communication between IoT applications and the devices it manages.
### Azure Sphere
* Is a secured, high-level application platform with built-in communication and security features for internet-connected devices.


## Big data and analytics
### Azure Synapse Analytics
* A cloud-based Enterprise Data Warehouse.
![](https://i.imgur.com/7i00xjK.png)

### Azure HDInsight
* A fully-maanged, open-source analytics service for enterprises.
![](https://i.imgur.com/BXdL5IH.png)

### Azure Databricks
* Apache Spark based analytics service.
![](https://i.imgur.com/xtyMQLz.png)

## Artificial Intelligence & Machine Learning
### Azure Machine Learning
* Cloud-based to develop, train, and deploy machine learning models.
### Cognitive Services
* Quickly enable apps to see, hear, speak, understand, and interpret a user's needs.
### Azure Bot Service
* Develop intelligent, enterprise-grade bots.


## Develop your apps with DevOps and GitHub
### Azure DevOpes
* Development collaboration tools including pipelines, Kanban boards, and automated cloud-based load testing.
### Github
* Software development hosting with version control, source code management, and bug/task management.
### GitHub Actions for Azure
* Automate software workflow to build, test, and deploy from withing GitHub.
### Azure DevTest Labs
* Quickly create environments in Azure while minimizing waste and controlling cost.


## Azure Management Tools
![](https://i.imgur.com/7uPBQ6E.png)

## Azure Resource Manager (ARM) templates
* Azure Resource Manager (ARM) templates are JavaScript Object Notation (JSON) files that can be used to create and deploy Azure infrastructure without having to write programing commands.
* Declarative syntax
* Repeatable results
* Orchestration
* Modular files
* Built-in validation
* Exportable code
![](https://i.imgur.com/lnkeF3D.png)


## Azure Monitor
* Azure Monitor maximizes the availability and performance of applications and services by collecting, analyzing, and acting on telemetry from lcoud and on-premises environments.
* Application Insights
* Log Analytics
* Smart Alerts
* Automation Actions
* Customized Dashboards
![](https://i.imgur.com/H4dtX4R.png)
