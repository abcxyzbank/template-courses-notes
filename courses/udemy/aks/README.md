# Azure Kubernetes Services

## Course content

### Section 1: Introduction

| S.No | Topic |
| ---- | ----- |
| 1    | Introduction about instructor and course |
| 2    | Good to have / Recommended background |
| 3    | Connect with me |

### Section 2: Understanding containers

| S.No | Topic                                               |
| ---- | --------------------------------------------------- |
| 4    | What is a container and how is it different from a VM? |
| 5    | Microservices architecture                          |
| 6    | What are Docker, Dockerfile and Docker Hub?         |
| 7    | Creating our first container app (web app), pushing it to Docker Hub and running |
| 8    | Create our 2nd container app (troubleshooting app), push it to DockerHub and run it |
| 9    | Understanding why we need a container orchestrator, like Kubernetes|
| 10   | Introduction to Kubernetes                 |
| 11   | Kubernetes architecture                    |
| 12   | Self-managed vs Cloud-managed Kubernetes cluster |

### Section 4: Starting with Azure Kubernetes Service (AKS)


| S.No | Topic                                                                 |
| ---- | --------------------------------------------------------------------- |
| 13   | What is Azure Kubernetes Service (AKS)?                                |
| 14   | Azure pricing, free account and AKS cost                              |
| 15   | Considerations for saving cost on AKS                                 |
| 16   | Login to Azure and set the subscription                               |
| 17   | Let's create our first AKS cluster                                    |
| 18   | Install CLI, explore Azure Cloud Shell, connect to the cluster        |
| 19   | aks-preview extension and feature registration                        |
| 20   | Making our life easier with autocompletion, alias, Kubernetes and AKS extension |
| 21   | PowerShell Basics in AKS - Connect to Azure, AKS creation, completion, aliases |
| 22   | Imperative and declarative approaches                                 |
| 23   | Practice with Nodes, Pod, Deployment, Replicaset, DaemonSet, Service, Secret, CM |
| 24   | Understanding our CIDs                                                |
| 25   | What is a node pool?                                                  |
| 26   | Connect to AKS nodes - quick demo                                     |
| 27   | Exploring the AKS cluster - Kubernetes side                           |
| 28   | kubelet                                                               |
| 29   | containerd                                                            |
| 30   | azure-ip-masq-agent                                                   |
| 31   | cloud-node-manager                                                    |
| 32   | coredns                                                               |
| 33   | coredns-autoscaler                                                    |
| 34   | CSI                                                                   |
| 35   | konnectivity                                                          |
| 36   | kube-proxy                                                            |
| 37   | metrics-server                                                        |
| 38   | Exploring the AKS cluster - Azure infrastructure side                 |
| 39   | Virtual Machine Scale Set (VMSS)                                      |
| 40   | Virtual Network (VNET) and Subnet (SNET)                              |
| 41   | Network Security Group (NSG)                                          |
| 42   | Route Table (RT)                                                      |
| 43   | Load Balancer (LB) and Public IP (PIP)                                |
| 44   | Managed Identity (MI)                                                 |
| 45   | Important notes about AKS support policy                              |
| 46   | Avoid this common mistake in AKS with the NRGLockdown feature         |
| 47   | Stop and Start feature                                                |
| 48   | About kubeconfig and how to work with multiple AKS clusters           |
| 49   | Deploy and manage a Kubernetes application (Extension) from Azure Marketplace |
| 50   | Install kubectl plugins with krew                                     |


### Section 5: Working with node pools and nodes

| S.No | Topic                                                                                          |
| ---- | ---------------------------------------------------------------------------------------------- |
| 51   | VM types: VMSS (Scale Set) vs VMAS (Availability Set)                                          |
| 52   | Understanding System and User node pool types                                                  |
| 53   | Connect to AKS nodes - using helper pod                                                         |
| 54   | Connect to AKS nodes - via SSH using Azure Bastion                                              |
| 55   | Connect to AKS nodes - via SSH using a pod                                                      |
| 56   | Connect to AKS nodes - run-command invoke                                                       |
| 57   | Node's Operating Systems is AKS                                                                 |
| 58   | Node pool with AzureLinux (Mariner) OS                                                          |
| 59   | Create Windows node pool and connect to nodes                                                   |
| 60   | Schedule pods on specific node pools or specific OS type nodes                                  |
| 61   | Customize node configuration using az aks parameters                                            |
| 62   | Customize node configuration using DaemonSet                                                    |
| 63   | OS disk types                                                                                  |
| 64   | Default OS disk size                                                                           |
| 65   | Spot node pools                                                                                |
| 66   | GPU node pools                                                                                 |
| 67   | Node pool snapshot                                                                             |
| 68   | Resize a node pool                                                                              |

