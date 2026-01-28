# Character

The `Character` class represents any in-game character.

## Methods

### `Character:Revive()`
Restores the character's health to 100% and forces them out of the dead state.

### `Character:SetHealth(health)`
Sets the characters health. Ranges from 0 (0%) to 2 (200%)

#### Parameters

`health`
: (number)

### `Character:SetPosition(x, y)`
Sets the character's position.

#### Parameters

`x`
: (number)

`y`
: (number)

`z`
: (number)

### `Character:SetRotation(x, y, z, w)`
Sets the character's rotation as a quaternion.

#### Parameters

`x`
: (number)

`y`
: (number)

`z`
: (number)

`w`
: (number)

### `Character:GetHealth()`

Returns the current health value. Ranges from 0 (0%) to 2 (200%)

#### Returns

`health`
: (number)

### `Character:GetPosition()`

Returns the character's current world position.

#### Returns

`x`
: (number)

`y`
: (number)

`z`
: (number)