# Mod Content Creator

A Unity Package to help you build asset bundles for mods for The Colonists (https://store.steampowered.com/app/677340/The_Colonists/)

## Requirements

* Unity 2020.3 (https://unity.com/releases/editor/whats-new/2020.3.37)

## Usage

1. Create a new project in Unity
1. Open the Package Manager (Window -> Package Manager)
1. Add a package from git URL with `https://github.com/codebyfire/colonists-mod-asset-bundle-builder.git` (Plus icon in the top left)
1. Create a prefab for your in-game asset, naming it following the mod naming conventions (e.g. building_200). (Full docs on The Colonists wiki: http://codebyfire.com/colonists/wiki/index.php/Mods) How to create a prefab in Unity: https://docs.unity3d.com/Manual/CreatingPrefabs.html
1. Assign the prefab to an asset bundle name (bottom of Inspector panel when prefab is selected - any name is fine, the game will read in all assetbundles)
1. Open the Asset Bundle Builder panel (Tools -> Asset Bundle Builder)
1. Enter the full path of your mod in the output directory
1. Click Build to build all asset bundles in the project and copy them to the specify mod folder
1. Run your mod!
