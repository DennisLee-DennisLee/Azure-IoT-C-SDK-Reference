# IoTHubDeviceClient_LL_CreateWithTransport()

Creates a IoT Hub client for communication with an existing IoT Hub using an existing transport.

## Syntax

\#include "[azure-iot-sdk-c/iothub_client/inc/iothub_device_client_ll.h](../iothub-device-client-ll-h.md)"  
```C
IOTHUB_DEVICE_CLIENT_LL_HANDLE IoTHubDeviceClient_LL_CreateWithTransport(
  const   config
);
```

## Parameters
* `config` Pointer to an [IOTHUB_CLIENT_DEVICE_CONFIG](../iothub-client-core-common-h.md#iothub_client_device_config) structure

The API *allows* sharing of a connection across multiple devices. This is a blocking call.

## Return Value
A non-NULL IOTHUB_DEVICE_CLIENT_LL_HANDLE value that is used when invoking other functions for IoT Hub client and NULL on failure.

