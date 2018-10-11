---                             
title: "lock.h header file reference | Microsoft Docs" 
titleSuffix: "Azure IoT C SDK"            
manager: timlt                 
author: wesmc7777              
ms.author: wesmc               
ms.date: 10/11/2018                    
ms.service: "iot-hub"             
ms.custom: ""                
ms.topic: "reference"        
---                            

# lock.h 

A minimalistic platform agnostic lock abstraction for thread synchronization.

## Includes

\#include "azure_c_shared_utility/macro_utils.h"  
\#include "[azure_c_shared_utility/umock_c_prod.h](umock-c-prod-h.md)"  

## Detailed Description

The Lock component is implemented in order to achieve thread synchronization, as we may have a requirement to consume locks across different platforms. This component exposes some generic APIs so that it can be extended for platform specific implementations.

## Functions

Function Name                  | Description                                
--------------------------------|---------------------------------------------
[LOCK_RESULTStrings](./lock-h/lock-resultstrings.md)            | 
[LOCK_RESULT_FromString](./lock-h/lock-result-fromstring.md)            | 
[Lock_Init](./lock-h/lock-init.md)            | This API creates and returns a valid lock handle.
[Lock](./lock-h/lock.md)            | Acquires a lock on the given lock handle. Uses platform specific mutex primitives in its implementation.
[Unlock](./lock-h/unlock.md)            | Releases the lock on the given lock handle. Uses platform specific mutex primitives in its implementation.
[Lock_Deinit](./lock-h/lock-deinit.md)            | The lock instance is destroyed.

## Macro definitions

#### LOCK_RESULT_VALUES

```C
#define LOCK_RESULT_VALUES \
        LOCK_OK, \
        LOCK_ERROR 
```

## Enumeration types

#### LOCK_RESULT

Enumeration specifying the lock status. 

```C
enum LOCK_RESULT {
  LOCK_OK,
  LOCK_ERROR
}
```

## Type definitions

#### LOCK_HANDLE

```C
typedef void* LOCK_HANDLE;
```

