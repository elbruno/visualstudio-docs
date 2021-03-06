---
title: "IDebugPrimitiveTypeField | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "IDebugPrimitiveTypeField interface"
ms.assetid: 73a428fd-797e-4ceb-8392-ba16f1c5226b
caps.latest.revision: 6
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
---
# IDebugPrimitiveTypeField
Represents a primitive type enumeration value from an [IDebugField](../../../extensibility/debugger/reference/idebugfield.md) interface.  
  
## Syntax  
  
```  
IDebugPrimitiveTypeField : IDebugField  
```  
  
## Methods  
 In addition to the methods on the [IDebugField](../../../extensibility/debugger/reference/idebugfield.md) interface, this interface implements the following method:  
  
|Method|Description|  
|------------|-----------------|  
|[GetPrimitiveType](../../../extensibility/debugger/reference/idebugprimitivetypefield-getprimitivetype.md)|Retrieves the primitive type associated with this field.|  
  
## Requirements  
 Header: Sh.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll