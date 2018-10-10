# prov_sc_delete_individual_enrollment()

Deletes a individual device enrollment record on the Provisioning Service.

## Syntax

\#include "[azure-iot-sdk-c/provisioning_service_client/inc/prov_service_client/provisioning_service_client.h](../provisioning-service-client-h.md)"  
```C
int prov_sc_delete_individual_enrollment(
  PROVISIONING_SERVICE_CLIENT_HANDLE  prov_client,
  INDIVIDUAL_ENROLLMENT_HANDLE        enrollment
);
```

## Parameters
* `prov_client` The handle used for connecting to the Provisioning Service. 

* `enrollment` The handle for the target individual enrollment. Will be matched based on registration id and etag.

## Return Value
0 upon success, a non-zero number upon failure.

