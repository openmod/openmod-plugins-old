# OpenMod Plugins

## Installing and Managing OpenMod Plugins
- To install a plugin, run the command `openmod install <NuGet Package ID>`.  
- To update plugins, run `openmod update <NuGet Package ID>`. 
- To uninstall a plugin, run `openmod uninstall <NuGet Package ID>`.

For more information, use the `help` command: e.g. use `help openmod install`.

## OpenMod Plugins List
| Name                              | NuGet Package ID                | Author  | Platform | Description                       | License    | Source Code                                                                                                                                                                                |
|-----------------------------------|---------------------------------|---------|----------|-----------------------------------|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OpenMod RocketMod Bridge          | [OpenMod.Rocket.Unturned](https://www.nuget.org/packages/OpenMod.Rocket.Unturned)       | OpenMod | unturned | Legacy RM4 support for OpenMod    | MIT        | [GitHub](https://github.com/openmod/OpenMod/tree/master/unturned/rocketmod)                                               |
| OpenMod RocketMod Permission Link | [OpenMod.Rocket.PermissionLink](https://www.nuget.org/packages/OpenMod.Rocket.PermissionLink) | OpenMod | unturned | Makes RM4 use OpenMod Permissions | EUPL\-1\.2 | [GitHub](https://github.com/openmod/OpenMod/tree/master/unturned/rocketmod/Rocket.PermissionLink) |

# Contributing

Before adding your plugin to this list, ensure the following conditions are met:
* You do not violate any copyright.
* The plugin must be licensed under an [open source license](https://opensource.org/licenses).
* The plugin package must be published to nuget.org.
* The source code must be available publicly.

After ensuring you meet these conditions, you can add your plugin:
- Go to https://tableconvert.com/.
- Click on "Import".
- Select Markdown, copy and paste the "OpenMod Plugins List" table from this file and click on "Import Data".
- Add your plugin(s) in **alphabetical order**.
- Add your license as SPDX identifier. See [here](https://spdx.org/licenses/) for SPDX identifiers.
- Create a pull request.
