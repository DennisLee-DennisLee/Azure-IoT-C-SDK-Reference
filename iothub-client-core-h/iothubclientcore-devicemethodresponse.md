# IoTHubClientCore_DeviceMethodResponse()

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_client_core.h](../iothub-client-core-h.md)"  
```C
IOTHUB_CLIENT_RESULT IoTHubClientCore_DeviceMethodResponse(
  IOTHUB_CLIENT_CORE_HANDLE  iotHubClientHandle,
  METHOD_HANDLE              methodId,
  const unsigned char *      response,
  size_t                     response_size,
  int                        statusCode
);
```

