﻿Rain of Stages is a framework to assist in the creation, testing, packaging and deployment of custom Risk of Rain 2 stages and mods.

As a player you can install Rain of Stages and then additionally install any custom Stage mods to add custom stages to your stage list.
Custom Stages can include unique game mechanics and entirely new modes of play!

As a developer, Rain of Stages will allow you to develop custom stages, setup custom sets of monsters, monster family events, and interactables.
Additionally, you can write custom code which will allow you to introduce new mechanics to the game via the BepInEx Unity game patcher and plugin framework.

If you would like to get started making Stages visit the [Github Pages for Rain of Stages](https://passivepicasso.github.io/Rain-of-Stages/)

Rain of Stages remains under development and contributions to the project are welcome

The project aims to provide many features to streamline the addition of many types of custom content for Risk of Rain 2.


Change Notes:
* 3.0.1
  * Move New Stage to Main Menu under Tools/Rain of Stages/New Stage

* 3.0.0
  * Built new node graph baking system, now capable of baking average RoR2 size maps in less than a second, and larger maps well under a minute.
  * Updated to ThunderKit 3.0.0
  * Greatly reduced the amount of code by removing proxy layer, now the majority of scripts can be used directly from the RoR2 assemblies
  * Added presets for ResourceMaterialMapper to allow easy use of hopoo terrain shaders/textures
  * Improved bundle loading mechanism to allow loading multiple stages

* 2.2.0:
  * Fix versioning

* 2.1.4:
  * Fix bug with destination injection and scene variants which replaced destinations and variants instead of adding to them

* 2.1.3:
  * Fix Version numbers

* 2.1.2:
  * Improved JumpPad Editor
  * Improved JumpPad Prefab