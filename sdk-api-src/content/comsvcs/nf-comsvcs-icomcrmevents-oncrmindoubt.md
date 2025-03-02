---
UID: NF:comsvcs.IComCRMEvents.OnCRMIndoubt
title: IComCRMEvents::OnCRMIndoubt (comsvcs.h)
description: Generated when CRM clerk receives an in-doubt notification to pass on to the CRM compensator.
old-location: cos\icomcrmevents_oncrmindoubt.htm
tech.root: cossdk
ms.assetid: b1144b7c-097f-4a1c-b7d7-d71b8108625b
ms.date: 12/05/2018
ms.keywords: IComCRMEvents interface [COM+],OnCRMIndoubt method, IComCRMEvents.OnCRMIndoubt, IComCRMEvents::OnCRMIndoubt, OnCRMIndoubt, OnCRMIndoubt method [COM+], OnCRMIndoubt method [COM+],IComCRMEvents interface, _dtc_IComCRMEvents_OnCRMIndoubt, comsvcs/IComCRMEvents::OnCRMIndoubt, cos.icomcrmevents_oncrmindoubt
f1_keywords:
- comsvcs/IComCRMEvents.OnCRMIndoubt
dev_langs:
- c++
req.header: comsvcs.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
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
- ComSvcs.h
api_name:
- IComCRMEvents.OnCRMIndoubt
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IComCRMEvents::OnCRMIndoubt


## -description


Generated when CRM clerk receives an in-doubt notification to pass on to the CRM compensator.


## -parameters




### -param pInfo [in]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/comsvcs/ns-comsvcs-comsvcseventinfo">COMSVCSEVENTINFO</a> structure.


### -param guidClerkCLSID [in]

The identifier of the CRM clerk.


## -returns



The user verifies the return values from this method.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/comsvcs/nn-comsvcs-icomcrmevents">IComCRMEvents</a>
 

 

