---
title: "teamwork resource type"
description: "A container for Microsoft Teams features available for organization."
author: "akjo"
doc_type: resourcePageType
ms.localizationpriority: high
ms.prod: "microsoft-teams"
---

# teamwork resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

A container for the range of Microsoft Teams functionalities that are available for the organization.

## Methods

| Method                                                  | Return Type                                         |Description                                                                               |
|:--------------------------------------------------------|:----------------------------------------------------|:-----------------------------------------------------------------------------------------|
|[List deletedTeams](../api/teamwork-list-deletedteams.md)|[deletedTeam](../resources/deletedteam.md) collection|Get a list of the [deletedTeam](../resources/deletedteam.md) objects and their properties.|

## Properties

| Property | Type | Description |
|:---------------|:--------|:----------|
|id|string| A unique identifier. |

## Relationships

| Relationship | Type | Description |
|:---------------|:--------|:----------|
|deletedTeams|[deletedTeam](../resources/deletedteam.md) collection| A collection of deleted teams.|
|devices|[teamworkDevice](../resources/teamworkdevice.md) collection|The Teams devices provisioned for the tenant.|
|workforceIntegrations|[workforceIntegration](../resources/workforceintegration.md) collection| A workforce integration with shifts.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.teamwork",
  "baseType": "microsoft.graph.entity"
}-->

``` json
{
    "@odata.type": "#microsoft.graph.teamwork",
    "id": "String (identifier)"
}
```

## See also

- [userTeamwork resource](userteamwork.md)

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "teamwork resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->
