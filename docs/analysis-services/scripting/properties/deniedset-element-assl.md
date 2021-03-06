---
title: "DeniedSet Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "DeniedSet Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "DeniedSet"
helpviewer_keywords: 
  - "DeniedSet element"
ms.assetid: 898deefb-822d-458b-96d8-880da287b687
caps.latest.revision: 34
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# DeniedSet Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Contains a set expression that defines the list of permissions that are denied on the associated attribute.  
  
## Syntax  
  
```xml  
  
<AttributePermission>  
      ...  
   <DeniedSet>...</DeniedSet>  
      ...  
</AttributePermission>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|String|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[AttributePermission](../../../analysis-services/scripting/objects/attributepermission-element-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The element that corresponds to the parent of **DeniedSet** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.AttributePermission>.  
  
## See Also  
 [Properties &#40;ASSL&#41;](../../../analysis-services/scripting/properties/properties-assl.md)  
  
  
