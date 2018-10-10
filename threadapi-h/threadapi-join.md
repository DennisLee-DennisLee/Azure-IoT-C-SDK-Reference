# ThreadAPI_Join()

Blocks the calling thread by waiting on the thread identified by the threadHandle argument to complete.

## Syntax

\#include "[azure-iot-sdk-c/c-utility/inc/azure_c_shared_utility/threadapi.h](../threadapi-h.md)"  
```C
THREADAPI_RESULT ThreadAPI_Join(
  THREAD_HANDLE  threadHandle,
  int *          res
);
```

## Parameters
* `threadHandle` The handle of the thread to wait for completion. 

* `res` The result returned by the thread which is passed to the [ThreadAPI_Exit](../threadapi-h/threadapi-exit.md) function.

When the threadHandle thread completes, all resources associated with the thread must be released and the thread handle will no longer be valid.

## Return Value
THREADAPI_OK if the API call is successful or an error code in case it fails.

