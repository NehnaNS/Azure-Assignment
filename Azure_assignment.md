##1. What are App Services and what are the different types of options available in App Services?

Azure App Service is a fully managed cloud platform provided by Microsoft Azure that allows developers to build, deploy, and host applications without managing servers. It supports multiple programming languages and provides features such as automatic scaling, security, monitoring, and continuous deployment.

The different types of App Service options are:

Web Apps – Used to host websites and web applications.
API Apps – Used to create and manage REST APIs.
WebJobs – Used to run background tasks and scheduled jobs.
Mobile Apps – Used to provide backend services for mobile applications.
Azure App Service helps developers focus on building applications while Azure handles the infrastructure and maintenance.


##2. Explain Cloud Availability Set and Availability Zones.

Availability Set and Availability Zones are Azure features that help improve the availability and reliability of applications.
An Availability Set is a logical grouping of virtual machines that distributes them across different fault domains and update domains. This ensures that if one server fails or undergoes maintenance, the other virtual machines continue to run, reducing downtime.
An Availability Zone is a physically separate datacenter within an Azure region. Each zone has its own power supply, cooling system, and networking infrastructure. By deploying resources across multiple availability zones, applications can continue operating even if an entire datacenter becomes unavailable.
In summary, Availability Sets protect against hardware failures within a datacenter, while Availability Zones protect against failures affecting an entire datacenter.

##3. What are the responsibilities of users when it comes to different cloud offerings like Infrastructure as a Service, Platform as a Service and Function as a Service and mention which Azure resource falls under each option?

Infrastructure as a Service (IaaS)
In IaaS, Azure provides the physical infrastructure, networking, and storage. The user is responsible for managing the operating system, applications, security settings, updates, and data.

Azure Resource: Azure Virtual Machines (VMs)

Platform as a Service (PaaS)
In PaaS, Azure manages the infrastructure, operating system, and runtime environment. Users are responsible for developing, deploying, and maintaining their applications and data.

Azure Resource: Azure App Service

Function as a Service (FaaS)
In FaaS, users only need to write and manage functions while Azure handles the infrastructure, scaling, and execution environment.

Azure Resource: Azure Functions


##4. In a brief paragraph, explain networking options available in Azure mentioning each service discussed in the class.

Azure provides various networking services that enable secure communication between resources. Azure Virtual Network (VNet) allows resources to communicate privately within Azure. Network Security Groups (NSGs) control inbound and outbound traffic through security rules. Azure Load Balancer distributes traffic across multiple servers to improve performance and availability. VPN Gateway provides secure connectivity between on-premises networks and Azure. Azure DNS offers domain name resolution services, while Azure Application Gateway provides advanced web traffic routing and load balancing. Together, these services help create secure, scalable, and reliable network infrastructures.

##5. What are storage accounts and the different options available to access storage accounts?

A Storage Account is an Azure service used to store and manage data in the cloud. It provides a secure and scalable location for storing different types of data and acts as a container for Azure storage services.

The different storage options include:

Blob Storage – Stores unstructured data such as images, videos, and documents.
File Storage – Provides shared file storage.
Queue Storage – Stores messages for communication between applications.
Table Storage – Stores structured NoSQL data.
Disk Storage – Provides storage for Azure Virtual Machines.
Storage accounts can be accessed through the Azure Portal, Azure Storage Explorer, Azure CLI, Azure PowerShell, and REST APIs.

##6. What are different options available to scale up and scale out Azure App Services?

Azure App Service provides two methods for handling increased workloads.

Scale Up (Vertical Scaling) involves increasing the resources of an existing instance, such as CPU, memory, and storage, by moving to a higher pricing tier. This improves the performance of a single instance.

Scale Out (Horizontal Scaling) involves increasing the number of application instances running simultaneously. Traffic is distributed among these instances, improving availability and allowing the application to handle more users.

Azure App Service supports both manual scaling and automatic scaling based on application demand.




