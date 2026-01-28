# Hooks

The `Hooks` library deals with listening and reacting to game events via Lua coroutines.

## Methods

---

### `Hooks.AddHook(hookType, callback)`
Registers a hook that listens for a specific Hook Type event.

#### Parameters

`hookType`
: (number) The event to listen for.

`callback`
: (Function) The function to execute when the Hook is fired.

## Hook Types

---

### `Hooks.OnLocalPlayerDead`
Fires when the health of the local player character reaches 0.

#### Usage:
```lua
Hooks.AddHook(Hooks.OnLocalPlayerDead, function())
```

### `Hooks.OnFrameUpdate`
Fired every frame.

#### Parameters

`delta`
: (number) Time elapsed between this frame and the last, or delta time.

#### Usage:
```lua
Hooks.AddHook(Hooks.OnFrameUpdate, function(deltaTime))
```