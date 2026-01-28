# Character

The `Character` class represents any in-game character.

## Methods

### `Character:Revive()`
Restores the character's health to 100% and forces them out of the dead state.

### `Character:SetHealth(health: number)`
Sets the characters health. Ranges from 0 (0%) to 2 (200%)

### `Character:SetPosition(x: number, y: number, z: number)`
Sets the character's position.

### `Character:SetRotation(x: number, y: number, z: number, w: number)`
Sets the character's rotation as a quaternion.

### `Character:GetHealth()`

Returns the current health value. Ranges from 0 (0%) to 2 (200%)

### `Character:GetPosition()`

Returns the character's current world position.

#### Returns

`x`
: X coordinate.

`y`
: Y coordinate.

`z`
: Z coordinate.