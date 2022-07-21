# Changelog  

<!-- Changelog.cfg v1.1.3.0
Komplexity (KPLX)
created: 19 Apr 18
updated: 217 Jan 2022
-->

| modName    | Komplexity (KPLX)                                                 |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | zer0Kerbal                                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/202749-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Komplexity)             |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Komplexity)           |
| spacedock  | (https://spacedock.info/mod/2805)                                 |
| ckan       | Komplexity                                                        |

## Version 1.0.1.0-release `<Sideways Frontways>` edition

* 18 Apr 2022
* Released for Kerbal Space Program [KSP 1.12.x]

### Updated

* [Runway.cfg] v1.0.8.0
  * swap the length, width for the height restrictions for the runway
    * this because unlike the launchpad, planes are short, squat and very height challenged.
    * hardest part is to figure out which variable goes to which.
    * thank you to [MystLeissa](https://github.com/MystLeissa) for this suggestion
  * complete refactoring of length (x), height (y), and length (z) maximum allowable sizes
    * add label: // wingspan (width), height, length
    * consult [Runway](https://zer0kerbal.github.io/Komplexity/Buildings/Runway) for details
  * closes #39 - [Request/Balancing]: Change the Level 1 SPH Length Restriction to 9.0m, and the Height to 6.0m
* [Launchpad.cfg] v1.0.7.0
  * complete refactoring of length (x), height (y), and length (z) maximum allowable sizes
    * consult [Runway](https://zer0kerbal.github.io/Komplexity/Buildings/Runway) for details
  * closes #39 - [Request/Balancing]: Change the Level 1 SPH Length Restriction to 9.0m, and the Height to 6.0m
    * add label: // width, height, length
    * consult [Launchpad](https://zer0kerbal.github.io/Komplexity/Buildings/Launchpad) for details
  * closes #44 - Label and Swap the launchpad array
* [Komplexity.version]
  * since Komplexity will run on any version of Kerbal Space program
  * remove
    * KSP_VERSION_MIN

### Add  

* Flags!
  * contributed by zer0Kerbal
  * closes #37 - Add Flag

#### docs/

* updated (in progress)
* add [Notices.md]
* docs/Buildings/
  * Updates
    * Full
      * [Administration.cfg] v1.1.0.0
    * Minor
      * [AstronautComplex.cfg] v1.0.6.1
      * [MissionControl.cfg] v1.0.5.1
      * [ResearchandDevelopment.cfg] v1.0.6.1
      * [SpaceplaneHanger.cfg] v1.0.6.1
      * [TrackingStation.cfg] v1.0.6.1
      * [VehicleAssemblyBuilding.cfg] v1.0.6.1

### Status

* Issues
  * closes #43 - 1.0.1.0 Social Media
  * closes #42 - 1.0.1.0 Update Documentation
  * closes #41 - 1.0.1.0 Verify Legal Mumbo Jumbo
  * closes #40 - Komplexity 1.0.1.0-release `<Sideways Frontways>

---

## Version - 1.0.0.0-release - `<Ribbon Kutting>`

* Release
* 07 Apr 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Updated

* [Mission.cfg] is now on by default (smarter patching)
* spelling and grammar linting

### Add  

* better graphics

### wiki  

* moved to pages

### docs/

* updated (in progress)

### Status

* Issues
  * closes #29 - Update Wiki
  * closes #30 - JNSQ
  * closes #31 - Komplexity 1.0.0.0-release `<Ribbon Kutting>`
  * closes #32 - 1.0.0.0 Verify Legal Mumbo Jumbo
  * closes #33 - 1.0.0.0 Update Documentation
  * closes #34 - 1.0.0.0 Update Social Media

---

## Version 0.9.9.9.1-prerelease - `<EDITION>`

* Pre-Release

---

## Version 0.9.9.9-prerelease - `<Strategic Floating`>

* 15 Jan 2022  
* Release for Kerbal Space Program [KSP 1.12.x]  

### Caveat Emptor: Bureaucracy

* not really suggested, but not incompatible.

## Changes

* Should now be compatible with Strategia

### Update  

* [Mission.cfg.0] renamed to [Mission.cfg] (now on by default)  
* [TrackingStation.cfg.0] renamed to [TrackingStation.cfg] (now on by default)  
* [Administration.cfg.0] renamed to [Administration.cfg] (now on by default)  
* spelling and grammar linting
* fixed charge in Administration for level 1 cost (38000 from 37500)
* Update [ResearchandDevelopment.cfg] to fix the floating point comparison error

### wiki  

* completed  - still needs polish/fact pass

### Status

* Issues
  * closes #10 - include a note informing users
  * closes #12 - 0.9.3.0 beta
  * closes #13 - Help Wanted - Test enhancement
  * closes #14 - Localization - no translations needed
  * closes #16 - 20.1 / 45.1 bug
  * closes #18 - Update ResearchandDevelopment.cfg
  * closes #19 - Smarter Patches
  * closes #20 - Version 0.9.9.9-prerelease documentation
  * closes #21 - 0.9.9.9 Legal MumboJumbo documentation
  * closes #22 - 0.9.9.9 Update documentation documentation
  * closes #23 - Release 0.9.9.9-prerelease documentation
  * closes #24 - 0.9.9.9 - Social Media documentation
  * closes #25 - Strategia compatibility
  * closes #26 - Strategia compatibility - Pull request
  * closes #27 - Version 0.9.9.9-prerelease - Strategic Floating

---

## Version - 0.9.3.0-prerelease - `<The Final Countdown>`

### Strategia, Bureaucracy

* not really suggested, but not incompatible.
* if installed, do not Komplex the Administration Building

### Update

* level one building costs
* lint the price charts

### Add

* better graphics
* better wiki

---

## Version - 0.9.2.0-prerelease `<Breaking up is easy>`

* 28 May 2021
* for KSP 1.12.2

* Pre-Release 30 May 2021
* Split patches into seperate files
* turn TrackingStation.cfg.O off by default
* include directions on how to enable TrackingStation.cfg.0
* slight edits to documentation
* forum post created

### Status 

* Issues
  * closes #8 - # Version 0.9.2.0 - Breaking up is easy

---

## Version - 0.9.1.0-beta - `<Komplex Complex>`

* Beta Release 15 May 2021

* 28 May 2021
* Released for KSP 1.12.3

### accounting computer error(s)

* in Astronaut upgrade costs, corrected.
* in Launchpad upgrade costs, corrected.
* in Runway upgrade costs, corrected.
* ***Sorry, no refunds!***
* key values for Launchpad/Runway L x RELEASEDIR x W - corrected

### Tracking Station

* now 10 full levels instead of the default 3
* Part's in VAB/SPH will not reflect 10 levels in their part info - three levels are hard coding into the game
* Even though Antenna Helper (Mod) had 3 levels hard coded - it is some use
* Other mods might not be equipped to comprehend and deal with change
* ~~Patch Manager will have this building set to default by default<~~
* ~~now with Patch Manager support (limited)!~~
* worked on the Wiki and the graphic charts to help explain new levels

---

## Version 0.9.0.0-beta - `<Granular Komplexity>` - for KSP 1.12.3 [11-May-2021]

* Beta Release
* 11 May 2021
* for KSP 1.12.2

### Changes

* zer0Kerbal played with one of his mods
* closes #3 - Create LICENSE- contributed by zer0Kerbal

### Changelog, .version, Readme.md

* created Changelog.cfg [KERBALCHANGELOG] (.this)
* Add license field
* Add author node
* Add version naming field
* added additional fields in .version (might need to tweak urls)
* added shields to Readme.md

### Online

* createdGitHub Repo
* created Forum Thread
* created SpaceDock
* created CKAN/NetKAN
* created Curseforge

### Status

* Issues
  * closes #3 - Create LICENSE

---

## Version 0.8.0.0-alpha - `<Brushing off the Construction Dust>`

### organize for introduction

* folder structure
* added license(s) file(s)
* added .version file
* Readme
* automated backend
* jsons
* Changelog.md -> Kerbal Changelog Changelog.cfg
* updated Readme.md
* moved changelog into separate file

<!-- CC BY-SA 4.0 by zer0Kerbal -->
