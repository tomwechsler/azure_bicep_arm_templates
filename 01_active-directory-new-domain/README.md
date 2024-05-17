---
description: This template creates a new Azure VM, it configures the VM to be an AD DC for a new Forest
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: active-directory-new-domain
languages:
- bicep
- json
---
# Create an Azure VM with a new AD Forest

This template will deploy a new VM (along with a new VNet and Load Balancer) and will configure it as a Domain Controller and create a new forest and domain.

Click the button below to deploy  
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftomwechsler%2Fazure_bicep_arm_templates%2Fmain%2F01_active-directory-new-domain%2Fazuredeploy.json)