---                             
title: "iothub_message.h header file reference | Microsoft Docs" 
titleSuffix: "Azure IoT C SDK"            
manager: timlt                 
author: wesmc7777              
ms.author: wesmc               
ms.date: 10/11/2018                    
ms.service: "iot-hub"             
ms.custom: ""                
ms.topic: "reference"        
---                            

# IoTHubMessage_SetConnectionModuleId()

Sets connection module ID. CAUTION: SDK user should not call it directly, it is for internal use only.

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_message.h](../iothub-message-h.md)"  
```C
IOTHUB_MESSAGE_RESULT IoTHubMessage_SetConnectionModuleId(
  IOTHUB_MESSAGE_HANDLE  iotHubMessageHandle,
  const char *           connectionModuleId
);
```

## Parameters
* `iotHubMessageHandle` Handle to the message. 

* `connectionModuleId` Pointer to the module ID of connector

## Return Value
Returns IOTHUB_MESSAGE_OK if the DiagnosticData was set successfully or an error code otherwise.

