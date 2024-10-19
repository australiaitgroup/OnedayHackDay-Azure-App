# Overview
Bicep template to provision azure services 


# Run following command to provision

```
az login 
az account set --subscription
az deployment group create \
  --resource-group <RESOURCE_GROUP_NAME> \
  --template-file <PATH_TO_BICEP_FILE> \
  --parameters <OPTIONAL_PARAMETERS>

```