# IoTHubMessage_Clone()

Creates a new IoT hub message with the content identical to that of the iotHubMessageHandle parameter.

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_message.h](../iot-c-ref-iothub-message-h.md)"  
```C
IOTHUB_MESSAGE_HANDLE IoTHubMessage_Clone(
  IOTHUB_MESSAGE_HANDLE  iotHubMessageHandle
);
```

## Parameters
* `iotHubMessageHandle` Handle to the message that is to be cloned.

## Return Value
A valid IOTHUB_MESSAGE_HANDLE if the message was successfully cloned or NULL in case an error occurs.

