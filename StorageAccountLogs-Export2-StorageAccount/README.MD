<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FGetVirtual%2FAzure-ARM%2Fmaster%2FStorageAccountLogs-Export2-StorageAccount%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/GetVirtual/Azure-ARM/master/StorageAccountLogs-Export2-StorageAccount/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

# Azure Monitor logs for storage accounts #

Deploy a Azure storage account pre-configured to export all storage logs to another storage account.
https://docs.microsoft.com/en-us/azure/storage/common/monitor-storage?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=azure-powershell#logs-in-azure-monitor-preview

**Attention - the export logs feature is currently in preview and you can´t deploy it without being whitelisted**


## ARM Template ##
- Creates source storage account
- Creates sink storage account where the logs go to
- Apply export diagnosis log settings


