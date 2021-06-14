---
title: "Update cloudPcOverview"
description: "Update the properties of a cloudPcOverview object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update cloudPcOverview
Namespace: microsoft.graph.managedTenants



Update the properties of a [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /tenantRelationships/managedTenants/cloudPcsOverview/{cloudPcOverviewId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object.

The following table shows the properties that are required when you update the [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md)|
|tenantDisplayName|String|**TODO: Add Description**|
|totalCloudPcStatus|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusNotProvisioned|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusProvisioning|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusProvisioned|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusUpgrading|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusInGracePeriod|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusDeprovisioning|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusFailed|Int32|**TODO: Add Description**|
|numberOfCloudPcStatusUnknown|Int32|**TODO: Add Description**|
|totalCloudPcConnectionStatus|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusPending|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusRunning|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusPassed|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusFailed|Int32|**TODO: Add Description**|
|numberOfCloudPcConnectionStatusUnkownFutureValue|Int32|**TODO: Add Description**|
|lastRefreshedDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_cloudpcoverview"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/tenantRelationships/managedTenants/cloudPcsOverview/{cloudPcOverviewId}
Content-Type: application/json
Content-length: 924

{
  "@odata.type": "#microsoft.graph.managedTenants.cloudPcOverview",
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


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.managedTenants.cloudPcOverview",
  "id": "6057790f-790f-6057-0f79-57600f795760",
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

