---
title: "riskyUser resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# riskyUser resource type

Namespace: microsoft.graph.managedTenants



**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List riskyUsers](../api/managedtenants-riskyuser-list.md)|[microsoft.graph.managedTenants.riskyUser](../resources/managedtenants-riskyuser.md) collection|Get a list of the [riskyUser](../resources/managedtenants-riskyuser.md) objects and their properties.|
|[Create riskyUser](../api/managedtenants-riskyuser-create.md)|[microsoft.graph.managedTenants.riskyUser](../resources/managedtenants-riskyuser.md)|Create a new [riskyUser](../resources/managedtenants-riskyuser.md) object.|
|[Get riskyUser](../api/managedtenants-riskyuser-get.md)|[microsoft.graph.managedTenants.riskyUser](../resources/managedtenants-riskyuser.md)|Read the properties and relationships of a [riskyUser](../resources/managedtenants-riskyuser.md) object.|
|[Update riskyUser](../api/managedtenants-riskyuser-update.md)|[microsoft.graph.managedTenants.riskyUser](../resources/managedtenants-riskyuser.md)|Update the properties of a [riskyUser](../resources/managedtenants-riskyuser.md) object.|
|[Delete riskyUser](../api/managedtenants-riskyuser-delete.md)|None|Deletes a [riskyUser](../resources/managedtenants-riskyuser.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|
|isDeleted|Boolean|**TODO: Add Description**|
|lastRefreshedDateTime|DateTimeOffset|**TODO: Add Description**|
|riskDetail|String|**TODO: Add Description**|
|riskLastUpdatedDateTime|DateTimeOffset|**TODO: Add Description**|
|riskLevel|String|**TODO: Add Description**|
|riskState|String|**TODO: Add Description**|
|tenantDisplayName|String|**TODO: Add Description**|
|tenantId|String|**TODO: Add Description**|
|userDisplayName|String|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.riskyUser",
  "baseType": "microsoft.graph.entity",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.riskyUser",
  "id": "String (identifier)",
  "userId": "String",
  "tenantId": "String",
  "tenantDisplayName": "String",
  "userDisplayName": "String",
  "userPrincipalName": "String",
  "riskState": "String",
  "riskLevel": "String",
  "riskDetail": "String",
  "isDeleted": "Boolean",
  "riskLastUpdatedDateTime": "String (timestamp)",
  "lastRefreshedDateTime": "String (timestamp)"
}
```

