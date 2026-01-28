# Core

The `Core` library deals mostly with coroutines and code execution.

## Methods

---

### `Core.CreateCoroutine(callback, arguments)`
Creates a coroutine, immediately beginning execution of it.

#### Parameters

`callback`
: (Function) The Lua function to execute.

`arguments`
: Arguments to pass to the function, if any.

#### Returns

`coroutineId`
: (number) Unique identifier for the coroutine.

---

### `Core.AbortCoroutine(coroutineId)`
Aborts a coroutine by its Id, immediately stopping its execution.

#### Parameters

`coroutineId`
: (number) Id of the coroutine to abort. As returned from `Core.CreateCoroutine`.

## Fields

---

### `Core.DeltaTime`
(number) The time elapsed between this frame and the last.