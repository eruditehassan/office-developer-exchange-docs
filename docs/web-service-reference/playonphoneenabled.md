---
title: "PlayOnPhoneEnabled"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
 
localization_priority: Normal
api_name:
- PlayOnPhoneEnabled
api_type:
- schema
ms.assetid: 6f800912-be4c-46f9-aa1e-dff0bbf877c5
description: "The PlayOnPhoneEnabled element indicates whether the Play-on-Phone feature is enabled."
---

# PlayOnPhoneEnabled

The **PlayOnPhoneEnabled** element indicates whether the Play-on-Phone feature is enabled. 
  
```XML
<PlayOnPhoneEnabled>true | false</PlayOnPhoneEnabled>
```

 **Boolean**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

None.
  
#### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[UnifiedMessagingConfiguration](unifiedmessagingconfiguration.md) <br/> |Contains configuration information for the Unified Messaging service.  <br/> |
   
## Text value

The **PlayOnPhoneEnabled** element has a value of **true** if play-on-phone is enabled for the account; otherwise, the value is **false**.
  
## Remarks

This element is required.
  
The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also

#### Concepts

[EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
