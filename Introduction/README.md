## 🌩️ What Is Cloud Computing?

Cloud computing refers to using computing resources such as servers, storage, databases, networking, and software through the internet instead of owning physical hardware.

Rather than buying and maintaining servers on your own premises, cloud users access resources hosted on remote data centers. These resources are available on demand, and users are charged only for what they actually consume.
In simple words, cloud computing allows applications and data to run on online servers instead of local machines.
<img width="469" height="360" alt="image" src="https://github.com/user-attachments/assets/bac67230-78d2-4995-abfc-3a9e50af087f" /> <img width="1200" height="1087" alt="image" src="https://github.com/user-attachments/assets/596a86d9-ccbb-424f-9325-67102afdfd87" />

## ⭐ Key Features of Cloud Computing

<img width="1280" height="752" alt="image" src="https://github.com/user-attachments/assets/d7d27eed-8ac9-4286-b58e-680ebfb66371" /> <img width="1242" height="813" alt="image" src="https://github.com/user-attachments/assets/24d7b205-a4c3-4b2f-92fb-2a5a431d1e0a" />

# Scalability
Resources can be increased or reduced easily based on workload.

# Elasticity
Systems automatically adjust capacity when demand changes.

# High Availability
Services remain accessible with minimal downtime.

# Agility
Resources can be provisioned quickly within minutes.

# Fault Tolerance
Applications continue working even if a component fails.

# Disaster Recovery
Data and applications can be restored after failures or disasters.

# Pay-As-You-Go Pricing
Users pay only for the resources they use.

## ☁️ Cloud Service Models
<img width="1200" height="610" alt="image" src="https://github.com/user-attachments/assets/a41ba75a-8362-4528-a097-f23640cd7906" /> <img width="1320" height="978" alt="image" src="https://github.com/user-attachments/assets/e1345206-e638-4e2c-8cd8-e3e87840e6bd" />

# 🔹 Infrastructure as a Service (IaaS)

More control is given to the user

Cloud provider manages hardware and virtualization

User manages OS, applications, and data

Common use cases:

Virtual machines

Testing and development

Application migration

# Examples:

AWS EC2

# Azure Virtual Machines🔹 Infrastructure as a Service (IaaS)

More control is given to the user

Cloud provider manages hardware and virtualization

User manages OS, applications, and data

# Common use cases:

Virtual machines

Testing and development

Application migration

# Examples:

AWS EC2

Azure Virtual Machines

## 🔹 Platform as a Service (PaaS)

Responsibilities are shared

Provider manages OS, runtime, and infrastructure

User focuses only on application code

# Ideal for:

Application development

# Example:

Heroku

## 🔹 Software as a Service (SaaS)

Provider manages everything

Users access applications via browser

No installation required

# Examples:

Gmail

Outlook

Microsoft 365

OneDrive


## 🔐 Shared Responsibility Model

The shared responsibility model explains who is responsible for what in cloud security.

Cloud Provider → Infrastructure, physical security, and underlying services

Customer → Data, user access, configurations, and applications

# 📌 Responsibility depends on whether you use IaaS, PaaS, or SaaS.

# 🌍 Cloud Deployment Models

<img width="693" height="864" alt="image" src="https://github.com/user-attachments/assets/4ef61724-2257-4bed-b5de-ac9bc44368d6" /> <img width="1446" height="729" alt="image" src="https://github.com/user-attachments/assets/06366659-d33e-41e1-81aa-041ef68bb6b8" />

## Private Cloud

Dedicated environment

High security and control

Higher cost and maintenance

## Public Cloud

Fully managed by provider

Cost-effective

No infrastructure management

## Hybrid Cloud

Mix of private and public cloud

Sensitive data stays private

## Multi-Cloud

Uses multiple cloud providers

Avoids vendor lock-in

## 🔌 API (Application Programming Interface)

An API is a set of rules that allows software systems to communicate with each other.

In cloud environments, APIs enable users to interact with:

Compute services

Storage

Databases

AI and ML services

<img width="414" height="331" alt="image" src="https://github.com/user-attachments/assets/c6aecc97-2983-46c0-8832-fbd0d1b94b08" /> 

## 📈 Scaling in Cloud Computing
# Vertical Scaling

Increasing resource size

# Example: Adding more RAM or CPU to a VM

# Horizontal Scaling

Adding or removing instances

Common in high-traffic applications


<img width="1400" height="794" alt="image" src="https://github.com/user-attachments/assets/720f500c-a4aa-4895-a076-60a3f673cb5a" /> <img width="1632" height="1056" alt="image" src="https://github.com/user-attachments/assets/d4c7e913-befc-40a0-96f1-11f51fc31c99" />

## 🖥️ Virtualization

Virtualization allows multiple virtual machines to run on a single physical server.

Key benefits:

Better hardware utilization

Multiple OS on one machine

Cost efficiency

<img width="5000" height="2617" alt="image" src="https://github.com/user-attachments/assets/3c4a21a8-e079-4431-8e7b-5e165b09969a" />

<img width="768" height="378" alt="image" src="https://github.com/user-attachments/assets/4408c096-95db-4cd1-af28-19aabbded4dc" />


## ⚙️ Hypervisor

A hypervisor is software that:

Creates and manages virtual machines

Isolates multiple VMs on one host

Allows different OS to run simultaneously


<img width="348" height="145" alt="image" src="https://github.com/user-attachments/assets/595d168f-7f2b-45e1-9f3e-0a06de8cd759" />


<img width="801" height="550" alt="image" src="https://github.com/user-attachments/assets/af0916d7-a1e9-4ad0-95eb-28ce364f2659" />


## 📦 Containerization

Containerization is a lightweight alternative to virtualization, mainly used for microservices.

Key points:

Packages application with dependencies

Shares host OS kernel

Faster and lightweight

Solves “it works on my machine” issue

Best for:

Microservices

Scalable backend systems

⚠️ Containers cannot run a different OS kernel.

<img width="1238" height="662" alt="image" src="https://github.com/user-attachments/assets/b5818960-c8ce-4987-bce0-b04a5eb5a9a7" /> <img width="1225" height="501" alt="image" src="https://github.com/user-attachments/assets/149f9aaa-985b-4f95-a6ef-577c2b726893" />

## 🏢 Datacenters, Regions & Availability Zones

<img width="615" height="465" alt="image" src="https://github.com/user-attachments/assets/2d053e1a-6192-4ff5-9372-bcf449fc8e6f" /> <img width="615" height="465" alt="image" src="https://github.com/user-attachments/assets/5617b2dc-5b05-4847-9a23-f540024d2ff1" />


# Datacenter

A physical building that stores servers and networking equipment.

# Region

A geographical area containing multiple datacenters.

# Availability Zones

Isolated datacenters within a region

Ensure high availability and fault tolerance

## 🧩 Virtual Machines vs Containers


<img width="1238" height="662" alt="image" src="https://github.com/user-attachments/assets/61527f75-c4f1-432c-b3f1-b1b6b107a143" /> <img width="952" height="618" alt="image" src="https://github.com/user-attachments/assets/f205f527-16a1-489f-bc5c-36aab0375585" />

## 🖥️ Virtual Machines (VMs)

Each VM runs its own full operating system

Uses a hypervisor on top of physical hardware

More secure but heavier and slower

Requires more CPU, RAM, and storage

Best for:

Legacy applications

Strong isolation requirements

## 📦 Containers

Share the host operating system kernel

No separate OS for each application

Lightweight and fast

Starts in seconds

Best for:

Microservices architecture

High-scalability applications

## ✍️ Author: Lajpat Gautam


















