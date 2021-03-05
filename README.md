# AzureNestedHyperV
Create a Nested HyperV Host in Azure with one click

1. *Azure-deploy.json* – ARM template which will be called to run this provisioning
1. *InstallHyperV.ps1* – PowerShell script which will be called first and run using the PowerShell Custom Script extension
1. *HyperVHostConfig.ps1* (actually packaged as a zip file) – this is the PowerShell DSC script which will be run using the PowerShell DSC Script Extension.

<a href="https://portal.azure.com/?WT.mc_id=modops-0000-pierrer#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpierreroman%2FLP4S5%2Fmaster%2FASR-Demo-Setup%2FAzureNestedHyperV-master%2Fazure-deploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
