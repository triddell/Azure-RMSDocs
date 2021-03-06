---
title: class mip::RecommendLabelAction 
description: Documents the mip::recommendlabelaction class of the Microsoft Information Protection (MIP) SDK.
author: msmbaldwin
ms.service: information-protection
ms.topic: reference
ms.collection: M365-security-compliance
ms.author: mbaldwin
ms.date: 01/28/2019
---

# class mip::RecommendLabelAction 
Recommend label actions is meant to suggest a label to the users. Suppressing this call after a user ignores the recommended label should be done through the supported actions on the execution state.
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public const std::string& GetLabelId() const  |  Get the label ID suggested.
public const std::vector\<std::string\>& GetClassificationIds() const  |  Get the Classification IDs that matched and caused this label to appear.
public ActionType GetType() const  |  Get the type of [Action](class_mip_action.md).
  
## Members
  
### GetLabelId function
Get the label ID suggested.

  
**Returns**: The label ID.
  
### GetClassificationIds function
Get the Classification IDs that matched and caused this label to appear.

  
**Returns**: Const std::vector<std::string>& a list of classification IDs that caused this label to appear.
  
### GetType function
Get the type of [Action](class_mip_action.md).

  
**Returns**: ActionType The type of derived action this base class can be cast to.
