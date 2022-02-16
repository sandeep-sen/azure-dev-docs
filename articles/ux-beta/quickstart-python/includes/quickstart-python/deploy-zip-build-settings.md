##### [bash](#tab/terminal-bash)

```azurecli
# Change these values to the ones used to create the App Service.
RESOURCE_GROUP_NAME='msdocs-python-webapp-quickstart'
APP_SERVICE_NAME='msdocs-python-webapp-quickstart-123'

az webapp config appsettings set \
    --resource-group $RESOURCE_GROUP_NAME \
    --name $APP_SERVICE_NAME \
    --settings SCM_DO_BUILD_DURING_DEPLOYMENT=true
```

##### [PowerShell terminal](#tab/terminal-powershell)

```azurecli
# Change these values to the ones used to create the App Service.
$resourceGroupName='msdocs-python-webapp-quickstart'
$appServiceName='msdocs-python-webapp-quickstart-123'

az webapp config appsettings set `
    --resource-group $resourceGroupName `
    --name $appServiceName `
    --settings SCM_DO_BUILD_DURING_DEPLOYMENT=true
```

---