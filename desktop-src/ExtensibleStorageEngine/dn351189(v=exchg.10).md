---
title: UInt64ColumnValue.GetValueFromBytes method  (Microsoft.Isam.Esent.Interop)
TOCTitle: 'GetValueFromBytes method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.UInt64ColumnValue.GetValueFromBytes(System.Byte[],System.Int32,System.Int32,System.Int32)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.uint64columnvalue.getvaluefrombytes(v=EXCHG.10)
ms:contentKeyID: 55104084
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
f1_keywords:
- Microsoft.Isam.Esent.Interop.UInt64ColumnValue.GetValueFromBytes
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.UInt64ColumnValue.GetValueFromBytes
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# UInt64ColumnValue.GetValueFromBytes method

Given data retrieved from ESENT, decode the data and set the value in the ColumnValue object.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub GetValueFromBytes ( _
    value As Byte(), _
    startIndex As Integer, _
    count As Integer, _
    err As Integer _
)
'Usage
Dim value As Byte()
Dim startIndex As Integer
Dim count As Integer
Dim err As Integer

Me.GetValueFromBytes(value, startIndex, _
    count, err)
```

``` csharp
protected override void GetValueFromBytes(
    byte[] value,
    int startIndex,
    int count,
    int err
)
```

#### Parameters

  - value  
    Type: \[\]  
    
    An array of bytes.

<!-- end list -->

  - startIndex  
    Type: [System.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)  
    
    The starting position within the bytes.

<!-- end list -->

  - count  
    Type: [System.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)  
    
    The number of bytes to decode.

<!-- end list -->

  - err  
    Type: [System.Int32](http://msdn2.microsoft.com/en-us/library/td2s409d)  
    
    The error returned from ESENT.

## See also

#### Reference

[UInt64ColumnValue class](dn351190\(v=exchg.10\).md)

[UInt64ColumnValue members](dn351254\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
