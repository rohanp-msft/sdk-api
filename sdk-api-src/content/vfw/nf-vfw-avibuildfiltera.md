---
UID: NF:vfw.AVIBuildFilterA
title: AVIBuildFilterA function (vfw.h)
description: The AVIBuildFilter function builds a filter specification that is subsequently used by the GetOpenFileName or GetSaveFileName function.
old-location: multimedia\avibuildfilter.htm
tech.root: Multimedia
ms.assetid: 0ec90343-7493-4fa7-ac89-a49db90ecdf7
ms.date: 12/05/2018
ms.keywords: AVIBuildFilter, AVIBuildFilter function [Windows Multimedia], AVIBuildFilterA, AVIBuildFilterW, _win32_AVIBuildFilter, multimedia.avibuildfilter, vfw/AVIBuildFilter, vfw/AVIBuildFilterA, vfw/AVIBuildFilterW
f1_keywords:
- vfw/AVIBuildFilter
dev_langs:
- c++
req.header: vfw.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: AVIBuildFilterW (Unicode) and AVIBuildFilterA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Vfw32.lib
req.dll: Avifil32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Avifil32.dll
api_name:
- AVIBuildFilter
- AVIBuildFilterA
- AVIBuildFilterW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# AVIBuildFilterA function


## -description



The <b>AVIBuildFilter</b> function builds a filter specification that is subsequently used by the <a href="https://msdn.microsoft.com/library/ms646927.aspx">GetOpenFileName</a> or <a href="https://msdn.microsoft.com/library/ms646928.aspx">GetSaveFileName</a> function.




## -parameters




### -param lpszFilter

Pointer to the buffer containing the filter string.


### -param cbFilter

Size, in characters, of buffer pointed to by <i>lpszFilter</i>.


### -param fSaving

Flag that indicates whether the filter should include read or write formats. Specify <b>TRUE</b> to include write formats or <b>FALSE</b> to include read formats.


## -returns



Returns AVIERR_OK if successful or an error otherwise. Possible error values include the following.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>AVIERR_BUFFERTOOSMALL</b></dt>
</dl>
</td>
<td width="60%">
The buffer size <i>cbFilter</i> was smaller than the generated filter specification.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>AVIERR_MEMORY</b></dt>
</dl>
</td>
<td width="60%">
There was not enough memory to complete the read operation.

</td>
</tr>
</table>
 




## -remarks



This function accesses the registry for all filter types that the AVIFile library can use to open, read, or write multimedia files. It does not search the hard disk for filter DLLs and formats.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/Multimedia/avifile-functions">AVIFile Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/Multimedia/avifile-functions-and-macros">AVIFile Functions and Macros</a>
 

 

