# IoTHubClientCore_LL_SendEventAsync()

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_client_core_ll.h](../iothub-client-core-ll-h.md)"  
```C
IOTHUB_CLIENT_RESULT IoTHubClientCore_LL_SendEventAsync(
  IOTHUB_CLIENT_CORE_LL_HANDLE               iotHubClientHandle,
  IOTHUB_MESSAGE_HANDLE                      eventMessageHandle,
  IOTHUB_CLIENT_EVENT_CONFIRMATION_CALLBACK  eventConfirmationCallback,
  void *                                     userContextCallback
);
```

