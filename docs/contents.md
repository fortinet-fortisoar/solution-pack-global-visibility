| [Home](../README.md) |
 | -------------------------------------------- |

  # Contents

The **Global Visibility** solution pack contains the following resources.


## Picklist

| Name      | Description                                                                        |
|:----------|:-----------------------------------------------------------------------------------|
| Site Type | A drop-down menu that lists Master, Tenant, and Global sites from which to choose. |

## Module Schema

| Name                   | Description                                                                               |
|:-----------------------|:------------------------------------------------------------------------------------------|
| Global Visibility Data | Module containing a JSON type field *Dashboard Data* which contains data for the widgets. |

## Connector

| Name             | Description                                                                                             |
|:-----------------|:--------------------------------------------------------------------------------------------------------|
| Remote FortiSOAR | This connector facilitates automated interactions, with a FortiSOAR endpoint using FortiSOAR playbooks. |

## Widgets

| Name                            | Description                                                                                                           |
|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------|
| Funnel Chart                    | Helps visualize the progression of data through layers.                                                               |
| Global Visibility Configuration | Global Visibility Configuration widget launches a Wizard to configure Remote FortiSOAR connector for different sites. |
| Top X                           | Lists the top records based on a specified field.                                                                     |
| Record Summary Tile             | Lists JSON data from a record in a neat tile.                                                                         |
| Record Summary Card             | Lists specified JSON objects in a card format.                                                                        |

## Roles

| Name                 | Description                                                    |
|:---------------------|:---------------------------------------------------------------|
| Full App Permissions | Full App Permissions for the **Global Visibility Data** Module |

## Playbook Collection

| 01 - Global Visibility |
|:----------------------:|

| Playbook Name                            | Description                                                                                                    |
|:-----------------------------------------|:---------------------------------------------------------------------------------------------------------------|
| Create Global Visibility Records         | This playbook creates records for sites based on Remote FortiSOAR connector configured                         |
| Refresh Global Visibility Dashboard Data | Trigger this playbook to refresh fetch updated data from different sites configured in Remote FortiSOAR Widget |
| Get Tenant Data                          | Gets data like alerts, indicators, and incidents from Tenant sites                                             |
| Get Data From Configured Sites           | Get data from all sites configured in remote FortiSOAR connector                                               |

<table>
    <tr>
        <th>Warning</th>
        <td>We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.</td>
    </tr>
</table>

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|