# Azure Portal Dashboard Contributor

This role has by default all read actions allowed. Additionaly specific actions are allow to perform operational tasks.

All actions can be found in the [documentation](https://learn.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftpowerbidedicated).

Current set is defined on 3 March 2023.

## Actions allowed

| Action | Description |
|-|-|
| Microsoft.PowerBIDedicated/*/read | All read actions on the Microsoft.PowerBIDedicated resource provided. |
| Microsoft.PowerBIDedicated/capacities/suspend/action | Suspends the Capacity. |
| Microsoft.PowerBIDedicated/capacities/resume/action | Resumes the Capacity. |
| Microsoft.PowerBIDedicated/servers/suspend/action | Suspends the Server. |
| Microsoft.PowerBIDedicated/servers/resume/action | Resumes the Server. |

## Actions denied

_none_

## Read actions allowed

The read actions are allowed through a wildcard (`Microsoft.PowerBIDedicated/*/read`). As of 3 March 2023 the list contains following actions:

| Action | Description |
|-|-|
| Microsoft.PowerBIDedicated/autoScaleVCores/read | Retrieves the information of the specificed Power BI Auto Scale V-Core. |
| Microsoft.PowerBIDedicated/capacities/read | Retrieves the information of the specified Power BI capacity. |
| Microsoft.PowerBIDedicated/capacities/providers/Microsoft.Insights/diagnosticSettings/read | Gets the diagnostic setting for the resource. |
| Microsoft.PowerBIDedicated/capacities/providers/Microsoft.Insights/logDefinitions/read | Gets the available logs for Power BI Dedicated Capacities. |
| Microsoft.PowerBIDedicated/capacities/providers/Microsoft.Insights/metricDefinitions/read | Gets the available metrics for Power BI capacity. |
| Microsoft.PowerBIDedicated/capacities/skus/read | Retrieve available SKU information for the capacity. |
| Microsoft.PowerBIDedicated/locations/operationresults/read | Retrieves the information of the specified operation result. |
| Microsoft.PowerBIDedicated/locations/operationstatuses/read | Retrieves the information of the specified operation status. |
| Microsoft.PowerBIDedicated/operations/read | Retrieves the information of operations. |
| Microsoft.PowerBIDedicated/servers/read | Retrieves the information of the specified Power BI Dedicated Server. |
| Microsoft.PowerBIDedicated/servers/skus/read | Retrieve available SKU information for the Server. |
| Microsoft.PowerBIDedicated/skus/read | 	Retrieves the information of SKUs. |
