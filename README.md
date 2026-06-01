# FS25 Custom Vehicle Reset Points

**Author:** FarmerDOOM

## Overview

Custom Vehicle Reset Points allows you to assign custom reset locations to vehicles and implements.

Instead of resetting equipment back to the shop (you still can via map), you can save a dedicated parking location anywhere on your farm and instantly return equipment to that location whenever needed.

I originally built this mod for my own gameplay. I like keeping equipment organized and parked where it belongs, but I don't always want to spend time driving machinery back across the map after every job.

This mod helps keep your farm organized while reducing unnecessary travel and downtime.

---

## Features

* Save custom reset locations for vehicles and implements
* Restore equipment directly to its assigned parking location
* Supports tractors, trailers, implements, and attachments
* Preserves vehicle orientation and parking direction
* Uses Farming Simulator 25's native reset system for maximum compatibility
* Supports attached equipment through a quick reset function
* Multiplayer compatible

---

## Controls

### Vehicles Menu

Select a vehicle or implement from the Vehicles menu.

| Key | Function                                              |
| --- | ----------------------------------------------------- |
| L   | Save current location as reset point                  |
| O   | Reset selected vehicle or implement to saved location |

### Attached Equipment

| Key      | Function                                                   |
| -------- | ---------------------------------------------------------- |
| CTRL + O | Detach and reset the currently selected attached implement |

Use the game's standard attachment selection system (G key by default) to choose which implement should be reset.

---

## Important Information

This mod intentionally uses Farming Simulator 25's native reset functionality.

By using the game's built-in reset system, attached and folded equipment is handled safely before being returned to its saved location.

Because the vanilla reset system is used:

* Some trailers may be emptied during reset
* Certain fillable equipment may lose contents during reset
* Equipment behavior will match Farming Simulator's standard reset behavior

For players who want to preserve trailer contents during reset, I recommend:

**Disable Emptying on Reset** by MechNoxer

Future versions may include optional built-in support for preserving fill levels.

---

## Installation

1. Download the latest release
2. Place the ZIP file into your Farming Simulator 25 mods folder

Typical location:

```text
Documents\My Games\FarmingSimulator2025\mods
```

3. Enable the mod when loading your save game

---

## Known Limitations

* Reset points are saved per vehicle or implement
* Resetting equipment uses the game's standard reset behavior
* Equipment must exist in the save before a reset point can be assigned

---

## Version History

### v1.0.0.0

Initial public release

* Custom reset locations
* Vehicle menu integration
* Saved orientation support
* Attached implement reset support
* Vanilla reset pipeline integration
* Multiplayer support

---

## Credits

Created by FarmerDOOM

Special thanks to the Farming Simulator modding community for documentation, examples, and reference implementations used during development.
