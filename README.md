# azure.linked-arm-templates

A sample Azure DevOps pipeline to deploy linked ARM templates from a private repository.

Before starting to work with these templates, read the information in the following blog posts:

* [How to deploy linked ARM templates from private Azure DevOps repositories](https://andrewmatveychuk.com/how-to-deploy-linked-arm-templates-from-private-azure-devops-repositories/)

## Deployment status

[![Build Status](https://dev.azure.com/matveychuk/azure.linked-arm-templates/_apis/build/status/andrewmatveychuk.azure.linked-arm-templates?branchName=master)](https://dev.azure.com/matveychuk/azure.linked-arm-templates/_build/latest?definitionId=2&branchName=master)

## Getting Started

To start working with this project, clone the repository to your local machine and look for the artifacts in the specific folders:

* linked templates - contains sample ARM templates for resources to be deployed
* main-template - contains master ARM template to perform deployments of resources from all linked templates
* resource-group - contains a template for provisioning a resource group for the resources
* storage-account-for-artifacts - contains a template for provisioning a storage account to be used for storing the linked ARM templates
