---
title: "getState (Client API reference) in Dynamics 365 Customer Engagement| MicrosoftDocs"
ms.date: 10/31/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
ms.assetid: 199d1344-351a-44ee-8c43-f6b00b85a793
author: "KumarVivek"
ms.author: "kvivek"
manager: "amyla"
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# getState (Client API reference)

[!INCLUDE[](../../../../includes/cc_applies_to_update_9_0_0.md)]

Returns the state of the timer control.

This method is only supported for [Unified Interface](/dynamics365/get-started/whats-new/customer-engagement/new-in-july-2017-update#unified-interface-framework-for-new-apps). 

## Control types supported

Timer

## Syntax

`formContext.getControl(arg).getState();`

## Return Value

**Type**: Number

**Description**: Returns one of the following values:

|Value | State |
|--|--|
|1 | Not Set|
|2 | In progress|
|3 | Warning|
|4 | Violated|
|5 | Success|
|6 | Expired|
|7 | Canceled|
|8 | Paused|

### Related topics

[Controls](../controls.md)
