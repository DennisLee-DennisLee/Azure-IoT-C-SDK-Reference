# IoTHubRegistryManager_CreateModule()

Creates a module on IoT Hub.

## Syntax

\#include "[azure-iot-sdk-c/iothub_service_client/inc/iothub_registrymanager.h](../iothub-registrymanager-h.md)"  
```C
IOTHUB_REGISTRYMANAGER_RESULT IoTHubRegistryManager_CreateModule(
  IOTHUB_REGISTRYMANAGER_HANDLE  registryManagerHandle,
  const                          moduleCreate,
  IOTHUB_MODULE                  module
);
```

## Parameters
* `registryManagerHandle` The handle created by a call to the create function. 

* `moduleCreate` [IOTHUB_REGISTRY_MODULE_CREATE](../iothub-registrymanager-h.md#iothub_registry_module_create) structure containing the existing deviceID, new module Id, primaryKey (optional) and secondaryKey (optional) 

* `module` Input parameter, if it is not NULL will contain the created module info structure

## Return Value
IOTHUB_REGISTRYMANAGER_RESULT_OK upon success or an error code upon failure.

