# Storage Account Key Reader

> [!TIP]
> It is advisable to use EntraID integration instead of account keys for enhanced security.

This role grants permission to the user to **read** the Storage Account keys.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftstorage).

Current set is defined on 15 February 2021.

## Actions allowed

| Action | Description |
|-|-|
| Microsoft.Storage/storageAccounts/listkeys/action | Returns the access keys for the specified storage account. |

## Actions denied

_none_
