# UI

The `UI` library deals with showing and hiding UI elements.

## Methods

---

### `UI.ShowNotification(text, duration, fadeout)`
Displays mission style text on screen.

#### Parameters

`text`
: (string) The text to display.

`duration`
: (number) The amount of time in seconds to display the text for.

`fadeout`
: (bool) Whether to fade out after the `duration` has elapsed. If set to False, will have to manually clear the notification via `UI.ClearNotification()` and the `duration` parameter goes unused.

---

### `UI.ClearNotification()`
Hides any notification currently being displayed.

---

### `UI.ResetWipes()`
Clears any wipes (fade ins and fade outs) currently being displayed.