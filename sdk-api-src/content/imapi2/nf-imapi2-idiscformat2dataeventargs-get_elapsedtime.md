---
UID: NF:imapi2.IDiscFormat2DataEventArgs.get_ElapsedTime
title: IDiscFormat2DataEventArgs::get_ElapsedTime (imapi2.h)
description: Retrieves the total elapsed time of the write operation.
old-location: imapi\idiscformat2dataeventargs_get_elapsedtime.htm
tech.root: imapi
ms.assetid: 5ac3c261-dedc-4316-9241-387fc222443d
ms.date: 12/05/2018
ms.keywords: IDiscFormat2DataEventArgs interface [IMAPI],get_ElapsedTime method, IDiscFormat2DataEventArgs.get_ElapsedTime, IDiscFormat2DataEventArgs::get_ElapsedTime, get_ElapsedTime, get_ElapsedTime method [IMAPI], get_ElapsedTime method [IMAPI],IDiscFormat2DataEventArgs interface, imapi.idiscformat2dataeventargs_get_elapsedtime, imapi2/IDiscFormat2DataEventArgs::get_ElapsedTime
f1_keywords:
- imapi2/IDiscFormat2DataEventArgs.get_ElapsedTime
dev_langs:
- c++
req.header: imapi2.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Imapi2.idl
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
- imapi2.h
api_name:
- IDiscFormat2DataEventArgs.get_ElapsedTime
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDiscFormat2DataEventArgs::get_ElapsedTime


## -description


Retrieves the total elapsed time of the write operation.


## -parameters




### -param value [out]

Elapsed time, in seconds, of the write operation. 


## -returns



S_OK is returned on success, but other success codes may be returned as a result of implementation. The following error codes are commonly returned on operation failure, but do not represent the only possible error values:

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
Pointer is not valid.

Value: 0x80004003

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/imapi2/nn-imapi2-ddiscformat2dataevents">DDiscFormat2DataEvents</a>



<a href="https://docs.microsoft.com/windows/desktop/api/imapi2/nn-imapi2-idiscformat2dataeventargs">IDiscFormat2DataEventArgs</a>
 

 

