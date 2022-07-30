---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.0
DaMichel's Spherical Tanks (DST)
created: 01 Oct 2019
updated: 21 Jul 2022 -->

<!-- based upon work by Lisias -->

# DaMichel's Spherical Tanks (DST)

[Home](./index.md)

Have you ever needed a set of spherical tanks of various capacities, to use for a refueling depot? an interplanetary mothership? A resource extraction base? Have you ever wanted a different tank options? DaMichel's Spherical Tanks might just be for you. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `DaMichel` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/SphericalTanks`
* Extract the package's `DaMichel` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/DaMichel` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/SphericalTanks`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/SphericalTanks`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/SphericalTanks`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [DaMichel]
      + [SphericalTanks]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-SA-4.0.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
        * SphericalTanks.version
    ...
  * KSP.log
  ...
```

### Dependencies

* [DaMichel Ltd (DM/L)][DML]

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DM/L)"
