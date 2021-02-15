# Azure Service Bus Key Reader

This role grants permission to the user to list service bus namespace access keys.

All actions can be found in the [documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftservicebus).

Current set is defined on 15 February 2021.

## Actions allowed

| Action | Description |
|-|-|
| Microsoft.ServiceBus/namespaces/authorizationRules/read | Get the list of Namespaces Authorization Rules description. |
| Microsoft.ServiceBus/namespaces/authorizationRules/listkeys/action | Get the Connection String to the Namespace |

## Actions denied

_none_
