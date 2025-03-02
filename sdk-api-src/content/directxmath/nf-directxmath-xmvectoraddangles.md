---
UID: NF:directxmath.XMVectorAddAngles
title: XMVectorAddAngles function (directxmath.h)
description: Adds two vectors representing angles.
old-location: dxmath\xmvectoraddangles.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.geometric.XMVectorAddAngles(XMVECTOR,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMVectorAddAngles, XMVectorAddAngles, XMVectorAddAngles method [DirectX Math Support APIs], dxmath.xmvectoraddangles
f1_keywords:
- directxmath/XMVectorAddAngles
dev_langs:
- c++
req.header: directxmath.h
req.include-header: DirectXMath.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: Use DirectX.
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
- directxmathvector.inl
api_name:
- XMVectorAddAngles
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMVectorAddAngles function


## -description


Adds two vectors representing angles.


## -parameters




### -param V1 [in]

First vector of angles. Each angle must satisfy -XM_PI &lt;= <i>V1</i>  &lt; XM_PI.


### -param V2 [in]

Second vector of angles. Each angle must satisfy -XM_2PI &lt;= <i>V1</i>  &lt; XM_2PI.


## -returns



Returns a vector whose components are the sums of the angles of the corresponding components. Each component of the returned vector will be an angle less than XM_PI and greater than or equal to -XM_PI.




## -remarks



<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-vector-arithmetic">Vector Arithmetic Functions</a>
 

 

