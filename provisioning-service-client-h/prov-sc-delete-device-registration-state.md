# prov_sc_delete_device_registration_state()

Deletes a device registration state on the Provisioning Service.

## Syntax

\#include "[azure-iot-sdk-c/provisioning_service_client/inc/prov_service_client/provisioning_service_client.h](../provisioning-service-client-h.md)"  
```C
int prov_sc_delete_device_registration_state(
  PROVISIONING_SERVICE_CLIENT_HANDLE  prov_client,
  DEVICE_REGISTRATION_STATE_HANDLE    reg_state
);
```

## Parameters
* `prov_client` The handle used for connecting to the Provisioning Service. 

* `reg_state` The handle for the target device registration state.

## Return Value
0 upon success, a non-zero number upon failure.

