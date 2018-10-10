# IoTHubRegistryManager_CreateDevice()

Creates a device on IoT Hub.

## Syntax

\#include "[azure-iot-sdk-c/iothub_service_client/inc/iothub_registrymanager.h](../iothub-registrymanager-h.md)"  
```C
IOTHUB_REGISTRYMANAGER_RESULT IoTHubRegistryManager_CreateDevice(
  IOTHUB_REGISTRYMANAGER_HANDLE  registryManagerHandle,
  const                          deviceCreate,
  IOTHUB_DEVICE                  device
);
```

DEPRECATED:: Use IoTHubRegistryManager_CreateDevice_Ex instead 
## Parameters
* `registryManagerHandle` The handle created by a call to the create function. 

* `deviceCreate` [IOTHUB_REGISTRY_DEVICE_CREATE](../iothub-registrymanager-h.md#iothub_registry_device_create) structure containing the new device Id, primaryKey (optional) and secondaryKey (optional) 

* `device` Input parameter, if it is not NULL will contain the created device info structure

## Return Value
IOTHUB_REGISTRYMANAGER_RESULT_OK upon success or an error code upon failure.

