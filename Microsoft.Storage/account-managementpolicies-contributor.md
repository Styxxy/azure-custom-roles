# Storage Table Contributor

This role grants permission to the user to manage the Management Policies on a Storage Account.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftstorage).

Current set is defined on 30 September 2024.

## Actions allowed

The actions are allowed based on a wildcard (`Microsoft.Storage/storageAccounts/managementPolicies/*`).

| Action | Description |
|-|-|
| Microsoft.Storage/storageAccounts/managementPolicies/delete | Delete storage account management policies |
| Microsoft.Storage/storageAccounts/managementPolicies/read | Get storage management account policies |
| Microsoft.Storage/storageAccounts/managementPolicies/write | Put storage account management policies |

## Actions denied

_none_
