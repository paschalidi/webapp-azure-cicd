### Create a private container registry using the Azure CLI

https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-azure-cli

Then you want to get your credentials and store them as secrets on gh. 

```
 az acr credential show -n <registryName> 
```

### AZURE_CREDENTIALS
```
az ad sp create-for-rbac --name "principal07n6bpz8" --sdk-auth --role contributor --scopes /subscriptions/04204ae7-830e-4071-9af6-0a81e41697d5/resourceGroups/webapp-rg-demo-07n6bpz8
```


resources: 

https://github.com/Azure/webapps-deploy
https://docs.microsoft.com/en-us/azure/app-service/tutorial-custom-container?pivots=container-linux