# Lock()

Acquires a lock on the given lock handle. Uses platform specific mutex primitives in its implementation.

## Syntax

\#include "[azure-iot-sdk-c/c-utility/inc/azure_c_shared_utility/lock.h](../iot-c-ref-lock-h.md)"  
```C
LOCK_RESULT Lock(
  LOCK_HANDLE  handle
);
```

## Parameters
* `handle` A valid handle to the lock.

## Return Value
Returns LOCK_OK when a lock has been acquired and LOCK_ERROR when an error occurs.

