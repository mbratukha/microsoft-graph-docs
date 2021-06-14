---
title: "managedTenantExecutionError resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# managedTenantExecutionError resource type

Namespace: microsoft.graph.managedTenants



**TODO: Add Description**


Inherits from [managedTenantOperationError](../resources/managedtenants-managedtenantoperationerror.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|error|String|**TODO: Add Description** Inherited from [managedTenantOperationError](../resources/managedtenants-managedtenantoperationerror.md).|
|errorDetails|String|**TODO: Add Description**|
|nodeId|Int32|**TODO: Add Description**|
|rawToken|String|**TODO: Add Description**|
|statementIndex|Int32|**TODO: Add Description**|
|tenantId|String|**TODO: Add Description** Inherited from [managedTenantOperationError](../resources/managedtenants-managedtenantoperationerror.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.managedTenants.managedTenantExecutionError"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.managedTenantExecutionError",
  "tenantId": "String",
  "error": "String",
  "rawToken": "String",
  "statementIndex": "Integer",
  "nodeId": "Integer",
  "errorDetails": "String"
}
```

