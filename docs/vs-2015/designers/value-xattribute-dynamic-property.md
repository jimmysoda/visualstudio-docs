---
title: "Value (XAttribute Dynamic Property) | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: ""
ms.topic: "article"
api_name: 
  - "XAttribute.Value"
api_type: 
  - "Assembly"
ms.assetid: 019733d2-e050-4120-b537-831cd3fc008e
caps.latest.revision: 4
author: gewarren
ms.author: gewarren
manager: "ghogen"
---
# Value (XAttribute Dynamic Property)
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Value (XAttribute Dynamic Property)](https://docs.microsoft.com/visualstudio/designers/value-xattribute-dynamic-property).  
  
Gets or sets the value of the XML attribute.  
  
## Syntax  
  
```  
attrib.Value   
```  
  
## Property Value/Return Value  
 A <xref:System.String> containing the value of this attribute.  
  
## Exceptions  
  
|Exception type|Condition|  
|--------------------|---------------|  
|<xref:System.ArgumentNullException>|When setting, the `value` is `null`.|  
  
## Remarks  
 This property is equivalent to the <xref:System.Xml.Linq.XAttribute.Value%2A> property of the <xref:System.Xml.Linq.XAttribute?displayProperty=fullName> class, but this dynamic property also supports change notifications.  
  
## See Also  
 <xref:System.Xml.Linq.XAttribute.Value%2A?displayProperty=fullName>   
 [XAttribute Class Dynamic Properties](../designers/xattribute-class-dynamic-properties.md)   
 [Attribute](../designers/attribute-xelement-dynamic-property.md)



