---
title: "Preview: Manage data sources | MicrosoftDocs"
description: View and manage on-premises data sources.
author: jimholtz
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 12/01/2020
ms.author: jimholtz 
search.audienceType: 
  - admin
search.app:
  - D365CE
  - PowerApps
  - Powerplatform
  - Flow
---
# Preview: Data source management

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

On the **Data** page of the Power Platform admin center (https://admin.powerplatform.microsoft.com), you can view and manage Power BI cloud and on-premises data sources and gateway clusters. The on-premises data sources on this page include all on-premises data source definitions for gateways you administer. The cloud data sources on this page are cloud connections in your published Power BI reports.

This article describes managing data sources. For information on managing gateway clusters, see [Preview: On-premises data gateway management](onpremises-data-gateway-management.md).

> [!NOTE]
> The data sources tab will not be available for tenant or service administrators when **Tenant administration** is turned on.

> [!div class="mx-imgBorder"] 
> ![Data sources tab](media/data-gateways-tenant-admin-off-data-sources.png "Data sources tab")

- **Data Source Name**: The name of the data source.
- **Data source type**: The type of the data source. For supported data sources, see [Power BI data sources](/power-bi/connect-data/power-bi-data-sources).
- **Users**: Users who can use this data source in data sets and data flows.
- **Status**: Select (![Check status](media/gateway-status.png "Check status")) to check the status of a gateway member.
- **Gateway cluster name**: The gateway cluster on which this data source was created. If it is a cloud data source, this value will be “Cloud”.

## Data source settings

Select a data source and then select **Settings** to see the following information. This view is currently read-only. 

> [!div class="mx-imgBorder"] 
> ![Data gateway settings tab](media/data-gateways-settings-tab.png "Data gateway settings tab")

> [!div class="mx-imgBorder"] 
> ![Data source settings](media/data-gateways-data-source-settings.png "Data source settings")

- **Data Source Name**: The name of the data source.
- **Data source type**: The type of the data source. For supported data sources, see [Power BI data sources](/power-bi/connect-data/power-bi-data-sources).
- **Connection details**: Connection information. Check back for updated information.
- **Authentication Method**: The authentication method chosen for this connection.

## Manage users

Select a data source and then select **Manage users** to see the list of current data source users. These users can use this data source in published reports and data flows. 

> [!div class="mx-imgBorder"] 
> ![Manage users for data source](media/data-gateways-source-manage-users.png "Manage users for data source")


## Remove a data source

Select a data source and then select **Remove** to remove the data source. 

> [!div class="mx-imgBorder"] 
> ![Remove a data source](media/data-gateways-remove-data-source.png "Remove a data source")

## Get help
For faster troubleshooting and assistance, select **Get help** to open a Get help panel. Include the session ID in a customer support ticket for any issues on the Data Gateways feature in the Power Platform admin center.

> [!div class="mx-imgBorder"] 
> ![Get help](media/get-help.png "Get help")

## Region

> [!div class="mx-imgBorder"] 
> ![Data source regions](media/data-gateways-data-source-region.png "Data source regions")

Currently, data sources are available only for the default Power BI region. For other regions, you won't see any data sources.

## Search

Select **Search** to find data sources and see their details. You currently can search on data source names, data source types, and gateway cluster names, but not users and status.

> [!div class="mx-imgBorder"] 
> ![Search data sources](media/data-gateways-data-source-search.png "Search data sources")

## Data source status

Select a data source, and then select **Check status** (![Data source status](media/gateway-status.png "Data source status")) to see the status of a data source.

### See also
 [On-premises data gateway](/data-integration/gateway/service-gateway-onprem)<br/>
 [Connecting to on-premises data sources with On-premises Data Gateway](/azure/analysis-services/analysis-services-gateway)<br/>


[!INCLUDE[footer-include](../includes/footer-banner.md)]