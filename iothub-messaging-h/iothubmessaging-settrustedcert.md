---                             
title: "iothub_messaging.h header file reference | Microsoft Docs" 
titleSuffix: "Azure IoT C SDK"            
manager: timlt                 
author: wesmc7777              
ms.author: wesmc               
ms.date: 10/11/2018                    
ms.service: "iot-hub"             
ms.custom: ""                
ms.topic: "reference"        
---                            

# IoTHubMessaging_SetTrustedCert()

This function is meant to be called by the user when to set the trusted certificate on the tls connection.

## Syntax

\#include "[azure-iot-sdk-c/iothub_service_client/inc/iothub_messaging.h](../iothub-messaging-h.md)"  
```C
IOTHUB_MESSAGING_RESULT IoTHubMessaging_SetTrustedCert(
  IOTHUB_MESSAGING_CLIENT_HANDLE  messagingClientHandle,
  const char *                    trusted_cert
);
```

## Parameters
* `messagingHandle` The handle created by a call to the create function. 

* `trusted_cert` The trusted certificate that will be set.

## Return Value
IOTHUB_CLIENT_OK upon success or an error code upon failure.

