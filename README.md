# Modulation Lerp

This is a Max For Live device that calculates a linearly interpolated value between two input values. This lets you adjust the minimum and maximum constraints of a third signal.

![How it Looks](images/device.gif)

[Video showing it in action.](https://www.youtube.com/watch?v=YfRTARPEUME)

## Installation

[Download the newest .amxd file from the releases page](https://github.com/zsteinkamp/m4l-Modulation-Lerp/releases) or clone this repository, and drag the `Modulation Lerp.amxd` device into a track in Ableton Live.

Note: If you want to open and edit the non-frozen device, you will need to have [zs.mapper](https://github.com/zsteinkamp/m4l-zs.mapper) installed. [Follow the installation instructions](https://github.com/zsteinkamp/m4l-zs.mapper) there.

## Changelog

* 2025-10-01 [v5](https://github.com/zsteinkamp/m4l-Modulation-Lerp/releases/download/v5/ModulationLerp-v5.amxd) - Update checks; Fix bipolar mod bug.
* 2024-10-29 [v4](https://github.com/zsteinkamp/m4l-Modulation-Lerp/releases/download/v4/ModulationLerp-v4.amxd) - Add non-blocking telemetry ping on load. Does not send any identifying information, only the plugin name, the local computer name, type of computer, and CPU type. I just want to see which plugins are used the most.
* 2024-08-17 [v3](https://github.com/zsteinkamp/m4l-Modulation-Lerp/releases/download/v3/Modulation.Lerp.v3.amxd) - Support Live 12's new modulation mode; Visual improvments.
* 2024-02-05 [v2](https://github.com/zsteinkamp/m4l-Modulation-Lerp/raw/main/frozen/Modulation%20Lerp%20v2.amxd) - Fix problem with additional modulation destinations. Thanks @Michaelknubben!
* 2023-04-10 [v1](https://github.com/zsteinkamp/m4l-Modulation-Lerp/raw/main/frozen/Modulation%20Lerp%20v1.amxd) - Initial Release.

## Usage

Map or move `Input A`, `Input B`, and the `A <=> B` knobs. Map the result to up to 8 other parameters.

## TODO

* ...

## Contributing

Thanks to Ben Sulzinsky for sending me the idea for this!

I'd love it if others extended this device. If you would like to contribute, simply fork this repo, make your changes, and open a pull request and I'll have a look.
