# Azure Portal Dashboard Contributor

This role has all operations (wildcard based) to perform on the Azure Portal Dashboards. With this role, a user can create/edit/delete any dashboard. Assigning it to a specific resource group, allows the user to (only) create dashboards within that resource group.

All actions can be found in the [documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftportal).

Current set is defined on 17 August 2020.

## Actions allowed

The actions are allowed based on a wildcard (`Microsoft.Portal/dashboards/*`).

| Action | Description |
|-|-|
| Microsoft.Portal/dashboards/read | Reads the dashboards for the subscription. |
| Microsoft.Portal/dashboards/write | Add or modify dashboard to a subscription. |
| Microsoft.Portal/dashboards/delete | Removes the dashboard from the subscription. |

## Actions denied

_none_
