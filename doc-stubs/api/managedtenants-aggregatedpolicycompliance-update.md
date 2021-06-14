---
title: "Update aggregatedPolicyCompliance"
description: "Update the properties of an aggregatedPolicyCompliance object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update aggregatedPolicyCompliance
Namespace: microsoft.graph.managedTenants



Update the properties of an [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.

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
PATCH /tenantRelationships/managedTenants/aggregatedPolicyCompliances/{aggregatedPolicyComplianceId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.

The following table shows the properties that are required when you update the [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md)|
|tenantId|String|**TODO: Add Description**|
|tenantDisplayName|String|**TODO: Add Description**|
|compliancePolicyId|String|**TODO: Add Description**|
|compliancePolicyName|String|**TODO: Add Description**|
|compliancePolicyType|String|**TODO: Add Description**|
|compliancePolicyPlatform|String|**TODO: Add Description**|
|numberOfCompliantDevices|Int64|**TODO: Add Description**|
|numberOfNonCompliantDevices|Int64|**TODO: Add Description**|
|numberOfErrorDevices|Int64|**TODO: Add Description**|
|policyModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|lastRefreshedDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_aggregatedpolicycompliance"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/tenantRelationships/managedTenants/aggregatedPolicyCompliances/{aggregatedPolicyComplianceId}
Content-Type: application/json
Content-length: 518

{
  "@odata.type": "#microsoft.graph.managedTenants.aggregatedPolicyCompliance",
  "tenantId": "String",
  "tenantDisplayName": "String",
  "compliancePolicyId": "String",
  "compliancePolicyName": "String",
  "compliancePolicyType": "String",
  "compliancePolicyPlatform": "String",
  "numberOfCompliantDevices": "Integer",
  "numberOfNonCompliantDevices": "Integer",
  "numberOfErrorDevices": "Integer",
  "policyModifiedDateTime": "String (timestamp)",
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
  "@odata.type": "#microsoft.graph.managedTenants.aggregatedPolicyCompliance",
  "id": "1c33c14c-c14c-1c33-4cc1-331c4cc1331c",
  "tenantId": "String",
  "tenantDisplayName": "String",
  "compliancePolicyId": "String",
  "compliancePolicyName": "String",
  "compliancePolicyType": "String",
  "compliancePolicyPlatform": "String",
  "numberOfCompliantDevices": "Integer",
  "numberOfNonCompliantDevices": "Integer",
  "numberOfErrorDevices": "Integer",
  "policyModifiedDateTime": "String (timestamp)",
  "lastRefreshedDateTime": "String (timestamp)"
}
```

