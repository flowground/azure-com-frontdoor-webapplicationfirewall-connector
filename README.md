# ![LOGO](logo.png) WebApplicationFirewallManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the WebApplicationFirewallManagement API (version 2018-08-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/frontdoor-webapplicationfirewall/2018-08-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:10+03:00

## API Description

APIs to manage web application firewall rules

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the protection policies within a resource group.

*Tags:* `ListWebApplicationFirewalPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Deletes Policy

*Tags:* `DeleteWebApplicationFirewallPolicy`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `policyName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Retrieve protection policy with specified name within a resource group.

*Tags:* `GetWebapplicationfirewallPolicy`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `policyName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Creates or update policy with specified rule set name within a resource group.

*Tags:* `CreateOrUpdateWebApplicationFirewallPolicy`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `policyName` - _required_ - The name of the resource group.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-frontdoor-webapplicationfirewall-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
