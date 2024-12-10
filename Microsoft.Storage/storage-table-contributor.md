# Storage Table Contributor

[!WARNING]
This role is Obsolete. Consider migrating to the Azure built-in RBAC role [Storage Table Data Contributor](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles/storage#storage-table-data-contributor).

This role grants permission to the user to manage the Storage Table service.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftstorage).

Current set is defined on 15 February 2021.

## Actions allowed

The actions are allowed based on a wildcard (`Microsoft.Storage/storageAccounts/tableServices/*`).

| Action | Description |
|-|-|
| Microsoft.Storage/storageAccounts/tableServices/read | Get Table service properties |
| Microsoft.Storage/storageAccounts/tableServices/write |  |
| Microsoft.Storage/storageAccounts/tableServices/tables/read |  |
| Microsoft.Storage/storageAccounts/tableServices/tables/write |  |
| Microsoft.Storage/storageAccounts/tableServices/tables/delete |  |

## Actions denied

_none_
