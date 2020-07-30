# Data Factory Operator

This role has by default all read actions allowed except of the Tables read role.
Additionaly specific actions are allow to perform operational tasks.

All actions can be found in the [documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftdatafactory).

Current set is defined on 30 June 2020.

## Operational actions allowed

| Action | Description |
|-|-|
| Microsoft.DataFactory/datafactories/datapipelines/pause/action | Pauses any Pipeline. |
| Microsoft.DataFactory/datafactories/datapipelines/resume/action | Resumes any Pipeline. |
| Microsoft.DataFactory/datafactories/gateways/connectioninfo/action | Reads the Connection Info for any Gateway. |
| Microsoft.DataFactory/factories/cancelpipelinerun/action | Cancels the pipeline run specified by the run ID. |
| Microsoft.DataFactory/factories/getDataPlaneAccess/action | Gets access to ADF DataPlane service. |
| Microsoft.DataFactory/factories/integrationruntimes/getObjectMetadata/action | Get SSIS Integration Runtime metadata for the specified Integration Runtime. |
| Microsoft.DataFactory/factories/integrationruntimes/refreshObjectMetadata/action | Refresh SSIS Integration Runtime metadata for the specified Integration Runtime. |
| Microsoft.DataFactory/factories/integrationruntimes/nodes/ipAddress/action | Returns the IP Address for the specified node of the Integration Runtime. |
| Microsoft.DataFactory/factories/pipelineruns/queryactivityruns/action | Queries the activity runs for the specified pipeline run ID. |
| Microsoft.DataFactory/factories/pipelines/createrun/action | Creates a run for the Pipeline. |
| Microsoft.DataFactory/factories/privateEndpointConnectionProxies/validate/action | Validate a Private Endpoint Connection Proxy. |
| Microsoft.DataFactory/factories/triggers/geteventsubscriptionstatus/action | Event Subscription Status. |

