---
title: "cloudPcOverview resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# cloudPcOverview resource type

Namespace: microsoft.graph.managedTenants



**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List cloudPcOverviews](../api/managedtenants-cloudpcoverview-list.md)|[microsoft.graph.managedTenants.cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) collection|Get a list of the [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) objects and their properties.|
|[Create cloudPcOverview](../api/managedtenants-cloudpcoverview-create.md)|[microsoft.graph.managedTenants.cloudPcOverview](../resources/managedtenants-cloudpcoverview.md)|Create a new [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.|
|[Get cloudPcOverview](../api/managedtenants-cloudpcoverview-get.md)|[microsoft.graph.managedTenants.cloudPcOverview](../resources/managedtenants-cloudpcoverview.md)|Read the properties and relationships of a [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.|
|[Update cloudPcOverview](../api/managedtenants-cloudpcoverview-update.md)|[microsoft.graph.managedTenants.cloudPcOverview](../resources/managedtenants-cloudpcoverview.md)|Update the properties of a [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.|
|[Delete cloudPcOverview](../api/managedtenants-cloudpcoverview-delete.md)|None|Deletes a [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|
|lastRefreshedDateTime|DateTimeOffset|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusFailed|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusPassed|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusPending|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusRunning|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusUnkownFutureValue|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusDeprovisioning|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusFailed|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusInGracePeriod|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusNotProvisioned|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusProvisioned|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusProvisioning|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusUnknown|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusUpgrading|Int32|**TODO: Add Description**|
|tenantDisplayName|String|**TODO: Add Description**|
|totalCloudPcConnectionStatus|Int32|**TODO: Add Description**|
|totalCloudPcStatus|Int32|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.cloudPcOverview",
  "baseType": "microsoft.graph.entity",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.cloudPcOverview",
  "id": "String (identifier)",
  "tenantDisplayName": "String",
  "totalCloudPcStatus": "Integer",
  "numberOfCloudPcStatusNotProvisioned": "Integer",
  "numberOfCloudPcStatusProvisioning": "Integer",
  "numberOfCloudPcStatusProvisioned": "Integer",
  "numberOfCloudPcStatusUpgrading": "Integer",
  "numberOfCloudPcStatusInGracePeriod": "Integer",
  "numberOfCloudPcStatusDeprovisioning": "Integer",
  "numberOfCloudPcStatusFailed": "Integer",
  "numberOfCloudPcStatusUnknown": "Integer",
  "totalCloudPcConnectionStatus": "Integer",
  "numberOfCloudPcConnectionStatusPending": "Integer",
  "numberOfCloudPcConnectionStatusRunning": "Integer",
  "numberOfCloudPcConnectionStatusPassed": "Integer",
  "numberOfCloudPcConnectionStatusFailed": "Integer",
  "numberOfCloudPcConnectionStatusUnkownFutureValue": "Integer",
  "lastRefreshedDateTime": "String (timestamp)"
}
```

