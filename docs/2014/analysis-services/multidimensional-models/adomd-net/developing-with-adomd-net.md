---
title: "Developing with ADOMD.NET | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "analysis-services"
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
helpviewer_keywords: 
  - "ADOMD.NET"
ms.assetid: abaf33aa-db55-43bf-8f30-15547559be1d
caps.latest.revision: 39
author: "Minewiskan"
ms.author: "owend"
manager: "mblythe"
---
# Developing with ADOMD.NET
  ADOMD.NET is a [!INCLUDE[msCoName](../../../includes/msconame-md.md)] .NET Framework data provider that is designed to communicate with [!INCLUDE[msCoName](../../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)]. ADOMD.NET uses the XML for Analysis protocol to communicate with analytical data sources by using either TCP/IP or HTTP connections to transmit and receive SOAP requests and responses that are compliant with the XML for Analysis specification. Commands can be sent in Multidimensional Expressions (MDX), Data Mining Extensions (DMX), Analysis Services Scripting Language (ASSL), or even a limited syntax of SQL, and may not return a result. Analytical data, key performance indicators (KPIs), and mining models can be queried and manipulated by using the ADOMD.NET object model. By using ADOMD.NET, you can also view and work with metadata either by retrieving OLE DB-compliant schema rowsets or by using the ADOMD.NET object model.  
  
 The ADOMD.NET data provider is represented by the `Microsoft.AnalysisServices.AdomdClient` namespace.  
  
## In This Section  
  
|Topic|Description|  
|-----------|-----------------|  
|[ADOMD.NET Client Programming](../../multidimensional-models-adomd-net-client/adomd-net-client-programming.md)|Describes how to use ADOMD.NET client objects to retrieve data and metadata from analytical data sources.|  
|[ADOMD.NET Server Programming](../../multidimensional-models-adomd-net-server/adomd-net-server-programming.md)|Describes how to use ADOMD.NET server objects to create stored procedures and user-defined functions.|  
|[Redistributing ADOMD.NET](redistributing-adomd-net.md)|Describes the process of redistributing ADOMD.NET.|  
|<xref:Microsoft.AnalysisServices.AdomdClient>|Details the objects that are contained in the `Microsoft.AnalysisServices.AdomdClient` namespace.|  
  
## See Also  
 [Multidimensional Expressions &#40;MDX&#41; Reference](/sql/mdx/multidimensional-expressions-mdx-reference)   
 [Data Mining Extensions &#40;DMX&#41; Reference](/sql/dmx/data-mining-extensions-dmx-reference)   
 [Analysis Services Schema Rowsets](../../schema-rowsets/analysis-services-schema-rowsets.md)   
 [Developing with Analysis Services Scripting Language &#40;ASSL&#41;](../scripting-language-assl/developing-with-analysis-services-scripting-language-assl.md)   
 [Multidimensional Model Data Access &#40;Analysis Services - Multidimensional Data&#41;](../mdx/multidimensional-model-data-access-analysis-services-multidimensional-data.md)  
  
  
