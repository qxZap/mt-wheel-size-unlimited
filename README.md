<p align="center">
  <img src=".github/hero.png" alt="Wheel Size Unlimited" width="100%">
</p>

# Wheel Size Unlimited

Wheel radius and width tuning, and any wheel on any vehicle.

Raises the garage limits on wheel radius past the game's 0.80 - 1.20 (up to 2.0), adds a
wheel width line per axle (up to 1.7), and lets any wheel be fitted to any vehicle,
including wheels from other mods.

Settings: `Binaries\Win64\plugins\wheel_size_unlimited.ini`, section `[WheelScale]`: `Min`,
`Max`, `WidthMin`, `WidthMax`, `Step`. The old `custom_wheel_scale.ini` is moved over on
the first start, so your settings survive the rename.

Single player and hosting only: on someone else's server, that server's limits apply.

## Install

Needs [Plugin Loader](https://github.com/qxZap/mt-plugin-loader) (`version.dll`) in
`MotorTown\Binaries\Win64\`. Put `mt_plugin_WheelSizeUnlimited.dll` in
`MotorTown\Binaries\Win64\plugins\`.

## Build

`build.bat` (MSVC 2022, x64) writes `out\mt_plugin_WheelSizeUnlimited.dll`.
