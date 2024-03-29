# SKGuns

<dl class="customResourceFieldmc_versions">
<dt>Tested Minecraft Versions:</dt>
<dd>
    <ul class="plainList">
        <li>1.19.3</li>
    </ul>
</dd>
</dl>

### ADVANCED GUNS PLUGIN MADE WITH SKRIPT

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/SKGunsIcon.png?raw=true" alt="SKGunsIcon.png">

## Dependencies

-REQUIRES <a href="https://github.com/SkriptLang/Skript/releases" target="_blank">Skript </a>(Runs on Skript)

-REQUIRES <a href="https://www.spigotmc.org/resources/skript-reflect.82259/">SkReflect</a> (Required for guns to work)

-REQUIRES <a href="https://github.com/Sashie/skript-yaml">skript-yaml</a> (Required for guns data load to work)

-REQUIRES <a href="https://www.spigotmc.org/resources/nbt-api.7939/">NBT API </a>(Required for guns to work)

-REQUIRES <a href="https://www.spigotmc.org/resources/skquery-1-13-1-19.36631/">SkQuery </a>(Required for certain features)

## Permissions

    skguns.skgunsgive
Command access to /skgunsgive

    skguns.skgunsgiveammo
Command access to /skgunsgiveammo

    skguns.resetgun
Command access to /resetgun

    skguns.*
Access to all features

## Installation

-Install <a href="https://github.com/SkriptLang/Skript/releases" target="_blank">Skript</a>

-Install <a href="https://www.spigotmc.org/resources/skript-reflect.82259/">SkReflect</a>

-Install <a href="https://github.com/Sashie/skript-yaml">skript-yaml</a>

-Install <a href="https://www.spigotmc.org/resources/nbt-api.7939/">NBT API</a>

-Install <a href="https://www.spigotmc.org/resources/skquery-1-13-1-19.36631/">SkQuery</a>

-Download this plugin file

-Locate "plugins/" in the ser### Ver files and put the files from the plugin zip file into that folder

-Install Resource Pack from the plugin file (Optional but recommended)

## Commands
    /skgunsgive <player> <gun id>
Gives a gun

<hr/>

    /skgunsgiveammo <player> <ammo type> <amount>
Gives ammo

## Weapon Editor
    /Server/plugins/SKguns/weapons
Go to this repository page. You will find the ID list of all weapons here.

## Controls
Right Click (Place / Interact) to fire gun

Left Click (Attack / Destroy) to scope with snipers

F (Swap Item Hand) to reload

## List Of Guns

### Pistols
- Peace Keeper
- Beretta
- Hornet

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Pistols.png?raw=true" alt="Pistols.png">

### Rifles
- AK-1000
- MX-101
- Ranger
- AK-47
- M16
- Musket

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Rifles.png?raw=true" alt="Rifles.png">

### Shotguns
- Ole Tongo
- Double Barrel
- Brass Punk

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Shotguns.png?raw=true" alt="Shotguns.png">

### Snipers
- Railgun
- Scout Rifle
- Rapid Fire Precision
- AWP

<img src="https://github.com/Pangw1n/SKGuns/blob/main/img/Snipers.png">

### SMGs
- UNP
- Torrent
- Pocket SMG

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/SMGs.png?raw=true" alt="SMGs.png">

### Launchers
- Rocket Launcher
- Grenade Launcher

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Launchers.png?raw=true" alt="Launchers.png">

### Machine Guns
- Minigun

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/machinegun1.png?raw=true" alt="machinegun1.png">

<hr/>

## Future Plans
- Adding Modern &amp; Past Weapons
- Grenades?
- Artillery?

## Change Log

### Ver 1.2.0 (Made by JasminDreasond)
- Tutorial on making custom weapons
- The rocket launcher now has new effects and new sound
- The script has been reorganized. Now new dependencies have been added
- SkBee dependence removed
- The command list has been updated
- It is now possible to create new weapons through yaml files (/Server/plugins/SKguns/weapons)
- Each weapon now has its own sound effect
- You can use the function createSkGunItem() to generate the item in your script to do things like create a recipe for the weapon
- Commands now have a permissions system

### Ver 1.1.3
- Armor now mitigates damage received from damage dealt by guns
- bug fixes

### Ver 1.1.2
- added new kind of weapon &amp; ammo: Machine Guns
- added Minigun
- bug fixes

### Ver 1.1.1
- added AK-47
- added M16
- added Musket
- fixed an issue with the plugin destroying the offhand item
- updated reloading sounds

### Ver 1.1.0
- Fixed a Texture in the Resource pack
- Added a new kind of weapon: Launchers
- Added a new kind of ammo: Explosive ammo
- Added Rocket Launcher
- Added Grenade Launcher
- Fixed a bug with scoping

### Ver 1.0.2
- Changed some features with scoping

### Ver 1.0.1
- Fixed a bug with Electric guns creating invincible entities

### Ver 1.0
- Release
- Futuristic weapons
