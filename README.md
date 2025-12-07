# EKS Emergency Doors

EKS Emergency Doors provides an extensible system for fire appliances and ambulances to open and close shutters or rear doors using configurable third-eye interaction points. 
Sound effects play for all nearby players with distance-based volume, and each vehicle can be configured to use doors, extras, or optional animations.

Fire appliances can operate shutters through door indexes or extras, while ambulances use standard rear door behaviour. 
Interaction points are fully position-based, allowing you to define precise offsets for each model.

## Configuration

Key details:

* Fire vehicles use `type = "doors"` or `type = "extra"`.
* Extras may be a single ID (`shutterExtra = 1`) or a list (`shutterExtra = {1, 2, 3}`).
* `optionalExtraOnOpen` enables one extra only while shutters remain open.
* `offsets` defines all third-eye interaction points for that model.
* `/vehiclecoords` lets you select and print offsets directly from in-game vehicles.

## Installation

Place the resource in your server and add:

ensure EKS_EmergencyDoors

Modify `config.lua` to match your vehicle models and offsets.

## Support

For help or bug reports, join our Discord and open a support ticket:
https://discord.gg/busQ9w6dqa