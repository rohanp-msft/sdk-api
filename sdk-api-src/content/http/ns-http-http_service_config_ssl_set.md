---
UID: NS:http._HTTP_SERVICE_CONFIG_SSL_SET
title: HTTP_SERVICE_CONFIG_SSL_SET (http.h)
description: Used to add a new record to the SSL store or retrieve an existing record from it.
old-location: http\http_service_config_ssl_set.htm
tech.root: http
ms.assetid: 23adda0b-907d-4804-9c12-e549af4f18c4
ms.date: 12/05/2018
ms.keywords: '*PHTTP_SERVICE_CONFIG_SSL_SET, HTTP_SERVICE_CONFIG_SSL_SET, HTTP_SERVICE_CONFIG_SSL_SET structure [HTTP], PHTTP_SERVICE_CONFIG_SSL_SET, PHTTP_SERVICE_CONFIG_SSL_SET structure pointer [HTTP], _http_http_service_config_ssl_set, http.http_service_config_ssl_set, http/HTTP_SERVICE_CONFIG_SSL_SET, http/PHTTP_SERVICE_CONFIG_SSL_SET'
f1_keywords:
- http/HTTP_SERVICE_CONFIG_SSL_SET
dev_langs:
- c++
req.header: http.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Http.h
api_name:
- HTTP_SERVICE_CONFIG_SSL_SET
targetos: Windows
req.typenames: HTTP_SERVICE_CONFIG_SSL_SET, *PHTTP_SERVICE_CONFIG_SSL_SET
req.redist: 
ms.custom: 19H1
---

# HTTP_SERVICE_CONFIG_SSL_SET structure


## -description


The 
<b>HTTP_SERVICE_CONFIG_SSL_SET</b> structure is used to add a new record to the SSL store or retrieve an existing record from it. An instance of the structure is used to pass data in to the 
<a href="https://docs.microsoft.com/windows/desktop/api/http/nf-http-httpsetserviceconfiguration">HTTPSetServiceConfiguration</a> function through the <i>pConfigInformation</i> parameter or to retrieve data from the 
<a href="https://docs.microsoft.com/windows/desktop/api/http/nf-http-httpqueryserviceconfiguration">HTTPQueryServiceConfiguration</a> function through the <i>pOutputConfigInformation</i> parameter when the <i>ConfigId</i> parameter of either function is equal to <b>HTTPServiceConfigSSLCertInfo</b>.


## -struct-fields




### -field KeyDesc

An 
<a href="https://docs.microsoft.com/windows/desktop/api/http/ns-http-http_service_config_ssl_key">HTTP_SERVICE_CONFIG_SSL_KEY</a> structure that identifies the SSL certificate record.


### -field ParamDesc

An 
<a href="https://docs.microsoft.com/windows/desktop/api/http/ns-http-http_service_config_ssl_param">HTTP_SERVICE_CONFIG_SSL_PARAM</a> structure that holds the contents of the specified SSL certificate record.


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/http/nf-http-httpqueryserviceconfiguration">HTTPQueryServiceConfiguration</a>



<a href="https://docs.microsoft.com/windows/desktop/api/http/nf-http-httpsetserviceconfiguration">HTTPSetServiceConfiguration</a>



<a href="https://docs.microsoft.com/windows/desktop/api/http/ns-http-http_service_config_ssl_key">HTTP_SERVICE_CONFIG_SSL_KEY</a>



<a href="https://docs.microsoft.com/windows/desktop/api/http/ns-http-http_service_config_ssl_param">HTTP_SERVICE_CONFIG_SSL_PARAM</a>
 

 

