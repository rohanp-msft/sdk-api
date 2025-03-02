---
UID: NF:wtsapi32.WTSFreeMemory
title: WTSFreeMemory function (wtsapi32.h)
description: Frees memory allocated by a Remote Desktop Services function.
old-location: termserv\wtsfreememory.htm
tech.root: TermServ
ms.assetid: 1c325174-ec08-4bbb-8e91-1a3cc9256110
ms.date: 12/05/2018
ms.keywords: WTSFreeMemory, WTSFreeMemory function [Remote Desktop Services], _win32_wtsfreememory, termserv.wtsfreememory, wtsapi32/WTSFreeMemory
f1_keywords:
- wtsapi32/WTSFreeMemory
dev_langs:
- c++
req.header: wtsapi32.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista
req.target-min-winversvr: Windows Server 2008
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Wtsapi32.lib
req.dll: Wtsapi32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Wtsapi32.dll
- Ext-MS-Win-Session-WtsApi32-l1-1-0.dll
api_name:
- WTSFreeMemory
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# WTSFreeMemory function


## -description


Frees memory allocated by a Remote Desktop Services function.


## -parameters




### -param pMemory [in]

Pointer to the memory to free.


## -returns



This function does not return a value.




## -remarks



Several Remote Desktop Services functions allocate buffers to return information. Use the 
<b>WTSFreeMemory</b> function to free these buffers.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wtsapi32/nf-wtsapi32-wtsenumerateprocessesa">WTSEnumerateProcesses</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wtsapi32/nf-wtsapi32-wtsenumeratesessionsa">WTSEnumerateSessions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wtsapi32/nf-wtsapi32-wtsquerysessioninformationa">WTSQuerySessionInformation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wtsapi32/nf-wtsapi32-wtsqueryuserconfiga">WTSQueryUserConfig</a>
 

 

