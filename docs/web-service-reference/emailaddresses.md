---
title: "EmailAddresses"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
 
localization_priority: Normal
api_name:
- EmailAddresses
api_type:
- schema
ms.assetid: fd4d773c-f7dc-4a04-9025-e772d7a45fdf
description: "The EmailAddresses element represents a collection of e-mail addresses for a contact."
---

# EmailAddresses

The **EmailAddresses** element represents a collection of e-mail addresses for a contact. 
  
```
<EmailAddresses>
   <Entry/>
</EmailAddresses>
```

 **EmailAddressDictionaryType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[Entry (EmailAddress)](entry-emailaddress.md) <br/> |Represents a single e-mail address for a contact.  <br/> |
   
#### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[Contact](contact.md) <br/> |Represents an Exchange contact item.  <br/> |
   
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema name  <br/> |Types schema  <br/> |
|Validation file  <br/> |Types.xsd  <br/> |
|Can be empty  <br/> |False  <br/> |
   
## See also

#### Concepts

[EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
#### Other resources

[Creating Contacts (Exchange Web Services)](http://msdn.microsoft.com/library/4845917e-70d1-481c-bbd7-011ec6571789%28Office.15%29.aspx)
  
[Updating Contacts](http://msdn.microsoft.com/library/9a865953-b94a-4229-b632-2dee433314be%28Office.15%29.aspx)
  
[Deleting Contacts](http://msdn.microsoft.com/library/fcc3dc84-cd3e-455e-a1a7-ae6921c9b588%28Office.15%29.aspx)
