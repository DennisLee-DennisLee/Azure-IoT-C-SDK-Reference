# prov_sc_delete_enrollment_group_by_param()

Deletes a device enrollment group record on the Provisioning Service.

## Syntax

\#include "[azure-iot-sdk-c/provisioning_service_client/inc/prov_service_client/provisioning_service_client.h](../provisioning-service-client-h.md)"  
```C
int prov_sc_delete_enrollment_group_by_param(
  PROVISIONING_SERVICE_CLIENT_HANDLE  prov_client,
  const char *                        group_id,
  const char *                        etag
);
```

## Parameters
* `prov_client` The handle used for connecting to the Provisioning Service. 

* `group_id` The enrollment group id of the target enrollment group. 

* `etag` The etag of the target enrollment group. If given as "*", will match any etag.

## Return Value
0 upon success, a non-zero number upon failure.

