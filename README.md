# Domoticz fork with BleBox suport

The **master** branch here contains a major rework of BleBox devices support for Domoticz.

## Features

- 11 BleBox devices supported (with minimal, reasonable functionality)
- strong focus on quality (code/functionality/extensibility)
- extensive unit tests


## How do I use this?

Build exactly the same way as the official Domoticz version.

Builds (for amd64 for now) are here: https://github.com/gadgetmobile/domoticz-blebox-builds

You may want to disable upgrades (which would give you the official version, without BleBox support).


## Why is this not in the Official Domoticz version?

These changes were rejected by one of the Domoticz maintainers (for no acceptable reason IMHO).

I personally highly recommend migrating from Domoticz to e.g. [Home Assistant](https://www.home-assistant.io/) as soon as you can. (There are lots of good reasons for doing so).

However, if you're stuck with Domoticz, this fork is for you. (It closely follows the offical version, so you can BleBox support and lose nothing from the offical version).


## Issues / support

Feel free to report them here: https://github.com/gadgetmobile/domoticz-blebox-builds

I've put in too much time into making Domoticz better, and I've happily switched to Home Assistant.

So I don't plan to support this further, but do report any BleBox-specific issues.
