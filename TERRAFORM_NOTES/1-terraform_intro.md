

# INTRODUCTION to TERRAFORM:

*### WHAT IS TERRAFORM?*
Terraform is an open-source Infrastructure as Code (IaC) tool by HashiCorp that uses HashiCorp Configuration Language (HCL) to create and manage cloud and on-premises resources such as virtual machines, networks, databases.

*### WHAT IS IaC?*
Infrastructure as Code (IaC) means provisioning and managing cloud infrastructure using code instead of manual process with enabling version control and automation.

WHY TERRAFORM?
1. Cloud Agnostic
2. Multi Cloud support
3. State Management
4. Declarative
5. Shows Plan before Apply


1. *Introduction to IaC & Terraform*

- What is Terraform
- What is IaC
- Imperative vs Declarative
- Why Terraform?
- Terraform vs Other tools (Ansible, Pulimi, Chef, Puppet)
- Terraform architecture & workflow (Init → Plan → Apply → Destroy)
- Providers & plugins

**What is Terraform?**

Terraform is an open-source Infrastructure as Code ( IaC ) tool by HashiCorp that uses HashiCorp Configuration Language ( HCL ) to create and manage cloud and on-premises resources such as virtual machines, networks, databases.

**What is IaC (Infrastructure as Code)**

Infrastructure as Code (IaC) means provisioning and managing cloud infrastructure using code instead of manual process with enabling version control and automation.

**Imperative vs Declarative**

- **Imperative:** You tell the system **how to do each step**. ( step-by-step instructions )
( e.g., create server, install software, configure settings)
- **Declarative:** You tell the system **what you want**, and it decides how to do it.
( e.g., “I want a server with this software installed.” ( Terraform does the steps )
- Terraform follows a declarative approach (Users define what they want, TF handles the execution)

**Why terraform over other tools?**

- Cloud Agnostic
Terraform works with many platforms (works with GCP, AWS, Azure, GitHub, etc.)
It uses the same language (HCL) and same workflow
It is not locked to one cloud, so, all these makes Terraform cloud-agnostic.
- Multi cloud supports
Company uses more than one cloud at the same time for high availability (if one cloud goes down, others keep running)
- Declarative
focus on desired state ( you tell the system what you want, not the step by step instructions)
- State Management
Tracks real infrastructure using `terraform.tfstate`
- Plan before Apply
Shows what will change before applying
