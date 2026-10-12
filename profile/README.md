# Oxygen Not Included gameplay mods

Gameplay and performance mods for Oxygen Not Included. This organization holds mods only.
The simulation platform (the replacement simulation library, the `OniFramework` API, the
documentation and the development tools) lives in
[Salacious-Oni-Dev](https://github.com/Salacious-Oni-Dev).

## Mods

| mod | what it is | status |
|---|---|---|
| [oni-time-travel](https://github.com/Salacious-Oni-Mods/oni-time-travel) | a time machine that sends a duplicant to a prehistoric version of your home asteroid and back | alpha |
| [oni-backrooms](https://github.com/Salacious-Oni-Mods/oni-backrooms) | fake rooms behind the backwall that look like they go back into the screen; first use, a critter kennel whose critters are simulated cheaply inside | alpha preview |
| [oni-perf-mod](https://github.com/Salacious-Oni-Mods/oni-perf-mod) | frame-rate and load-time fixes: work the game repeats every frame for nothing is skipped or run at the rate the game was tuned for; an optional fast loader keeps the window live while a large colony loads | alpha |
| [oni-gc-runtime](https://github.com/Salacious-Oni-Mods/oni-gc-runtime) | shorter garbage-collection freezes: a rebuilt Mono runtime with parallel marking, and a mod that moves collections to when the game window is not in focus | alpha |

## Releases

Current: the mods released alongside the SDK's [Alpha 2 (`v0.1.0-alpha.2`)](https://github.com/Salacious-Oni-Dev/oni-sdk-docs/releases/tag/v0.1.0-alpha.2)

Each link opens that mod's releases, newest first:

- [oni-time-travel releases](https://github.com/Salacious-Oni-Mods/oni-time-travel/releases)
- [oni-backrooms releases](https://github.com/Salacious-Oni-Mods/oni-backrooms/releases)
- [oni-perf-mod releases](https://github.com/Salacious-Oni-Mods/oni-perf-mod/releases)
- [oni-gc-runtime releases](https://github.com/Salacious-Oni-Mods/oni-gc-runtime/releases)

## Requirements

`oni-perf-mod` and `oni-gc-runtime` run on the unmodified game. `oni-time-travel` and
`oni-backrooms` are built on the ONI Framework Library: they need the SDK's `OniFramework.Library`
mod (from the `oni-framework-api` release 0.1.0-alpha.2; each mod's README names the lowest
library version it needs), and neither the `OniFramework` mod nor the replacement `SimDLL.dll`. The SDK guide
[Installing and removing](https://github.com/Salacious-Oni-Dev/oni-sdk-docs/blob/main/guides/installing.md)
says how to install the library and how to get back to the unmodified game. Each mod's README
lists the DLC it needs.

## Credits

Oxygen Not Included is developed and published by Klei Entertainment. This project is not
affiliated with or endorsed by Klei.
How this project follows Klei's modding guidelines, rule by rule: [COMPLIANCE](https://github.com/Salacious-Oni-Dev/oni-sdk-docs/blob/main/COMPLIANCE.md).

Development of this project uses AI coding assistants. All changes are reviewed, tested and
released by the maintainer.
