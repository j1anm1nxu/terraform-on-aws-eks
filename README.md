# [Terraform on AWS EKS Kubernetes IaC](https://links.stacksimplify.com/terraform-on-aws-eks-kubernetes-iac-sre)

## [Root of Contents](./)

<!-- 
[![Image](https://stacksimplify.com/course-images/terraform-on-aws-eks-kubernetes.png "Terraform on AWS EKS Kubernetes IaC SRE- 50 Real-World Demos ")](https://links.stacksimplify.com/terraform-on-aws-eks-kubernetes-iac-sre)
-->

<!-- ## Course Modules -->
## Table of Contents
01. [Infrastructure as Code (IaC)](01-Infrastructure-as-Code-IaC-Basics/README.md)
2.  Terraform Install Tools, Command and Language Basics
    - [Tools](02-Terraform-Basics/02-01-Install-Tools-TerraformCLI-AWSCLI-VSCodeIDE/README.md)
    - [Command](02-Terraform-Basics/02-02-Terraform-Command-Basics/README.md)
    - [Language](02-Terraform-Basics/02-03-Terraform-Language-Syntax/README.md)
3.  [Terraform Settings, Providers and Resources](03-Terraform-Settings-Providers-Resources/README.md)
4.  [Terraform Input Variables, Output Values, Datasources](04-Terraform-Variables-and-Datasources/README.md)
5.  Terraform Loops, MetaArguments, Splat Operator and Functions
    - [Terraform For Loops, Lists, Maps and Count Meta-Argument](05-Terraform-Loops-MetaArguments-SplatOperator/05-01-MetaArgument-Count-For-Loops-Lists-Maps/README.md)
    - [Terraform for_each Meta-Argument with Functions toset, tomap](05-Terraform-Loops-MetaArguments-SplatOperator/05-02-MetaArgument-for_each/README.md)
    - [Terraform Small Utility Project](05-Terraform-Loops-MetaArguments-SplatOperator/05-03-Utility-Project/README.md)
    - [Meta-Argument for_each with AZ Instance Type Check](05-Terraform-Loops-MetaArguments-SplatOperator/05-04-for_each-with-az-instancetype-check/README.md)
6.  AWS VPC 3-Tier Architecture Design using Terraform
    - [AWS VPC 3-Tier Architecture Design using Terraform](06-AWS-VPC/06-01-AWS-VPC-using-Mgmt-Console/README.md)
    - [AWS VPC 3-Tier Architecture Design using Terraform](06-AWS-VPC/06-02-AWS-VPC-using-Terraform/README.md)
7.  [Bastion Host AWS EC2 Instances, Security Groups, TF Provisioners with Terraform](07-AWS-EC2-BastionHos/README.md) 
8.  [AWS EKS Cluster, Public and Private Node Groups using Terraform](08-AWS-EKS-Cluster-Basics/README.md)
    - [01-ekscluster-terraform-manifest](08-AWS-EKS-Cluster-Basics/01-ekscluster-terraform-manifests)
9.  [Kubernetes Fundamentals](09-Kubernetes-Fundamentals/README.md)
10. [Kubernetes Deployment and Service using YAML](10-Kubernetes-Deployment-and-Service/README.md)
    - [kube-manifests](10-Kubernetes-Deployment-and-Service/kube-manifests)
11. [Terraform Kubernetes Provider - Kubernetes Deployment & Service](11-Kubernetes-Resources-via-Terraform/README.md)
    - [11-Kubernetes-Resources-via-Terraform](11-Kubernetes-Resources-via-Terraform/02-k8sresources-terraform-manifests)
12. [Terraform Remote State Storage - AWS S3 & DynamoDB](12-Terraform-Remote-State-Storage/README.md)
    - [01-ekscluster-terraform-manifests](12-Terraform-Remote-State-Storage/01-ekscluster-terraform-manifests)
    - [02-k8sresources-terraform-manifests](12-Terraform-Remote-State-Storage/02-k8sresources-terraform-manifests)
13. [AWS EKS IAM Roles for Service Accounts (IRSA) using Terraform](13-EKS-IRSA/README.md)
    - [01-ekscluster-terraform-manifests](13-EKS-IRSA/01-ekscluster-terraform-manifests)
    - [02-eks-irsa-demo-terraform-manifests](13-EKS-IRSA/02-eks-irsa-demo-terraform-manifests)
14. [AWS EKS EBS CSI Driver Install with Self-Managed AddOn Option using Terraform](14-EBS-CSI-Install-Kubernetes-Storage/README.md)
    - [01-ekscluster-terraform-manifests](14-EBS-CSI-Install-Kubernetes-Storage/01-ekscluster-terraform-manifests)
    - [02-ebs-terraform-manifests](14-EBS-CSI-Install-Kubernetes-Storage/02-ebs-terraform-manifests)
    - [other-files-for-review](14-EBS-CSI-Install-Kubernetes-Storage/other-files-for-review)
15. [AWS EKS EBS Demo using k8s YAML  (UserMgmt WebApp with MySQL DB)](15-EBS-Kubernetes-SampleApp-YAML/README.md)
    - [01-ekscluster-terraform-manifests](15-EBS-Kubernetes-SampleApp-YAML/01-ekscluster-terraform-manifests)
    - [02-ebs-terraform-manifests](15-EBS-Kubernetes-SampleApp-YAML/02-ebs-terraform-manifests)
    - [03-kube-manifests-UMS-WebApp](15-EBS-Kubernetes-SampleApp-YAML/03-kube-manifests-UMS-WebApp)
16. AWS EKS EBS Demo using k8s Terraform  (UserMgmt WebApp with MySQL DB)
17. AWS EKS EBS Volumes Retain and Resize Settings
18.  AWS EBS CSI EKS Add-On
19. Provision AWS IAM Admin User as EKS Admin
20. Provision AWS IAM Basic User as EKS Admin
21. Provision of AWS Users (Admin & Basic) as EKS Admins using Terraform
22. Provision EKS Admins using IAM Roles & IAM Groups
23. Provision EKS Admins using IAM Roles & IAM Groups using Terraform
24. Provision EKS ReadOnly User using IAM Roles, Groups & k8s CR, CRB
25. Provision EKS Developer Users using IAM Roles, Groups & k8s R, RB
26. AWS Load Balancer Controller Install using Terraform Helm Provider
27. Ingress Basics - Automate with Terraform
28. Ingress Context Path based Routing - Automate with Terraform
29. Ingress SSL and SSL Redirect - Automate with Terraform
30. Install ExternalDNS using Terraform Helm Provider
31. Ingress with ExternalDNS - Automate with Terraform
32. Kubernetes LB Service with ExternalDNS - Automate with Terraform
33. Ingress Name based Virtual Host Routing- Automate with Terraform
34. Ingress SSL Discovery Host
35. Ingress SSL Discovery TLS
36. Ingress Groups - Automate with Terraform
37. Ingress Target Type IP - Automate with Terraform
38. Ingress Internal Load Balancer - Automate with Terraform
39. Ingress Cross Namespaces - Automate with Terraform
40. AWS Network Load Balancer with AWS Load Balancer Controller
41. AWS NLB TLS, External DNS with AWS LBC - Automate with Terraform
42. AWS NLB Internal LB with AWS LBC - Automate with Terraform
43. AWS EKS Fargate Profiles using Terraform
44. Run EKS Workloads on AWS Fargate - Automate with Terraform
45. AWS Fargate Only EKS Cluster using Terraform
46. AWS EFS CSI Controller Install using Terraform Helm Provider
47. AWS EFS Static Provisioning - Automate with Terraform
48. AWS EFS Dynamic Provisioning - Automate with Terraform
49. AWS EFS File System Mount for Fargate Workloads 
50. Kubernetes Cluster Autoscaler Controller Install 
51. Kubernetes Cluster Autoscaler Controller Test
52. Kubernetes Horizontal Pod Autoscaling with Terraform
53. Kubernetes Vertical Pod Autoscaling with Terraform
54. AWS EKS Monitoring and Logging with kubectl
55. AWS EKS Monitoring and Logging with Terraform



## Kubernetes Concepts Covered
01. Kubernetes Deployments
02. Kubernetes Pods
03. Kubernetes Service of Type LoadBalancer
04. Kubernetes Service of Type ClusterIP
05. Kubernetes Ingress Service
06. Kubernetes Ingress Class
07. Kubernetes Storage Class
08. Kubernetes Storage Persistent Volume
09. Kubernetes Storage Persistent Volume Claim
10. Kubernetes RBAC
11. Kubernetes Role
12. Kubernetes Role Binding
13. Kubernetes Cluster Role 
14. Kubernetes Cluster Role Binding
15. Kubernetes Cluster Autoscaler
16. Kubernetes Vertical Pod Autoscaler
17. Kubernetes Horizontal Pod Autoscaler
18. Kubernetes DaemonSets
19. Kubernetes Namespaces
20. Kubernetes Service Accounts
21. Kubernetes Groups
22. Kubernetes ConfigMaps
23. Kubernetes Requests and Limits
24. Kubernetes Worker Nodes


## Terraform Concepts covered
01. Settings Block
02. Providers Block
03. Multiple Providers usage
04. Dependency Lock File Importance
05. Resources Syntax and Behavior
06. Resources Meta-Argument - depends_on
07. Resources Meta-Argument - count
08. Resources Meta-Argument - for_each
09. Resources Meta-Argument - lifecycle
10. Input Variables - Basics
11. Input Variables - Assign When Prompted
12. Input Variables - Assign with terraform.tfvars
13. Input Variables - Assign with auto tfvars
14. Input Variables - Lists
15. Input Variables - Maps
16. File Function
17. Output Values
18. Local Values
19. Datasources
20. Backends - Remote State Storage
21. File Provisioner
22. remote-exec Provisioner
23. local-exec Provisioner
24. Null Resource
25. Modules from Public Registry
26. element function
27. Remote State Datasource
28. Terraform Datasources

## Terraform Providers used
1. AWS Terraform Provider
2. Kubernetes Terraform Provider
3. Kubectl Terraform Provider
4. HTTP Terraform Provider
5. Null Terraform Provider
6. Helm Terraform Provider



## What will students learn in your course?
- You will learn to master Terraform & Kubernetes on AWS EKS in a Real-world perspective with 55 demo's on AWS Cloud with 25+ Kubernetes and 25+ Terraform Concepts
- You will learn Terraform Basics for 4.5 hours
- You will build a AWS VPC 3-Tier network with Terraform
- You will build a AWS EKS Cluster with Public and Private Node Groups with Terraform
- You will learn Kubernetes Fundamentals for 3 hours
- You will implement a simple kubernetes deployment and service using Terraform Kubernetes Provider
- Understand and Implement Terraform Remote State Datasource
- You will learn AWS EKS IRSA (IAM Roles for Service Accounts Concept) in detail and implement it with Terraform
- You will master Kubernetes Storage concepts with AWS EBS CSI Controller by automating the whole install process with Terraform
- You will master AWS EKS IAM Concepts with 7 detailed Demo
- You will learn to implement AWS Load Balancer Controller Install on AWS EKS Cluster with Terraform
- You will learn to implement 14 Ingress Service Demos (AWS Application Load Balancer) using Terraform Kubernetes Provider 
- You will learn to implement 3 Kubernetes Service Demos for AWS Load Balancer Controller
- You will master the AWS Fargate Concepts with 3 demos including running all workloads of EKS Cluster on AWS Fargate (Fargate Only EKS Cluster)
- You will install Kubernetes Cluster Autoscaler on AWS EKS Cluster with Terraform and Test it
- You will implement Horizontal and Vertical Pod Autoscaler Concepts with Terraform
- You will learn to implement AWS EKS Monitoring and Logging using kubectl and Terraform



## What are the requirements or prerequisites for taking your course?
- You must have an AWS Cloud account to follow with me for hands-on activities.
- You don't need to have any basic knowledge of Terraform. Course will get started from very very basics of Terraform and take you to very advanced levels
- You don't need to have any basic knowledge of Kubernetes. Course will get started from very very basics of Kubernetes and take you to very advanced levels

## Who is this course for?
- Infrastructure Architects or Sysadmins or Developers who are planning to master Terraform from Real-World perspective on AWS Cloud in combination with AWS Elastic Kubernetes Service (AWS EKS)
- Any beginner who is interested in learning IaC Infrastructure as Code current trending tool Terraform with AWS Cloud


## Github Repositories used for this course
- [Terraform on AWS EKS Kubernetes IaC SRE- 50 Real-World Demos](https://github.com/stacksimplify/terraform-on-aws-eks)
- [Course Presentation](https://github.com/stacksimplify/terraform-on-aws-eks/tree/main/course-presentation)
- [Kubernetes Fundamentals](https://github.com/stacksimplify/kubernetes-fundamentals)
- **Important Note:** Please go to these repositories and FORK these repositories and make use of them during the course.


## Each of my courses come with
- Amazing Hands-on Step By Step Learning Experiences
- Real Implementation Experience
- Friendly Support in the Q&A section
- 30 Day "No Questions Asked" Money Back Guarantee!

## My Other AWS Courses

- Terraform on EKS
  [![Image](https://stacksimplify.com/course-images/terraform-on-aws-eks-kubernetes.png "Terraform on AWS EKS Kubernetes IaC SRE- 50 Real-World Demos ")](https://links.stacksimplify.com/terraform-on-aws-eks-kubernetes-iac-sre)

- [Udemy Enroll](https://www.stacksimplify.com/azure-aks/courses/stacksimplify-best-selling-courses-on-udemy/)

## Stack Simplify Udemy Profile
- [Udemy Profile](https://www.udemy.com/user/kalyan-reddy-9/)

# HashiCorp Certified: Terraform Associate - 50 Practical Demos
[![Image](https://stacksimplify.com/course-images/hashicorp-certified-terraform-associate-highest-rated.png "HashiCorp Certified: Terraform Associate - 50 Practical Demos")](https://links.stacksimplify.com/hashicorp-certified-terraform-associate) 

# AWS EKS - Elastic Kubernetes Service - Masterclass
[![Image](https://stacksimplify.com/course-images/AWS-EKS-Kubernetes-Masterclass-DevOps-Microservices-course.png "AWS EKS Kubernetes - Masterclass")](https://www.udemy.com/course/aws-eks-kubernetes-masterclass-devops-microservices/?referralCode=257C9AD5B5AF8D12D1E1)


# Azure Kubernetes Service with Azure DevOps and Terraform 
[![Image](https://stacksimplify.com/course-images/azure-kubernetes-service-with-azure-devops-and-terraform.png "Azure Kubernetes Service with Azure DevOps and Terraform")](https://www.udemy.com/course/azure-kubernetes-service-with-azure-devops-and-terraform/?referralCode=2499BF7F5FAAA506ED42)

# Terraform on AWS with SRE & IaC DevOps | Real-World 20 Demos
[![Image](https://stacksimplify.com/course-images/terraform-on-aws-best-seller.png "Terraform on AWS with SRE & IaC DevOps | Real-World 20 Demos")](https://links.stacksimplify.com/terraform-on-aws-with-sre-and-iacdevops)

# Azure - HashiCorp Certified: Terraform Associate - 70 Demos
[![Image](https://stacksimplify.com/course-images/azure-hashicorp-certified-terraform-associate-highest-rated.png "Azure - HashiCorp Certified: Terraform Associate - 70 Demos")](https://links.stacksimplify.com/azure-hashicorp-certified-terraform-associate)

# Terraform on Azure with IaC DevOps and SRE | Real-World 25 Demos

[![Image](https://stacksimplify.com/course-images/terraform-on-azure-with-iac-azure-devops-sre-1.png "Terraform on Azure with IaC DevOps and SRE | Real-World 25 Demos")](https://links.stacksimplify.com/terraform-on-azure-with-iac-devops-sre)




## Additional References
- [Certification Curriculum](https://www.hashicorp.com/certification/terraform-associate)
- [Certification Preparation](https://learn.hashicorp.com/collections/terraform/certification)
- [Study Guide](https://learn.hashicorp.com/tutorials/terraform/associate-study?in=terraform/certification)
- [Exam Review Guide](https://learn.hashicorp.com/tutorials/terraform/associate-review?in=terraform/certification)
- [Sample Questions](https://learn.hashicorp.com/tutorials/terraform/associate-questions?in=terraform/certification)







