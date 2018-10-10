# Map_ContainsKey()

This function returns a boolean value in keyExists if the map contains a key with the same value the parameter key.

## Syntax

\#include "[azure-iot-sdk-c/c-utility/inc/azure_c_shared_utility/map.h](../iot-c-ref-map-h.md)"  
```C
MAP_RESULT Map_ContainsKey(
  MAP_HANDLE    handle,
  const char *  key,
  bool *        keyExists
);
```

## Parameters
* `handle` The handle to an existing map. 

* `key` The key that the caller wants checked. 

* `keyExists` The function writes true at the address pointed at by this parameter if the key exists in the map and false otherwise.

## Return Value
Returns MAP_OK if the check was performed successfully or an error code otherwise.

