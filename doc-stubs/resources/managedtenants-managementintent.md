---
title: "managementIntent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# managementIntent resource type

Namespace: microsoft.graph.managedTenants



**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List managementIntents](../api/managedtenants-managementintent-list.md)|[microsoft.graph.managedTenants.managementIntent](../resources/managedtenants-managementintent.md) collection|Get a list of the [managementIntent](../resources/managedtenants-managementintent.md) objects and their properties.|
|[Create managementIntent](../api/managedtenants-managementintent-create.md)|[microsoft.graph.managedTenants.managementIntent](../resources/managedtenants-managementintent.md)|Create a new [managementIntent](../resources/managedtenants-managementintent.md) object.|
|[Get managementIntent](../api/managedtenants-managementintent-get.md)|[microsoft.graph.managedTenants.managementIntent](../resources/managedtenants-managementintent.md)|Read the properties and relationships of a [managementIntent](../resources/managedtenants-managementintent.md) object.|
|[Update managementIntent](../api/managedtenants-managementintent-update.md)|[microsoft.graph.managedTenants.managementIntent](../resources/managedtenants-managementintent.md)|Update the properties of a [managementIntent](../resources/managedtenants-managementintent.md) object.|
|[Delete managementIntent](../api/managedtenants-managementintent-delete.md)|None|Deletes a [managementIntent](../resources/managedtenants-managementintent.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|
|isGlobal|Boolean|**TODO: Add Description**|
|managementTemplates|[microsoft.graph.managedTenants.managementTemplateDetailedInfo](../resources/managedtenants-managementtemplatedetailedinfo.md) collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.managementIntent",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.managementIntent",
  "id": "String (identifier)",
  "displayName": "String",
  "isGlobal": "Boolean",
  "managementTemplates": [
    {
      "@odata.type": "microsoft.graph.managedTenants.managementTemplateDetailedInfo"
    }
  ]
}
```

