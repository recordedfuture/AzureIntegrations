More information about Recorded Future Intelligence Solution for Microsoft Sentinel can be found in the main [readme](https://github.com/Azure/Azure-Sentinel/blob/master/Solutions/Recorded%20Future/readme.md).


## RecordedFuture-Identity-CustomConnector-POC
> [!NOTE]
> This is a Proof of Concept where we try new concepts and versions of the identity solution.

Logic app custom connector used by Recorded Future identity logic apps for communication with backend API. This connector is used by other logic apps in and are listed as a prerequisite in dependent logic apps. 


## Identity Custom Connector
Connector mapping the new /v2/credentials/lookup in [Azure-Identity BFI](https://api.recordedfuture.com/gw/azure-identity/)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frecordedfuture%2FAzureIntegrations%2Fmain%2FEntraID%2FRecordedFuture-Identity-Custom-Connector%2Fazuredeploy.json)

## RecordedFutureIdentity-lookup-and-save-user V2
Lookup and save modified to use the custom connector.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frecordedfuture%2FAzureIntegrations%2Fmain%2FEntraID%2FRecordedFutureIdentity-lookup-and-save-user%2Fazuredeploy.json)

