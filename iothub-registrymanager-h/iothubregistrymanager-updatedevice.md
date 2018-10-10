# IoTHubRegistryManager_UpdateDevice()

Updates a device on IoT Hub.

## Syntax

\#include "[azure-iot-sdk-c/iothub_service_client/inc/iothub_registrymanager.h](../iothub-registrymanager-h.md)"  
```C
IOTHUB_REGISTRYMANAGER_RESULT IoTHubRegistryManager_UpdateDevice(
  IOTHUB_REGISTRYMANAGER_HANDLE  registryManagerHandle,
  IOTHUB_REGISTRY_DEVICE_UPDATE  deviceUpdate
);
```

DEPRECATED:: Use IoTHubRegistryManager_UpdateDevice_Ex instead 
## Parameters
* `registryManagerHandle` The handle created by a call to the create function. 

* `deviceUpdate` [IOTHUB_REGISTRY_DEVICE_UPDATE](../iothub-registrymanager-h.md#iothub_registry_device_update) structure containing the new device Id, primaryKey (optional), secondaryKey (optional), authentication method, and status

## Return Value
IOTHUB_REGISTRYMANAGER_RESULT_OK upon success or an error code upon failure.

