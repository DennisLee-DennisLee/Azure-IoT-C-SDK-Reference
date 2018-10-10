# IoTHubRegistryManager_GetDeviceList()

## Syntax

\#include "[azure-iot-sdk-c/iothub_service_client/inc/iothub_registrymanager.h](../iot-c-ref-iothub-registrymanager-h.md)"  
```C
IOTHUB_REGISTRYMANAGER_RESULT IoTHubRegistryManager_GetDeviceList(
  IOTHUB_REGISTRYMANAGER_HANDLE  registryManagerHandle,
  size_t                         numberOfDevices,
  SINGLYLINKEDLIST_HANDLE        deviceList
);
```

