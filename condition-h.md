# condition.h 

Stub comment for brief. Please update this comment.

## Includes

\#include "azure_c_shared_utility/macro_utils.h"  
\#include "[azure_c_shared_utility/lock.h](lock-h.md)"  
\#include "[azure_c_shared_utility/umock_c_prod.h](umock-c-prod-h.md)"  

## Detailed Description

Stub comment for details. Please update this comment.

## Functions

Function Name                  | Description                                
--------------------------------|---------------------------------------------
[COND_RESULTStrings](./condition-h/cond-resultstrings.md)            | 
[COND_RESULT_FromString](./condition-h/cond-result-fromstring.md)            | 
[Condition_Init](./condition-h/condition-init.md)            | This API creates and returns a valid condition handle.
[Condition_Post](./condition-h/condition-post.md)            | unblock all currently working condition.
[Condition_Wait](./condition-h/condition-wait.md)            | block on the condition handle unti the thread is signalled or until the timeout_milliseconds is reached.
[Condition_Deinit](./condition-h/condition-deinit.md)            | The condition instance is deinitialized.

## Macro definitions

#### COND_RESULT_VALUES

```C
#define COND_RESULT_VALUES \
        COND_OK, \
        COND_INVALID_ARG, \
        COND_ERROR, \
        COND_TIMEOUT 
```

## Enumeration types

#### COND_RESULT

Enumeration specifying the lock status. 

```C
enum COND_RESULT {
  COND_OK,
  COND_INVALID_ARG,
  COND_ERROR,
  COND_TIMEOUT
}
```

## Type definitions

#### COND_HANDLE

```C
typedef void* COND_HANDLE;
```

