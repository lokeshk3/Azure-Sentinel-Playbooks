# Prisma-Sentinel
author: Nathan Swift

This Logic App connector will act as a Webhook listener, Prisma can then send an array of events to it and it will send the events to Azure Sentinel - Prisma_CL  

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fswiftsolves-msft%2FAzure-Sentinel-Playbooks%2Fmaster%2FPrisma-Sentinel%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fswiftsolves-msft%2FAzure-Sentinel-Playbooks%2Fmaster%2FPrisma-Sentinel%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>

**Additional Post Install Notes:**

Ensure to authorize the AzureLogAnalyticsDataCollector API by giving it the Azure Sentinel LogAnalytics Workspace ID and Key
<img src="https://raw.githubusercontent.com/swiftsolves-msft/Azure-Sentinel-Playbooks/master/Prisma-Sentinel/images/authorize.png"/>
</a>

Prisma configuration can be found: https://docs.paloaltonetworks.com/prisma/prisma-cloud/prisma-cloud-admin/configure-external-integrations-on-prisma-cloud/integrate-prisma-cloud-with-webhooks.html