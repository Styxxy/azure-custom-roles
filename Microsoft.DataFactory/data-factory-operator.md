# Data Factory Operator

This role has by default all read actions allowed except of the Tables read role. Additionaly specific actions are allow to perform operational tasks.

All actions can be found in the [documentation](https://docs.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#microsoftdatafactory). This role is inspired by the information [medium blog post](https://medium.com/microsoftazure/azure-custom-role-guidance-and-azure-data-factory-custom-operator-role-daaa6d7e66df) "Azure Custom Role Guidance and Azure Data Factory Custom Operator Role" by Inderjit Rana.

Current set is defined on 30 July 2020.

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

## Actions denied

| Action | Description |
|-|-|
| Microsoft.DataFactory/datafactories/tables/read | Reads any Dataset. |

## Read actions allowed

The read actions are allowed through a wildcard (`Microsoft.DataFactory/*/read`). As of 30 July 2020 the list contains following actions:

| Action | Description |
|-|-|
| Microsoft.DataFactory/checkazuredatafactorynameavailability/read | Checks if the Data Factory Name is available to use. |
| Microsoft.DataFactory/datafactories/read | Reads the Data Factory. |
| Microsoft.DataFactory/datafactories/activitywindows/read | Reads Activity Windows in the Data Factory with specified parameters. |
| Microsoft.DataFactory/datafactories/datapipelines/read | Reads any Pipeline. |
| Microsoft.DataFactory/datafactories/datapipelines/activities/activitywindows/read | Reads Activity Windows for the Pipeline Activity with specified parameters. |
| Microsoft.DataFactory/datafactories/datapipelines/activitywindows/read | Reads Activity Windows for the Pipeline with specified parameters. |
| Microsoft.DataFactory/datafactories/datasets/read | Reads any Dataset. |
| Microsoft.DataFactory/datafactories/datasets/activitywindows/read | Reads Activity Windows for the Dataset with specified parameters. |
| Microsoft.DataFactory/datafactories/datasets/sliceruns/read | Reads the Data Slice Run for the given dataset with the given start time. |
| Microsoft.DataFactory/datafactories/datasets/slices/read | Gets the Data Slices in the given period. |
| Microsoft.DataFactory/datafactories/gateways/read | Reads any Gateway. |
| Microsoft.DataFactory/datafactories/linkedServices/read | Reads any Linked Service. |
| Microsoft.DataFactory/datafactories/runs/loginfo/read | Reads a SAS URI to a blob container containing the logs. |
| Microsoft.DataFactory/datafactories/tables/read | Reads any Dataset. |
| Microsoft.DataFactory/factories/read | Reads Data Factory. |
| Microsoft.DataFactory/factories/dataflows/read | Reads Data Flow. |
| Microsoft.DataFactory/factories/datasets/read | Reads any Dataset. |
| Microsoft.DataFactory/factories/getDataPlaneAccess/read | Reads access to ADF DataPlane service. |
| Microsoft.DataFactory/factories/getFeatureValue/read | Reads exposure control feature value for the specific location. |
| Microsoft.DataFactory/factories/integrationruntimes/read | Reads any Integration Runtime. |
| Microsoft.DataFactory/factories/integrationruntimes/getconnectioninfo/read | Reads Integration Runtime Connection Info. |
| Microsoft.DataFactory/factories/integrationruntimes/getstatus/read | Reads Integration Runtime Status. |
| Microsoft.DataFactory/factories/integrationruntimes/listauthkeys/read | Lists the Authentication Keys for any Integration Runtime. |
| Microsoft.DataFactory/factories/integrationruntimes/monitoringdata/read | Gets the Monitoring Data for any Integration Runtime. |
| Microsoft.DataFactory/factories/integrationruntimes/nodes/read | Reads the Node for the specified Integration Runtime. |
| Microsoft.DataFactory/factories/linkedServices/read | Reads Linked Service. |
| Microsoft.DataFactory/factories/operationResults/read | Gets operation results. |
| Microsoft.DataFactory/factories/pipelineruns/read | Reads the Pipeline Runs. |
| Microsoft.DataFactory/factories/pipelineruns/activityruns/read | Reads the activity runs for the specified pipeline run ID. |
| Microsoft.DataFactory/factories/pipelineruns/queryactivityruns/read | Reads the result of query activity runs for the specified pipeline run ID. |
| Microsoft.DataFactory/factories/pipelines/read | Reads Pipeline. |
| Microsoft.DataFactory/factories/pipelines/pipelineruns/read | Reads the Pipeline Run. |
| Microsoft.DataFactory/factories/pipelines/pipelineruns/activityruns/progress/read | Gets the Progress of Activity Runs. |
| Microsoft.DataFactory/factories/privateEndpointConnectionProxies/read | Read Private Endpoint Connection Proxy. |
| Microsoft.DataFactory/factories/privateEndpointConnectionProxies/operationresults/read | Read the results of creating a Private Endpoint Connection Proxy. |
| Microsoft.DataFactory/factories/privateEndpointConnectionProxies/operationstatuses/read | Read the status of creating a Private Endpoint Connection Proxy. |
| Microsoft.DataFactory/factories/querypipelineruns/read | Reads the Result of Query Pipeline Runs. |
| Microsoft.DataFactory/factories/querytriggerruns/read | Reads the Result of Trigger Runs. |
| Microsoft.DataFactory/factories/sandboxpipelineruns/read | Gets the debug run info for the Pipeline. |
| Microsoft.DataFactory/factories/sandboxpipelineruns/sandboxActivityRuns/read | Gets the debug run info for the Activity. |
| Microsoft.DataFactory/factories/triggerruns/read | Reads the Trigger Runs. |
| Microsoft.DataFactory/factories/triggers/read | Reads any Trigger. |
| Microsoft.DataFactory/factories/triggers/triggerruns/read | Reads the Trigger Runs. |
| Microsoft.DataFactory/locations/getFeatureValue/read | Reads exposure control feature value for the specific location. |
| Microsoft.DataFactory/operations/read | Reads all Operations in Microsoft Data Factory Provider. |
