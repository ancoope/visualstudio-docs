---
title: "IDebugReference2::SetReferenceType | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugReference2::SetReferenceType"
helpviewer_keywords: 
  - "IDebugReference2::SetReferenceType"
ms.assetid: 5854a172-ea82-481c-97d9-c7fc16923d44
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugReference2::SetReferenceType
Sets the reference type. Reserved for future use.  
  
## Syntax  
  
```cpp  
HRESULT SetReferenceType (   
   REFERENCE_TYPE dwRefType  
);  
```  
  
```csharp  
int SetReferenceType (   
   enum_REFERENCE_TYPE dwRefType  
);  
```  
  
#### Parameters  
 `dwRefType`  
 [in] A value from the [REFERENCE_TYPE](../../../extensibility/debugger/reference/reference-type.md) enumeration that specifies the reference type.  
  
## Return Value  
 Always returns `E_NOTIMPL`.  
  
## See Also  
 [IDebugReference2](../../../extensibility/debugger/reference/idebugreference2.md)   
 [REFERENCE_TYPE](../../../extensibility/debugger/reference/reference-type.md)