### Section 6: Networking in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 69   | Kubenet network plugin                                                                         |
| 70   | Azure CNI network plugin                                                                       |
| 71   | Azure CNI overlay network plugin                                                               |
| 72   | Network plugins comparison                                                                     |
| 73   | Bring your own VNET/subnet, NSG and Route Table in AKS                                           |
| 74   | A deeper look into LoadBalancer Service in AKS                                                  |
| 75   | Consideration when multiple NSGs are used                                                       |
| 76   | Kubernetes Internal Load Balance                                                               |
| 77   | Use an Azure Private Link service to connect to an internal load balancer                       |
| 78   | Understand VET Peering                                                                         |
| 79   | SNAT in Azure                                                                                  |
| 80   | Outbound types: Load Balancer, NAT Gateway and UserDefinedRouting (UDR)                         |
| 81   | Create AKS with NAT Gateway                                                                    |
| 82   | Create AKS with UDR and Azure Firewall                                                          |
| 83   | Learn how AKS works with HTTP Proxy                                                            |
| 84   | Install mitmproxy on a VM                                                                      |
| 85   | Deploy an AKS cluster with HTTP Proxy                                                          |
| 86   | Explore, update, and troubleshoot AKS with HTTP Proxy                                           |

### Section 7: Types of clusters in relation to control plane access

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 87   | Types of clusters in relation to control plane access                                            |
| 88   | Explore public AKS cluster                                                                     |
| 89   | Create public AKS cluster with VET integration                                                  |
| 90   | API server authorized IP ranges                                                                 |
| 91   | Create and connect to general and VET integration private AKS cluster                            |
| 92   | az aks invoke command                                                                           |
| 93   | Run kubectl commands from worker nodes                                                          |

### Section 8: AKS-managed Microsoft EntraID (previously known as AAD)

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 94   | Clarification about the rebranding of Active Directory to Microsoft Entra imin                 |
| 95   | Understanding AKS-managed AAC integration with Azure RBAC and Kubernetes.                       |
| 96   | Prepare the environment for Azure RBAC                                                          |
| 97   | Practice Azure RBAC                                                                             |
| 98   | Use custom role with Azure RBAC                                                                 |
| 99   | Prepare the environment for Kubernetes RBAC                                                     |
| 100  | Practice Kubernetes RBAC                                                                        |
| 101  | Local accounts                                                                                  |

### Section 9: Security and identities in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 103  | Create an AKS cluster with service principal                                                    |
| 104  | Certificate rotation                                                                            |
| 105  | Network policies in AKS                                                                         |
| 106  | Azure Key Vault Provider for Secrets Stori ASTDrive                                             |
| 107  | Use autorotation for Azure Key Vault                                                            |
| 108  | Azure Policy for Kubernetes                                                                     |
| 109  | Microsoft Defender for Containers in AKS                                                        |
| 110  | AppArmor in AKS                                                                                 |
| 111  | Seccomp in AKS                                                                                  |
| 112  | Use Image Cleaner (Eraser) in AKS                                                               |

