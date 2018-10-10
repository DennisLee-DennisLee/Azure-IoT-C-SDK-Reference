# Prov_Device_Register_Device()

## Syntax

\#include "[azure-iot-sdk-c/provisioning_client/inc/azure_prov_client/prov_device_client.h](../prov-device-client-h.md)"  
```C
PROV_DEVICE_RESULT Prov_Device_Register_Device(
  PROV_DEVICE_HANDLE                           prov_device_handle,
  PROV_DEVICE_CLIENT_REGISTER_DEVICE_CALLBACK  register_callback,
  void *                                       user_context,
  PROV_DEVICE_CLIENT_REGISTER_STATUS_CALLBACK  register_status_callback,
  void *                                       status_user_context
);
```

