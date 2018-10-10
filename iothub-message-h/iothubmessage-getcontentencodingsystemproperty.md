# IoTHubMessage_GetContentEncodingSystemProperty()

Returns the content-encoding of the message payload, if defined.

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_message.h](../iothub-message-h.md)"  
```C
const char* IoTHubMessage_GetContentEncodingSystemProperty(
  IOTHUB_MESSAGE_HANDLE  iotHubMessageHandle
);
```

## Parameters
* `iotHubMessageHandle` Handle to the message.

## Return Value
A string with the content-encoding value if defined (or NULL otherwise).

