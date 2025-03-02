---
UID: NF:windows.foundation.IPropertyValue.GetInspectableArray
title: IPropertyValue::IPropertyValue (windows.foundation.h)
description: Gets the array of pointers to IInspectable objects that is stored in the current IPropertyValue object.
old-location: winrt\ipropertyvalue_getinspectablearray.htm
tech.root: WinRT
ms.assetid: 0af4f31f-e121-4cb2-8e83-c774bf25cae5
ms.date: 12/05/2018
ms.keywords: GetInspectableArray, GetInspectableArray method [Windows Runtime], GetInspectableArray method [Windows Runtime],IPropertyValue interface, IPropertyValue interface [Windows Runtime],GetInspectableArray method, IPropertyValue.GetInspectableArray, IPropertyValue.IPropertyValue, IPropertyValue::GetInspectableArray, IPropertyValue::IPropertyValue, windows/IPropertyValue::GetInspectableArray, winrt.ipropertyvalue_getinspectablearray
f1_keywords:
- windows.foundation/IPropertyValue.GetInspectableArray
dev_langs:
- c++
req.header: windows.foundation.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Windows.Foundation.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windows.Foundation.h
api_name:
- IPropertyValue.GetInspectableArray
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IPropertyValue::IPropertyValue


## -description


Gets the array of pointers to <a href="https://docs.microsoft.com/windows/desktop/api/inspectable/nn-inspectable-iinspectable">IInspectable</a> objects that is stored in the current <a href="https://docs.microsoft.com/windows/desktop/api/windows.foundation/nn-windows-foundation-ipropertyvalue">IPropertyValue</a> object.


## -parameters




### -param __valueSize [out]

Type: <b>UINT32*</b>

The number of values in the array.


### -param value [out]

Type: <b>IInspectable**</b>

The array of pointers to <a href="https://docs.microsoft.com/windows/desktop/api/inspectable/nn-inspectable-iinspectable">IInspectable</a> objects.

The returned pointer must be freed using <a href="https://docs.microsoft.com/windows/desktop/api/combaseapi/nf-combaseapi-cotaskmemfree">CoTaskMemFree</a>.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/windows.foundation/nn-windows-foundation-ipropertyvalue">IPropertyValue</a>



<a href="https://docs.microsoft.com/windows/desktop/api/windows.foundation/nf-windows-foundation-ipropertyvaluestatics-createinspectablearray">IPropertyValueStatics::CreateInspectableArray</a>
 

 