### Section 10: Scaling in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 113  | Understand resource reservations                                                                |
| 114  | Manually scale pod replicas and node                                                            |
| 115  | Stop/deallocate nodes with Scale-dowr                                                           |
| 116  | Horizontal Pod Autoscaler (HPA                                                                  |
| 117  | Vertical Pod Autoscaler (VPA)                                                                   |
| 118  | Cluster Autoscaler (CAS                                                                        |
| 119  | Virtual nodes add-on for AKS                                                                    |
| 120  | KEDA in AKS                                                                                     |

### Section 11: Storage in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 121  | Exploring the storage options in AKS                                                            |
| 122  | Dynamically create Azure Disk                                                                   |
| 123  | Create snapshot and restore Azure Disk                                                          |
| 124  | Resize Azure Disk                                                                               |
| 125  | Statically create Azure File                                                                    |
| 126  | Use a custom StorageClass to create AzureFile with private endpoint and GRS                     |
| 127  | Use a StatefulSet to dynamically create Azure Blob                                               |
| 128  | Understand Azure NetApp Files and Astra Trident                                                 |
| 129  | Dynamically create Azure NetApp Files with Astra Trident in AKS                                  |
| 130  | Expand / resize an Azure NetApp Files volume                                                    |

### Section 12: Monitor and troubleshoot

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 131  | Activity logs                                                                                   |
| 132  | Diagnose and solve problems and Ask Genie                                                       |
| 133  | Resource Health and Azure Status                                                                |
| 134  | Azure Advisor                                                                                   |
| 135  | Metrics explorer for AKS                                                                        |
| 136  | Metrics explorer for AKS related resources                                                      |
| 137  | Azure Monitor with Container Insights in AKS                                                    |
| 138  | Explore Insights                                                                                |
| 139  | Explore Workbooks                                                                               |
| 140  | Explore Logs                                                                                    |
| 141  | Understanding Alerts                                                                            |
| 142  | Create out-of-the-box Alert                                                                     |
| 143  | Create custom Alert                                                                             |
| 144  | Diagnostics settings in AKS                                                                     |
| 145  | Monitor AKS with managed Prometheus and Grafana                                                 |
| 146  | Understand and capture TCPDump on Linux node and collect it locally                             |
| 147  | Capture TCPDump on Linux node with autorotation and store it in a file share                     |
| 148  | Capture TCPDump on Linux pod with Mariner OS and collect it locally                             |
| 149  | Add a TCPDump sidecar container to a pod                                                        |

### Section 13: Upgrade an AKS cluster

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 150  | Understanding K8s version, node image, the upgrade and why we need to upgrade                  |
| 151  | Auto-upgrade Feature                                                                            |
| 152  | Planned Maintenance Feature                                                                     |
| 153  | What to check to prevent an upgrade failure                                                     |
| 154  | Performing a Kubernetes version upgrade - All at once                                           |
| 155  | Performing a Kubernetes version upgrade - Blue green                                             |
| 156  | Performing a node image upgrade                                                                 |

### Section 14: Integrate AKS with Azure Container Registry (ACR)

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 157  | What is Azure Container Registry (ACR) and how the integration works?                           |
| 158  | Create ACR and push/import our apps to it                                                       |
| 159  | Integrate AKS and ACR - Azure/RBAC method                                                       |
| 160  | Integrate AKS and ACR - Kubernetes/pull secret method                                           |
| 161  | Securely connect to ACR via a private connection                                                |

### Section 15: Ingress controllers in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 162  | What is an ingress controller?                                                                  |
| 163  | Using Application Gateway Ingress Controller (AGIC)                                             |
| 164  | Expose apps using a domain name on HTTPS                                                        |
| 165  | Using nginx-ingress-controller in AKS                                                           |
| 166  | Expose App on HTTPS with Cert-Manager and Let's Encrypt                                         |
| 167  | Use multiple ingress controllers in the same AKS cluster                                        |

### Section 16: Gateway API and Application Gateway for Containers

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 168  | Gateway API basics                                                                             |
| 169  | What is Application Gateway for Containers?                                                     |
| 170  | Using Application Gateway for Containers (including Gateway API and Ingress API)                |

### Section 17: High Availability in AKS

| S.No | Topic                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------- |
| 171  | Free and Standard tiers for AKS cluster management                                              |
| 172  | Availability Zones in AKS                                                                      |
| 173  | Use Azure Front Door to route traffic between multiple AKS clusters                             |
| 174  | Use custom domain and Azure Front Door certificate to expose apps in AKS                        |

### Section 18: Deploy to AKS using AzureDevOps

| S.No | Topic                                                                 |
| ---- | --------------------------------------------------------------------- |
| 175  | Initial setup: Create a project, a service connection, add files, create ACR+AKS |
| 176  | Example 1: Use a pre configured Pipeline to build/push to ACR and deploy to AKS |
| 177  | Example 2: Use a Pipeline configured by us to build/push to ACR, deploy to AKS |
| 178  | Example 3: Use a Pipeline to run kubectl commands against our AKS cluster |
| 179  | Setup a self-hosted agent and use it to deploy to ACR and AKS           |

### Section 19: Bonus Lecture

Thank you for actively participating in my course and showing dedication to learning. Your commitment is truly commendable.

As a token of appreciation, I would like to offer you a special opportunity. You can use the following link to access other courses at a discounted price. Keep up the great work and continue your educational journey!

Azure Kubernetes Service (AKS) Made Easy: A Comprehensive and Practical Course

OpenShift 4 and Azure Red Hat OpenShift (ARO) Made Easy

Azure Container Instances (ACI): A Complete Guide

Azure Container Registry (ACR): A Complete Guide

Application Gateway Ingress Controller (AGIC) Made Easy

Azure Application Gateway for Containers (with Gateway API)
Refs:


## Azure Services Covered

| S.No | Azure Service Name |
| -----| ------------------ |
| 01.  | Azure AKS  |
| 02.  | Azure Disks  |
| 03.  | Azure Files  |
| 04.  | Azure MySQL Database  |
| 05.  | Azure Storage Accounts  |
| 06.  | Azure Cloud Shell  |
| 07.  | Azure Load Balancer  |
| 08.  | Azure DNS Zones  |
| 09.  | Azure Container Registries ACR  |
| 10.  | Azure Container Registries ACR with Azure Service Principal |
| 11.  | Azure DevOps - Build Pipelines with ACR & Github Repositories |
| 12.  | Azure DevOps - Release Pipelines with AKS|
| 13.  | Azure Public IP Address|
| 14.  | Azure Standard Load Balancer|
| 15.  | Azure Virtual Networks|
| 16.  | Azure Active Directory|
| 17.  | Azure Container Instances - Virtual Nodes|
| 18.  | Azure AKS Windows and Linux User NodePools|
| 19.  | Azure Managed Service Identity - MSI|
| 20.  | Azure Virtual Machine Scale Sets|
| 21.  | Azure Log Analytics Workspaces for Azure Monitor|

## Kubernetes Concepts Covered

| S.No | Kubernetes Concept Name |
| ---- | ------------------- |
| 1.   | Kubernetes Architecture  |
| 2.   | Pods  |
| 3.   | ReplicaSets  |
| 4.   | Deployments  |
| 5.   | Services - Load Balancer Service  |
| 6.   | Services - Cluster IP Service  |
| 7.   | Services - External Name Service  |
| 8.   | Services - Ingress Service  |
| 9.   | Services - Ingress SSL & SSL Redirect  |
| 10.  | Services - Ingress & External DNS  |
| 11.  | Services - Domain Name based Routing  |
| 12.  | Imperative - with kubectl  |
| 13.  | Declarative - Declarative with YAML  |
| 14.  | Secrets |
| 15.  | Init Containers |
| 16.  | Requests & Limits |
| 17.  | Namespaces - Imperative |
| 18.  | Namespaces - Limit Range |
| 19.  | Namespaces - Resource Quota |
| 20.  | Storage Classes |
| 21.  | Persistent Volumes |
| 22.  | Persistent Volume Claims |
| 23.  | Services - Load Balancers |
| 24.  | Annotations |
| 25.  | HPA - Horizontal Pod Autoscaler |
| 26.  | CA - Cluster Autoscaler |
| 27.  | Config Maps |
| 28.  | RBAC - Role & Role Bindings |
| 29.  | RBAC - Cluster Role & Cluster Role Bindings |
| 30.  | Virtual Kubelet |
| 31.  | Secrets - Image Pull Secrets |

## List of Docker Images  on Docker Hub

| Application Name  | Docker Image Name |
| ----------------- | ----------------- |
| Simple Nginx V1  | amediowebservices/kubenginx:1.0.0  |
| Spring Boot Hello World API  | amediowebservices/kube-helloworld:1.0.0  |
| Simple Nginx V2  | amediowebservices/kubenginx:2.0.0  |
| Simple Nginx V3  | amediowebservices/kubenginx:3.0.0  |
| Simple Nginx V4  | amediowebservices/kubenginx:4.0.0  |
| Backend Application  | amediowebservices/kube-helloworld:1.0.0  |
| Frontend Application  | amediowebservices/kube-frontend-nginx:1.0.0  |
| Kube Nginx App1  | amediowebservices/kube-nginxapp1:1.0.0  |
| Kube Nginx App2  | amediowebservices/kube-nginxapp2:1.0.0  |
| User Management Web Application  | amediowebservices/kube-usermgmt-webapp:1.0.0-MySQLDB  |

## List of Docker Images you build in Azure Container Registry

## List of Docker Images you build in GitHub Container Registry

## List of Docker Images you build in GitLab Container Registry

## What will students learn in your course?

The code block provides a summary of what students will learn in the course "Azure Kubernetes Services (AKS) Made Easy". The course covers various topics including building Azure AKS production-grade clusters, using Terraform for provisioning AKS clusters, implementing DevOps concepts with Azure DevOps, learning Kubernetes fundamentals, writing and deploying Kubernetes manifests, working with Azure services in combination with AKS, enabling autoscaling features, mastering kubectl commands, integrating AKS with Azure Active Directory, and understanding Kubernetes RBAC concepts.

## Are there any course requirements or prerequisites?

- To follow along with the hands-on activities, you will need an Azure Cloud account.
- No prior knowledge of Docker or Kubernetes is required to start this course.

## Who are your target students?

- This section of the README file specifies the target students for the course.
- It provides information about the intended audience and who would benefit the most from taking the course.

## Target Audience

This course is designed for the following individuals:

- Azure Architects or Sysadmins or Developers who are planning to master Azure Kubernetes Service (AKS) for running applications on Kubernetes.
- Beginners who are interested in learning Kubernetes on the cloud using Azure AKS.
- Beginners who are interested in learning Azure DevOps and Terraform to provision Azure Kubernetes Clusters.

## Github Repositories used for this course

## Profiles

- [GitHub](https://www.github.com)
- [X](https://twitter.com)
- [Linkedin](https://www.linkedin.com/)
