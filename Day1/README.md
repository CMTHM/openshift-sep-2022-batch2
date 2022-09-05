# Day1

## What is Hypervisor?
- is nothing but virtualization technology
- virtualization helps us run many OS side by side on the same machine
- Two types of Hypervisors
  1. Type1 - used in Servers/Workstations ( aka Bare Metal Hypervisor )
  2. Type2 - used in Laptops/Desktops
- Virtualization is a heavy-weight technology
   - because each Virtual Machine(VM) requires dedicated hardware resources
       - CPU Cores
       - RAM
       - Storage
 
## What is Container Engine?
- application virtualization technology
- container is nothing but an application process
- container engines let's us create and manage container with user-friendly commands
- container engines depends on other tools to manage images and containers
  - example: 
      1. Docker is a Container Engine but depends on runC Container Runtime to manage containers 
      2. Podman is a Container Engine but depends on CRI-O Container Runtime to manage containers
      
## What is Container Runtime?
- runC is a container runtime
- helps Container Engines to manage containers
   - creating a container
   - listing a container
   - modifying a container
   - deleting a container

## What is Container Orchestration Platform?
1. Docker SWARM
2. Google Kubernetes
3. Red Hat OpenShift
4. AWS Managed Kubernetes - EKS(Elastic Kubernetes Service )
5. Azure Managed Kubernetes - AKS ( Azure Kubernetes Service )
6. AWS Managed OpenShift - ROSA - Red Hat OpenShift on AWS
7. Azure Managed OpenShift - Red Hat OpenShift on Azure


