# Map_AddOrUpdate()

Adds/updates a key/value pair to the map.

## Syntax

\#include "[azure-iot-sdk-c/c-utility/inc/azure_c_shared_utility/map.h](../iot-c-ref-map-h.md)"  
```C
MAP_RESULT Map_AddOrUpdate(
  MAP_HANDLE    handle,
  const char *  key,
  const char *  value
);
```

## Parameters
* `handle` The handle to an existing map. 

* `key` The key to be used for this map entry. 

* `value` The value to be associated with key.

This function behaves exactly like [Map_Add](../iot-c-ref-map-h/map-add.md) except that if the key already exists in the map then it overwrites the value with the supplied value instead of returning an error. If a non-NULL pointer to a callback function was supplied via the mapFilterFunc parameter when [Map_Create](../iot-c-ref-map-h/map-create.md) was called then that callback is invoked when a new entry is added or when an existing entry is updated and if the callback returns a non-zero value then the function cancels the add/update operation and returns MAP_FILTER_REJECT.

## Return Value
If any of the input parameters are NULL then this function returns MAP_INVALID_ARG. If the filter function associated with the map rejects the entry then MAP_FILTER_REJECT is returned. In case an error occurs when the new key is added/updated in the map the function returns MAP_ERROR. If everything goes well then MAP_OK is returned.

