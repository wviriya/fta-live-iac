---
services: ARM and Azure Pipeline 
author: wviriya
level: 300
---

# FastTrack for Azure Live - How to deploy Azure services and infrastructure. Leverage Azure Pipeline for CI/CD.  

## Synopsis:
"Zero to Hero with ARM and IaC" How to create an ARM Template using Bicep and deploy using Azure Pipelines.

## Who should attend:
- I want to do Infrastructure as Code but don't know where to start.
- My team keeps asking me to deploy infrastructure and various environments to Azure, and I do it manually.
- I want to automate my infrastructure.

## At the end of the session you should:
- Understand the basic structure of an ARM Template
- Be aware of the tools available to create and manage ARM Templates
- Understand basic how to create and use simple Azure Pipelines

## What are prerequisites:
- Azure Subscription
- Azure DevOps account
- JSON (JavaScript Object Notation)
- YAML Syntax
- Git repository
- Desire to learn

## Where are your team
![Automation Maturity](contents/automation_maturity.png)

## About this sample
This sample is a guide for learning basic ARM Template usage. The links in this document can you help better understand these services and tools.

## [What is Infrastructure as Code?](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-infrastructure-as-code)

## [Why I should adopt Infrastructure as Code Practice? (Read John Downs' Blog)](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/the-benefits-of-infrastructure-as-code/ba-p/2069350)

## Azure Resource Manager (ARM) Template
A native infra-as-code solution for managing Azure resources using a declarative programming paradigm.

### Concepts
- [What is ARM?](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview)
- [What are ARM Templates?](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
- [Bicep (Experimental)](https://github.com/azure/bicep)
- [Nested and Linked templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/linked-templates)
- [Deployment modes](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-modes)
- [Best practices](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-best-practices)    

### Authoring tools and helps
- [ARM QuickStart Templates](https://azure.microsoft.com/en-us/resources/templates/)
- [Azure Portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-the-portal)
- [VS Code](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-visual-studio-code?tabs=CLI)
- [Visual Studio](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/create-visual-studio-deployment-project)
- [Template structure and syntax](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-syntax)
- [Template references](https://docs.microsoft.com/en-us/azure/templates/)
- [ARM template functions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions)
- [ARM Template Toolkit for analyzing and testing](https://github.com/Azure/arm-ttk)

### CI/CD
- [Deploy with Azure Pipelines](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/add-template-to-azure-pipelines)
- [Deploy with GitHub Actions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-github-actions)

### Learning resources
- [Microsoft Learn path on ARM template](https://docs.microsoft.com/en-us/learn/paths/deploy-manage-resource-manager-templates)

### New and preview features
- [Deployment scripts (GA - DEC 2020)](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-deployment-script)
- [What-If deployment (GA - DEC 2020)](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-deploy-what-if?tabs=azure-powershell)
- [Template Specs (Preview)](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs?tabs=azure-powershell)
- [Azure Deployment Manager (Preview)](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs?tabs=azure-powershell)

## Other orchestrators
### Terraform with Azure
- [Overview](https://docs.microsoft.com/en-us/azure/developer/terraform/overview)
- [Terraform QuickStart](https://docs.microsoft.com/en-us/azure/developer/terraform/install-configure)
- [Terraform Configuration Language](https://www.terraform.io/docs/configuration/syntax.html)
- [Store Terraform state in Azure Storage](https://docs.microsoft.com/en-us/azure/developer/terraform/store-state-in-azure-storage)
- [Automating infrastructure deployments in the Cloud with Terraform and Azure Pipelines](https://www.azuredevopslabs.com/labs/vstsextend/terraform/)

### Ansible wiht Azure
- [Overview](https://docs.microsoft.com/en-us/azure/developer/ansible/overview)
- [Ansible QuickStart](https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm)  
- [Ansible Playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html)
- [Automating infrastructure deployments in the Cloud with Ansible and Azure Pipelines](https://www.azuredevopslabs.com/labs/vstsextend/ansible/)

## [FAQ](./faq.md)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
