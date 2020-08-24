# OpenMod Plugins

## Installing and Managing OpenMod Plugins
- To install a plugin, run the command `openmod install <NuGet Package ID[:Version]> [-Pre]>`.  
- To update plugins, do the same as to install it.
- To uninstall a plugin, run `openmod uninstall <NuGet Package ID>`.

For more information, use the `help` command: e.g. use `help openmod install`.

## OpenMod Plugins List
| Name                              | NuGet Package ID                                                                                     | Author    | Platform | Description                                                                                                    | License      | Source Code                                                                                       |
|-----------------------------------|------------------------------------------------------------------------------------------------------|-----------|----------|----------------------------------------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------|
| AdvancedThief                     | [SS.AdvancedThief](https://www.nuget.org/packages/SS.AdvancedThief/)                                 | Senior S  | Unturned | This plugin add a command to have a best rol in Roleplays servers!                                             | EUPL-1.2     | [GitHub](https://github.com/Senior-S/AdvancedThief-OpenMod)                                       |
| BuilderMode                       | [SS.BuilderMode](https://www.nuget.org/packages/SS.BuilderMode/)                                     | Senior S  | Unturned | A simple/shitty plugin to build with more facility.                                                            | EUPL-1.2     | [GitHub](https://github.com/Senior-S/BuilderMode-OpenMod)                                         |
| DeathMessenger                    | [Tortellio.DeathMessenger](https://www.nuget.org/packages/Tortellio.DeathMessenger)                  | Tortellio | Unturned | Sending death messages based on player death causes.                                                           | EUPL-1.2     | [GitHub](https://github.com/Tortellio/DeathMessenger)                                             |
| Global Ban                        | [Pustalorc.GlobalBan](https://www.nuget.org/packages/Pustalorc.GlobalBan/)                           | Pustalorc | Unturned | Keep bans globally between servers. Supports HWID & IP banning.                                                | EUPL-1.2     | [GitHub](https://github.com/Pustalorc/GlobalBan/)                                                 |
| HiddenIdentity                    | [SS.HiddenIdentity](https://www.nuget.org/packages/ss.hiddenidentity/)                               | Senior S  | Unturned | Now you can be a good thief, if you have a mask anyone cant see your name!                                     | EUPL-1.2     | [GitHub](https://github.com/Senior-S/HiddenIdentity-OpenMod/)                                     |
| JobsOnlineUI                      | [SS.JobsOnlineUI](https://www.nuget.org/packages/ss.jobsonlineui/)                                   | Senior S  | Unturned | A simple plugin to check the players or jobs online while press a key.                                         | EUPL-1.2     | [GitHub](https://github.com/Senior-S/JobsOnlineUI-OpenMod)                                        |
| NewEssentials                     | [Kr4ken.NewEssentials](https://www.nuget.org/packages/Kr4ken.NewEssentials)                          | Kr4ken    | Unturned | The new essential plugin for Unturned. This project aims to be a replacement for uEssentials built on OpenMod. | GPL-3.0-only | [GitHub](https://github.com/Kr4ken-9/NewEssentials)                                               |
| OpenMod RocketMod Bridge          | [OpenMod.Rocket.Unturned](https://www.nuget.org/packages/OpenMod.Rocket.Unturned)                    | OpenMod   | Unturned | Legacy RM4 support for OpenMod                                                                                 | MIT          | [GitHub](https://github.com/openmod/OpenMod/tree/master/unturned/rocketmod)                       |
| OpenMod RocketMod Permission Link | [OpenMod.Rocket.PermissionLink](https://www.nuget.org/packages/OpenMod.Rocket.PermissionLink)        | OpenMod   | Unturned | Makes RM4 use OpenMod Permissions                                                                              | EUPL-1.2     | [GitHub](https://github.com/openmod/OpenMod/tree/master/unturned/rocketmod/Rocket.PermissionLink) |
| Player Info Library               | [Pustalorc.PlayerInfoLib.Unturned](https://www.nuget.org/packages/Pustalorc.PlayerInfoLib.Unturned/) | Pustalorc | Unturned | Player Info Library, store information about all your players.                                                 | EUPL-1.2     | [GitHub](https://github.com/Pustalorc/PlayerInfoLib/)                                             |
| Permission Extensions             | [DiFFoZ.PermissionExtensions](https://www.nuget.org/packages/DiFFoZ.PermissionExtensions/)           | DiFFoZ    | Unturned | Add support prefix, suffix, and color for OpenMod                                                              | GPL-3.0-only | [GitHub](https://github.com/DiFFoZ/PermissionExtensions)                                          |
| RealisticVehicleLock              | [SS.RealisticVehicleLock](https://www.nuget.org/packages/ss.realisticvehiclelock/)                   | Senior S  | Unturned | A plugin to add more realism to your roleplay server, the name say all!                                        | EUPL-1.2     | [GitHub](https://github.com/Senior-S/RealisticVehicleLock-OpenMod)                                |
| UconomyToOpenMod                  | [UconomyToOpenMod](https://www.nuget.org/packages/UconomyToOpenMod)                                  | Rube200   | Unturned | Support rocketmod plugins to use OpenMod Economy.                                                              | GPL-3.0-only | [GitHub](https://github.com/Rube200/UconomyToOpenMod)                                             |

# Contributing

Before adding your plugin to this list, ensure that the following conditions are met:
* Your plugin does not violate any copyright.
* The plugin is licensed under an [open source license](https://opensource.org/licenses).
* The plugin package is already published on nuget.org.
* The source code is available publicly (e.g. on GitHub).

After ensuring you meet these conditions, you can add your plugin:
- Go to https://www.tablesgenerator.com/.
- Click on File->Paste table data...
- Paste the table from above and click load.
- Add your plugin(s) in **alphabetical order**, based on the name. Plugins abusing the alphabetical ordering will be rejected.
- Add your license as SPDX identifier. See [here](https://spdx.org/licenses/) for SPDX identifiers.
- Keep your descriptions as short as possible.
- Create a pull request.
