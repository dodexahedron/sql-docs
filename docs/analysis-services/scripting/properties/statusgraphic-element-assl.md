---
title: "StatusGraphic Element (ASSL) | Microsoft Docs"
ms.date: 5/8/2018
ms.prod: sql
ms.custom: assl
ms.reviewer: owend
ms.technology: analysis-services
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# StatusGraphic Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Contains the recommended graphical representation of the status of the [Kpi](../../../analysis-services/scripting/objects/kpi-element-assl.md) element.  
  
## Syntax  
  
```xml  
  
<Kpi>  
   ...  
   <StatusGraphic>...</StatusGraphic>  
   ...  
</Kpi>  
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
|Parent element|[Kpi](../../../analysis-services/scripting/objects/kpi-element-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The value of this element is limited to one of the strings listed in the following table.  
  
|Value|Description|  
|-----------|-----------------|  
|*Traffic Light - Single*|Traffic light (single)|  
|*Traffic Light - Multiple*|Traffic light (multiple)|  
|*Road Signs*|Road signs|  
|*Gauge - Ascending*|Gauge|  
|*Gauge - Descending*|Reversed Gauge|  
|*Thermometer*|Thermometer|  
|*Cylinder*|Cylinder|  
|*Smiley Face*|Face|  
  
 The element that corresponds to the parent of **StatusGraphic** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.Kpi>.  
  
## See Also  
 [Properties &#40;ASSL&#41;](../../../analysis-services/scripting/properties/properties-assl.md)  
  
  
