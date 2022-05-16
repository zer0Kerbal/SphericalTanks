---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

# Changelog  
  
| modName    | DaMichel's SphericalTanks (DST)                                   |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-3.0                                                      |
| author     | DaMichel, Bezzier and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208140-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SphericalTanks)         |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SphericalTanks)       |
| spacedock  | (https://spacedock.info/mod/2342)                                 |
| ckan       | DMTanks-SphericalTanks                                            |

## Version 2.1.99.0-prerelease - `<Split'n'Polish: SphericalTanks>`

* 09 May 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Add

* Dependency
  * DaMichel Ltd (agency, flag, common files)

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts
* closes #29 - Asset Updates

### Localization

* Update
  * <us-en.cfg>
* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
* updates #11 - English <us-en.cfg>
* updates #10 - Localization - Master

### Status

* Issues
  * closes #6 - SphericalTanks (DST) 1.1.99.0-prerelease `<Split'n'Polish: SphericalTanks>`
  * closes #7 - 1.1.99.0 Verify Legal Mumbo Jumbo
  * closes #8 - 1.1.99.0 Update Documentation
  * closes #9 - 1.1.99.0 Social Media

---

## Version 1.1.0.2 - for KSP 1.12.3 [22-Mar-2022]

* #4 - [ImgBot] Optimize images - contributed by imgbot[bot]
* #6 - [ImgBot] Optimize images

---

## Version 1.1.0.1-prerelease - `<Spit'n'Polish>`

* 2020-02-24
* Released for Kerbal Space Program 1.8.1

* removed
  * tags.cfg (redundant patch since tags now in localization)
* updated product hero shots
* created SpaceDock header

* Thank you
  * @Joal ban Kluane
    * for suggesting improvement in the forum post(s)
  * @shdwlrd
    * for pointing out issues in part.cfg's
    * (s.i.c.)
  * @Jiraiyah
    * for pointing at the Karbonite patches.
    * (s.i.c.)
  * BenjaminCronin
    * for pointed out decorative right brace in changelogs
    * wite-out applied.
* Also dangling VERSION.
  * superglued applied.

### Parts

* Changed
  * [maximum_drag] from 0.25 to 0.2 (stock)
  * [minimum_drag] from 0.25 to 0.3 (stock)
  * [maxTemp from 1800] from 1400 to 2000 (stock)
* Added
  * missing texture (c125-normalmap_NRM.dds)

### Localization

* Updated
  * from #DM_sphericaltanks_* to #DST_*
* Added into localization
  * new B9TankTypes
  * new patch

### Compatibility

* Updated
  * integrated TweakScale module (removed KGEx, added freeScale = True)
  * [B9TankTypes.cfg]
    * Add tank definitions
      * [Karbonite]
      * [Karborundum]
        * unitsPerVolume probably need adjustment
        * currently set to 5
        * seems there is a 5:1 ratio between LF and K
  * [B9PartSwitch.cfg]
    * Karbonite patch
  * [B9FuelSwitch-Snacks.cfg]
    * removed extraneous [SNACKS]
  * [B9FuelSwitch-TAC-LS.cfg]
    * removed extraneous [TAC]
* Added
  * tank patch
    * [Karborundum]
      * if B9PartSwitch and Karbonite+ (Karborundum) is installed
* [USI-Logistics]
  * to tanks
  * if USI-Logistics installed.
  * [B9FuelSwitch-Karborundum.cfg]
    * [Karborundum]
      * out of [B9FuelSwitch-Karbonite.cfg]
      * into its own patch

### Notes

* Volumes between USI, DST, and stock
  * something is out of whack
  * Not Sphericaltanks
  * Appears to be USI-Kontainers holding about 10% more than mathimatically possible

### Status

* Issues
  * closes #28 - Previous Releases
  * updates #29 - Asset Updates
  * closes #31 - 1.1.0.1-prerelease

---

## Version 1.1.0.0-adoption - `<Fresh Coat of Paint: SphericalTanks>`

* 2020-02-17
* Released for Kerbal Space Program 1.8.1

* adopted by zer0Kerbal
* for Kerbal Space Program (KSP) 1.9.1 (might work for earlier)

### Localization

* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
    * <en-us.cfg>
  * translations welcomed through GitHub Push Request
  * updates #10 - Localization - Master
  * closes #11 - English <us-en.cfg>
  * closes #27 - Part Localization

* updated license to CC BY-SA 4.0
* file structure and modernization
* modernized part.cfg
* many little changes to patches/parts.

### Created

* Kerbal Changelog
* Readme
* github repo
* SpaceDock entry
* CKAN entry
* Curseforge entry
* Forum post
* .json

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts
* updates #29 - Asset Updates

### Status

* Issues
  * updates #28 - Previous Releases
  * closes #30 - 1.1.0.0-adoption

---

## Version - 1.0.1.0-release - Cost Increase

* Nov 03, 2017
* Kerbal Space Progrtam 1.3.1

* This release increases the cost of the AeroRTG by 50%, to offset its aerodynamic nature as compared to the original RTG.
* The part continues to function, so this brings it up to date for 1.3.1.

---

## Version - 1.0.0.0-release - colorcurves update

* May 10, 2016
* Kerbal Space Progrtam 1.0.5
* adopted by Bezzier (Color Curves)

### This brings these parts up to date by

Correcting typos

* Correcting typos
* Rebalancing to stock values
  * costs
  * masses
  * temperatures
  * drag
* Adding Core Heat
* [techRequired] to experimentalElectrics

---

## Version - 0.0.0.0-release - Original by DaMichel

* unknown version number
* Apr 18-2014
* First release

---

<!-- This File CC BY-ND 4.0 by zer0Kerbal -->