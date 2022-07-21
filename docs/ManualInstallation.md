---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.0
Komplexity (KPLX)
created: 01 Oct 2019
updated: 21 Jul 2022 -->

<!-- based upon work by Lisias -->

# Komplexity (KPLX)

[Home](./index.md)

A Custom Barn Kit config addon that increases Kerbal Space Center buildings to ten levels instead of the stock game's four. For Kerbal Space Program. Doesn't add more building models.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KGEx` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/Komplexity`
* Extract the package's `KGEx/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KGEx/` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KGEx/Komplexity`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KGEx/Komplexity`
* Extract the package's `GameData/` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KGEx/Komplexity`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + <GameData>
    + <KGEx>
      + <Komplexity>
        + <Configs>
          * Administration.cfg
          * AstronautComplex.cfg
          * Launchpad.cfg
          * MissionControl.cfg
          * ResearchandDevelopment.cfg
          * Runway.cfg
          * SpaceplaneHanger.cfg
          * TrackingStation.cfg
          * VehicleAssemblyBuilding.cfg
        + <Compatibility>
          * RealSolarSystem.cfg
          * OuterPlanetsMod.cfg
        #.#.#.#.htm
        Attributions.htm
        CC-BY-SA-4.0.txt
        changelog.md
        Komplexity.version
        ManualInstallation.htm
        readme.htm
      ...
    ...
    * ModuleManager.dll
  KSP.log
  ...
```

### Dependencies

* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]
* One of the following:
  * [Custom Barn Kit][cbk]  
  * [Custom Barn Kit - RO build][cbkro]

[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
[cbk]: https://forum.kerbalspaceprogram.com/index.php?/topic/109027-*/ "Custom Barn Kit"
[cbkro]: https://forum.kerbalspaceprogram.com/index.php?/topic/109027-*/ "Custom Barn Kit - RO build"
