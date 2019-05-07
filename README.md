# ![LOGO](logo.png) AzureAnalysisServices **flow**ground Connector

## Description

A generated **flow**ground connector for the AzureAnalysisServices API (version 2017-08-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/analysisservices/2017-08-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:07+03:00

## API Description

The Azure Analysis Services Web API provides a RESTful set of web services that enables users to create, retrieve, update, and delete Analysis Services servers

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available consumption REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The client API version.

### Check the name availability in the target location.

*Tags:* `Servers`

#### Input Parameters
* `location` - _required_ - The region name which the operation will lookup into.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List the result of the specified operation.

*Tags:* `Servers`

#### Input Parameters
* `location` - _required_ - The region name which the operation will lookup into.
* `operationId` - _required_ - The target operation Id.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List the status of operation.

*Tags:* `Servers`

#### Input Parameters
* `location` - _required_ - The region name which the operation will lookup into.
* `operationId` - _required_ - The target operation Id.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the Analysis Services servers for the given subscription.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists eligible SKUs for Analysis Services resource provider.

#### Input Parameters
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the Analysis Services servers for the given resource group.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified Analysis Services server.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets details about the specified Analysis Services server.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be a minimum of 3 characters, and a maximum of 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates the current state of the specified Analysis Services server.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Provisions the specified Analysis Services server based on the configuration specified in the request.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be a minimum of 3 characters, and a maximum of 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Dissociates a Unified Gateway associated with the server.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Return the gateway status of the specified Analysis Services server instance.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Resumes operation of the specified Analysis Services server instance.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists eligible SKUs for an Analysis Services resource.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Suspends operation of the specified Analysis Services server instance.

*Tags:* `Servers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the Azure Resource group of which a given Analysis Services server is part. This name must be at least 1 character in length, and no more than 90.
* `serverName` - _required_ - The name of the Analysis Services server. It must be at least 3 characters in length, and no more than 63.
* `api-version` - _required_ - The client API version.
* `subscriptionId` - _required_ - A unique identifier for a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-analysisservices-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
