# VehicleManager

The `VehicleManager` library deals with the spawning and despawning of vehicles.

## Methods

---

### `VehicleManager.CreateVehicle(model, x, y, z, angle, snapToGround)`
Requests a vehicle to be created.

#### Parameters

`model`
: (number) The ID of the vehicle model.

`x`
: (number) X coordinate.

`y`
: (number) Y coordinate.

`z`
: (number) Z coordinate.

`angle`
: (number) Yaw in radians.

`snapToGround`
: (bool) Whether to snap the car to the ground.

#### Returns

`vehicleRequest`
: (VehicleRequest) An instance of the vehicle request to keep track of its creation.

---

### `VehicleManager.DestroyVehicle(vehicleRequest)`
Destroys a vehicle or cancels a vehicle request.

#### Parameters

`vehicleRequest`
: (VehicleRequest) The request, as returned by CreateVehicle, to cancel (or to delete, if the vehicle has been spawned)

## Vehicle Spawn States

### `VehicleManager.Processing`
Vehicle is still being loaded, hasn't been spawned yet.

### `VehicleManager.Failed`
Vehicle failed to spawn.

### `VehicleManager.Spawned`
Vehicle spawned successfully.