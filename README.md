# MetNet-AzureRDSFarm
# 

This template deploys the following resources:

<ul><li>storage account;</li><li>vnet, public ip, load balancer;</li><li>domain controller vm;</li><li>RD Gateway/RD Web Access vm;</li><li>RD Connection Broker/RD Licensing Server vm;</li><li>a number of RD Session hosts (number defined by 'numberOfRdshInstances' parameter)</li></ul>

The template will deploy DC, join all vms to the domain and configure RDS roles in the deployment.

Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmetnetwork%2FMetNet-AzureRDSFarm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
