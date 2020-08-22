# vMenu-Improved
vMenu is server sided menu for FiveM servers, including full\* permission support.

This version (vMenu-Improved) has been modified by dotexe to add additional features.


\*(Some features do not have permissions support as they are either harmless or it'd just be silly to deny them. However, they will be disabled if you deny access to the submenu that they are a part of (eg: unlimited stamina in Player Options will be disabled if you deny `vMenu.PlayerOptions.Menu`.))

--------

# Download & Installation & Permissions

## Download

Click [here](https://github.com/original-dotexe/vMenu-Improved/releases) to go to the releases page and download it.

--------

## Installation
Please follow the instructions over at the [vMenu docs](https://docs.vespura.com/vmenu/installation)

## Zap Hosting
If you're using Zap Hosting, you may find that moving the `permissions.cfg` file to the same folder as your `server.cfg` file may not work correctly (it could get reset every time you restart your server).

If this is the case, leave your `permissions.cfg` file here: `/resources/vMenu/config/permissions.cfg` and add the following to the very top of your server.cfg file: `exec resources/vMenu/config/permissions.cfg` (instead of `exec permissions.cfg`).

You can also use ZAP Hosting's one-click installer for vMenu. Get a ZAP-Hosting server with a 10% lifetime discount [HERE](https://zap-hosting.com/vespura) and make sure to use `Vespura-a-3715` at checkout.

--------

## Trouble shooting & support
Take a look at the docs first of all. I will ignore you if your question is answered on the docs or the forum topic.

- [docs](https://docs.vespura.com/vmenu/)
- [forum topic](https://vespura.com/vmenu)
- [discord](https://vespura.com/discord)


--------

## Permissions 
Click [here](https://docs.vespura.com/vmenu/permissions-ref) for permissions information.

## Configuration
Click [here](https://docs.vespura.com/vmenu/configuration) for configuration options information.


--------


## MenuAPI
Starting from vMenu v2.1.0, vMenu will be using [MenuAPI (MAPI)](https://github.com/TomGrobbe/MenuAPI), a custom menu API designed specifically for vMenu by me.

vMenu v2.0.0 and earlier was [using a modified version of NativeUI](https://github.com/TomGrobbe/NativeUI), originally by [Guad](https://github.com/Guad/NativeUI), but converted to FiveM by the CitizenFX Collectives and myself (updated/refactored).


--------

## License
**For an updated license, check the license.md file. That file will always overrule anything mentioned in the readme.md**


Tom Grobbe - https://www.vespura.com/
dotexe - https://www.dotexe.cf

	Copyright © 2017-2020

----

You can use and edit this code to your liking. However don't ever claim it to be your own code and always provide proper credit.
I will, however, not help you if you want to modify my code.
