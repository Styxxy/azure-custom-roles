# Azure Service Bus Key Operator Service Role

> [!TIP]
> It is advisable to use EntraID integration instead of account keys for enhanced security.

This role grants permission to the user to list and regenerate service bus namespace access keys.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftstorage).

Current set is defined on 15 February 2021.

## Actions allowed

| Action | Description |
|-|-|
| Microsoft.ServiceBus/namespaces/authorizationRules/read | Get the list of Namespaces Authorization Rules description. |
| Microsoft.ServiceBus/namespaces/authorizationRules/listkeys/action | Get the Connection String to the Namespace |
| Microsoft.ServiceBus/namespaces/authorizationRules/regenerateKeys/action | Regenerate the Primary or Secondary key to the Resource |

## Actions denied

_none_
