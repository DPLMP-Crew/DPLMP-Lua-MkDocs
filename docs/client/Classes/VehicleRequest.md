# VehicleRequest

The `VehicleRequest` class represents a request to spawn a vehicle to the `VehicleManager`. May be fulfilled.

## Methods

---

### `VehicleRequest:GetState()`
Retrieves the current spawned state of the vehicle.

#### Returns

`state`
: (number) Possible values are `VehicleManager.Processing`, `VehicleManager.Failed`, or `VehicleManager.Spawned`.