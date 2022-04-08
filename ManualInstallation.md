---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.2.0
Komplexity (KPLX)
created: 01 Oct 2019
updated: 05 Apr 2022 -->

<!-- based upon work by Lisias -->

# Komplexity (KPLX)

An Custom Barn Kit config addon that increased Kerbal Space Center building levels to a ten levels instead of the stock game's four. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the KGEx folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/Komplexity`
* Extract the package's `KGEx/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KGEx/Komplexity` --> `<KSP_ROOT>/GameData/KGEx/Komplexity`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/Komplexity`
* Extract the package's `GameData/` folder into your KSP's folder as follows:
  * `<PACKAGE>/GameData/KGEx/Komplexity` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  [GameData]
    [KGEx]
      [Komplexity]
        [Configs]
          * [Administration.cfg]
          * [AstronautComplex.cfg]
          * [Launchpad.cfg]
          * [MissionControl.cfg]
          * [ResearchandDevelopment.cfg]
          * [Runway.cfg]
          * [SpaceplaneHanger.cfg]
          * [TrackingStation.cfg]
          * [VehicleAssemblyBuilding.cfg]
        #.#.#.#.htm
        changelog.md
        License.txt
        readme.htm
        Komplexity.version
      ...
    ...
  KSP.log
  ...
```

### Dependencies

* [Module Manager /L][mm]
* One of the following:
  * [Custom Barn Kit][cbk]  
  * [Custom Barn Kit - RO build][cbkro]

[mm]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
[cbk]: https://forum.kerbalspaceprogram.com/index.php?/topic/109027-*/ "Custom Barn Kit"
[cbkro]: https://forum.kerbalspaceprogram.com/index.php?/topic/109027-*/ "Custom Barn Kit - RO build"
