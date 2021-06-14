---
title: "aggregatedPolicyCompliance resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# aggregatedPolicyCompliance resource type

Namespace: microsoft.graph.managedTenants



**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List aggregatedPolicyCompliances](../api/managedtenants-aggregatedpolicycompliance-list.md)|[microsoft.graph.managedTenants.aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) collection|Get a list of the [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) objects and their properties.|
|[Create aggregatedPolicyCompliance](../api/managedtenants-aggregatedpolicycompliance-create.md)|[microsoft.graph.managedTenants.aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md)|Create a new [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.|
|[Get aggregatedPolicyCompliance](../api/managedtenants-aggregatedpolicycompliance-get.md)|[microsoft.graph.managedTenants.aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md)|Read the properties and relationships of an [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.|
|[Update aggregatedPolicyCompliance](../api/managedtenants-aggregatedpolicycompliance-update.md)|[microsoft.graph.managedTenants.aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md)|Update the properties of an [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.|
|[Delete aggregatedPolicyCompliance](../api/managedtenants-aggregatedpolicycompliance-delete.md)|None|Deletes an [aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|compliancePolicyId|String|**TODO: Add Description**|
|compliancePolicyName|String|**TODO: Add Description**|
|compliancePolicyPlatform|String|**TODO: Add Description**|
|compliancePolicyType|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|
|lastRefreshedDateTime|DateTimeOffset|**TODO: Add Description**|
|numberOfCompliantDevices|Int64|**TODO: Add Description**|
|numberOfErrorDevices|Int64|**TODO: Add Description**|
|numberOfNonCompliantDevices|Int64|**TODO: Add Description**|
|policyModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|tenantDisplayName|String|**TODO: Add Description**|
|tenantId|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.aggregatedPolicyCompliance",
  "baseType": "microsoft.graph.entity",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.aggregatedPolicyCompliance",
  "id": "String (identifier)",
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

