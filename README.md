# how-to-deploy
This repo contains details and examples of how we deploy software including infrastructure as code.

# How We Deploy Software


## Infrastructure as Code
* We will use OpenSource Terraform Cloud to create resources in the public cloud providers such as Azure, Google Cloud, and AWS.
* Remote state will be stored in Terraform Cloud.
* Terragrunt will be used to keep our TF code DRY.

## IOT Central - Azure 
* We will deploy Azure’s IOT Central Applications with the azurerm_iotcentral_application TF resource.


