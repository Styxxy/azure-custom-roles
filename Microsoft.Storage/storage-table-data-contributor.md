# Storage Table Data Contributor

This role grants permission to the user to eead, write, and delete Azure Storage Table tables and data.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftstorage).

Current set is defined on 15 February 2021.

## Actions allowed

Some actions are allowed based on a wildcard (`Microsoft.Storage/storageAccounts/tableServices/tables/*`).

| Action | Description |
|-|-|
| Microsoft.Storage/storageAccounts/tableServices/read | Get Table service properties |
| Microsoft.Storage/storageAccounts/tableServices/tables/read |  |
| Microsoft.Storage/storageAccounts/tableServices/tables/write |  |
| Microsoft.Storage/storageAccounts/tableServices/tables/delete |  |

## Actions denied

_none_
