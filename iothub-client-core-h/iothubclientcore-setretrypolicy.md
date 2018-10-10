# IoTHubClientCore_SetRetryPolicy()

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_client_core.h](../iothub-client-core-h.md)"  
```C
IOTHUB_CLIENT_RESULT IoTHubClientCore_SetRetryPolicy(
  IOTHUB_CLIENT_CORE_HANDLE   iotHubClientHandle,
  IOTHUB_CLIENT_RETRY_POLICY  retryPolicy,
  size_t                      retryTimeoutLimitInSeconds
);
```

