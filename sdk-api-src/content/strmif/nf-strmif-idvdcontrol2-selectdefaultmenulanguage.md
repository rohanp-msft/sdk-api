---
UID: NF:strmif.IDvdControl2.SelectDefaultMenuLanguage
title: IDvdControl2::SelectDefaultMenuLanguage (strmif.h)
description: The SelectDefaultMenuLanguage method sets the default language for all menus and menu buttons.
old-location: dshow\idvdcontrol2_selectdefaultmenulanguage.htm
tech.root: DirectShow
ms.assetid: f45d71e5-d125-477b-8fdf-f719a6c20101
ms.date: 12/05/2018
ms.keywords: IDvdControl2 interface [DirectShow],SelectDefaultMenuLanguage method, IDvdControl2.SelectDefaultMenuLanguage, IDvdControl2::SelectDefaultMenuLanguage, IDvdControl2SelectDefaultMenuLanguage, SelectDefaultMenuLanguage, SelectDefaultMenuLanguage method [DirectShow], SelectDefaultMenuLanguage method [DirectShow],IDvdControl2 interface, dshow.idvdcontrol2_selectdefaultmenulanguage, strmif/IDvdControl2::SelectDefaultMenuLanguage
f1_keywords:
- strmif/IDvdControl2.SelectDefaultMenuLanguage
dev_langs:
- c++
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IDvdControl2.SelectDefaultMenuLanguage
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDvdControl2::SelectDefaultMenuLanguage


## -description



The <code>SelectDefaultMenuLanguage</code> method sets the default language for all menus and menu buttons.




## -parameters




### -param Language

Variable of type LCID that specifies the default language.


## -returns



Returns one of the following values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
Invalid argument.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_DVD_INVALIDDOMAIN</b></dt>
</dl>
</td>
<td width="60%">
The <a href="https://docs.microsoft.com/windows/desktop/DirectShow/dvd-navigator-filter">DVD Navigator</a> is not in a valid domain.

</td>
</tr>
</table>
 




## -remarks



This method selects the default text language to use for menus when the disc is played. For example, if <i>Language</i> is specified as 0x409 for U.S. English, the DVD Navigator tries to show U.S. English text in menus. If the default menu language is not found on a disc, the DVD Navigator selects the closest match.

The following table shows the Annex J command name to which this method name corresponds, and the domains in which this method is valid.

<table>
<tr>
<td>Annex J Command Name
            </td>
<td>Valid Domains
            </td>
</tr>
<tr>
<td>Menu_Language_Select</td>
<td>DVD_DOMAIN_Stop</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/dvd-applications">DVD Applications</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nn-strmif-idvdcontrol2">IDvdControl2 Interface</a>
 

 

