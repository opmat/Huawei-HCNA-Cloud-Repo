This is a self-made resume written while studying the material for the **HCNA-BCCP Huawei Certified Network Associate-Building Cloud Computing Platform**

The official material can be found [here][a7c749f4]

  [a7c749f4]: http://support.huawei.com/learning/trainFaceDetailAction?lang=en&pbiPath=term1000025174&courseId=Node1000007639 "link to Huawei web"




## Certification Main Objetives

- Describe the basic concept and values of Cloud Computing
- Be familiar with the features and concept of virtual technologies
- Be familiar with the basic structure of Huawei Cloud Computing solution
- Describe the hardware structure of FusionCloud
- Be familiar with the software structure of FusionCloud
- Master the configuration of Huawei Cloud Computing hardware
- Master the configuration of Huawei Cloud Computing software
- Master the configuration of Huawei Cloud Computing service

## Index

  - OHC11081 Cloud Computing Concepts and Values
  - OHC11082 Virtualization Technology
  - OHC11083 Huawei FusionCloud Solutions
  - OHC11084 Huawei Cloud Computing Hardware System
  - OHC11085 FusionCompute Architecture
  - OHC11086 FusionManager Architecture Principles
  - OHC11087 FusionAccess Architecture Principles
  - OHC11088 FusionCloud Solution Deployment

# Cloud Computing Concepts and Values
Key characteristics of cloud computing are On-demand self-service, Location-independent resource pool (ubiquitous network access over the Internet), Pay per use, Elasticity.


Cloud computing is a Computing/Storage Network. It includes devices for data processing (servers), data storage and data communications (switches); and services for virtualization, scheduling and management, and the providing platform.

Other characteristics are low-cost servers, distributed software and automatic management.

Cloud computing is an integration of grid computing, distributed computing, parallel computing, network storage technologies, virtualization, load balancing, and other
traditional computer and network technologies.

Deployment methods: private (organizations), public (telecom carrier), community (shared infraestructure) and hybrid cloud.

##### Bussiness models:
  - infraestructure as a Service (IaaS).Processors, storage devices, networks.
  - Platform as a Service (PaaS). Application development platforms such as Java and .Net.
  - Software as a Service (SaaS). Applications wich run on cloud computing infraestructure. Such as CRM, ERP and OA.

##### Other concepts:
  - Web 1.0 is the idea of users obtaining in*formation through web browsers.
  - Web 2.0 works the idea of let the users be creators and authors on the internet.

##### Key technologies:
![Key technology](image1.jpeg)

- Servers, large memory and high [IOPS](https://en.wikipedia.org/wiki/IOPS).
- Storage devices, high IOPS, linked cloning, thin provisioning and snapshot functions.
- Switches, high-density and low-cost.
- VMs, virtualization software platform for resource pools.
- Distributed computing, scheduling and adjustment.
- Data center security.
- Management software, integrated and automatic.

Can be classified into three aspects: architecture, hardware, and software.
Architecture:
- Scale up (vertical expansion): Adds storage capacity to existing systems.
- Scale out (horizontal expansion): Adds nodes. Each node can provide storage, proccessing, and I/O bandwith.

Storage system:
- The distributed storage system consolidates low-cost and SATA hard disks on servers into storage resource pools.

Data center Networking:
- The service data flow (VMs) trend changes from vertical traffic to horizontal traffic.
- Development of [layer 2](https://en.wikipedia.org/wiki/Data_link_layer) network.

##### Benefits of cloud computing
The virtualization supports scalability of servers:
- Each server is virtualized into multiple VMs.
- VM specifications (CPU and memory) can be flexibly changed to increase or reduce the numbers of VM.
- Physical memory resources can be virtualized into more virtual memory resources.
- The expansion of servers can be implemented using the PXE or an ISO file.
- Cloud-based service systems employ batch VM deployment.
- - Resources can be deployed in large scale in short time.
- Resources can be dynamically expanded and shrunk.
- Less manual operations due to the automatic deployment.
- Deployments times changes from a month to minutes.

##### Data centralization for information security
- Data is transferred through HTTPS.
- System access requires certificates or accounts.
- Secure architecture and [VMM](https://en.wikipedia.org/wiki/Virtual_Machine_Manager) to isolate VMs from each other. Automatic security management.
- Trend Micro antivirus software.

##### Smart scheduling for energy saving
- Intelligent scheduling policies.
- Dynamic power management (DPM).

##### Reduced noise and power consumption
##### Efficient maintenance for cost reduction
##### Seamless switchover and mobile office
You can log in to the system desktop using various terminals at any time. The data and desktops uniformly run and are stored on the data center. The [Hot Swap](https://en.wikipedia.org/wiki/Hot_swapping) mode is supported for terminal replacement.

##### In-service upgrade and expansion
![upgrade](image2.jpeg)

##### Unified management
Huawei cloud solutions supports:
- The ability to manage physical servers, switches, and Huawei firewall devices (E1000 and E8000) in a unified manner.
- Mainstream servers and storage devices from other vendors.
- Both, Huawei Virtualization software FusionCompute and VMware.

##### cloud computing Application and examples
![cloud computing growth](image3.jpeg)

- Amazon EC2 supports VM leasing used in Linux and Windows, data processing, and storage leasing.
- Microsoft azure provides the VM development platform Visual Studio, which is based on Windows server and Linux systems.
- Alibaba cloud server, Elastic Compute Service (ECS).

##### Huawei Cloud Computing Solutions
Huawei FusionCloud solution is composed by four products:
  - FusionSphere. Cloud OS. Optimum cost effectiveness. Horizontal fusion.
  - FusionCube. Converged Appliance. Bussiness agility. Vertical Fusion.
  - FusionAccess. Desktop Cloud. Secure, efficient, user experience.
  - FusionInsight. Big data analysis. Easy-to-use, secure, reliable.

![Huawei desktop cloud case](image4.jpeg)

# Virtualization technology
Virtualization converts "physical" resources into "logical" resources.
- Zoning. Multiple VMs can run on the same physical server.
- Isolation. VMs on the same server are isolated from each other.
- Encapsulation. Each VM is saved in a file. You can migrate and copy the file in order to migrate and copy the VM.
- Hardware-independence. VMs can run on any server without requiring any modifications on servers.

Concepts: Host machine(physical), guest machine (virtualized), Guest Os and Host OS, Hypervisor(VMM).

Hosted vistualization:
