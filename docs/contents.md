| [Home](../README.md) |
 | -------------------------------------------- |

  # Contents

The **Global Visibility** solution pack contains the following resources.


## Picklist

|Name|
| :- |
| Site Type |

## Module Schema

|Name|Description|
| :- | :- |
| Global Visibility Data | Module has a JSON type field *Dashboard Data* which contains data for the widgets. |

## Connector

| Name | Description |
| :- | :- |
| Remote FortiSOAR | This connector facilitates automated interactions, with a FortiSOAR endpoint using FortiSOAR playbooks. Add the Remote FortiSOAR connector as a step in FortiSOAR playbooks and run REST API operations on FortiSOAR environments other than your own FortiSOAR environment |

## Widgets

| Name | Description |
| :- | :- |
| Funnel Chart | To Visualize the Progression of Data Through Funnel layers. |
| Global Visibility Configuration | Global Visibility Configuration widget will open a Wizard to configure Remote Fortisoar connector for different sites. |
| Top X |  |
| Record Summary Tile |  |
| Record Summary Card |  |


## Roles

|Name|Description|
| :- | :- |
| Full App Permissions | Full App Permissions for the **Global Visibility Data** Module  |




## Playbook Collection

| 01 - Global Visibility |
|:------------:|

| Playbook Name | Description |
| :- | :- |
| Create Global Visibility Records | This playbook creates records for sites based on Remote FortiSOAR connector configured |
| Refresh Global Visibility Dashboard Data | Trigger this playbook to refresh fetch updated data from different sites configured in Remote FortiSOAR Widget |
| Get Tenant Data | None |
| Get Data From Configured Sites | Get data from all sites configured in remote FortiSOAR connector |





>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |