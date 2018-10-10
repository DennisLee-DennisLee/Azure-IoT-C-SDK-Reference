# prov_sc_set_trace()

Sets tracing/logging of http communications on or off.

## Syntax

\#include "[azure-iot-sdk-c/provisioning_service_client/inc/prov_service_client/provisioning_service_client.h](../iot-c-ref-provisioning-service-client-h.md)"  
```C
void prov_sc_set_trace(
  PROVISIONING_SERVICE_CLIENT_HANDLE  prov_client,
  TRACING_STATUS                      status
);
```

## Parameters
* `prov_client` The handle for the connection that should be traced. 

* `status` The tracing status to set.

