# nebulasmp

This is the repository for the mods required for the Nebula SMP.

### NOTICE: INSTALLING THE LATEST VERSION OF FABRIC MAY CAUSE UNINTENDED ISSUES

## Prerequisites

- [Fabric Installer 0.10.2](https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.10.2/fabric-installer-0.10.2.jar)
- [modpack_required **OR** modpack_recommended](https://github.com/esolang/nebulasmp/releases)
- a brain

## Installation

1. Open Fabric Installer and install the Client version. 
   - Minecraft Version `1.18`
   - Loader Version `0.12.11`
2. Navigate to your mods folder.
   - Windows
     - Press `Win + R` and type `%appdata%`.
     - Open `.minecraft`.
     - If there is no folder named `mods`, create one.
     - Open mods folder
3. Extract mods from the modpack into the folder.
   - Windows
     - Open the modpack with either WinRar or 7-Zip.
     - Extract files into the mods folder.
4. Run Minecraft `1.18` at least once. (If you already have done this, skip this step)
5. Run Minecraft with Fabric
   - Official launcher
     - Click on the installations tab.
     - Click on `New installation`.
     - Change version to `release fabric-loader-0.12.8-1.18`.
     - Click create.
     - Switch the release to the left of the play button to the newly created installation.
   - TLauncher
     - Click on the releases at the bottom.
     - Set the version to `Release fabric-loader-0.12.8-1.18`.

## FAQ

> How do I configure shaders in Iris shaders?

Refer to the [shaders](https://github.com/esolang/nebulasmp/tree/main/shaders) folder.

> I keep falling through the floor and nothing loads!

See if uninstalling Sodium helps.
