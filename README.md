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

-REQUIRES <a href="https://www.spigotmc.org/resources/nbt-api.7939/">NBT API </a>(Required for guns to work)

-REQUIRES <a href="https://www.spigotmc.org/resources/skquery-1-13-1-19.36631/">SkQuery </a>(Required for certain features)



## Installation

-Install <a href="https://github.com/SkriptLang/Skript/releases" target="_blank">Skript</a>

-Install <a href="https://www.spigotmc.org/resources/skript-reflect.82259/">SkReflect</a>

-Install <a href="https://www.spigotmc.org/resources/nbt-api.7939/">NBT API</a>

-Install <a href="https://www.spigotmc.org/resources/skquery-1-13-1-19.36631/">SkQuery</a>

-Download this plugin file

-Locate "plugins/" in the server files and put the files from the plugin zip file into that folder

-Install Resource Pack from the plugin file (Optional but recommended)

-run the command "/sk reload all" or restart the server


## Commands
    /skgunsgive <player> <gun id> <damage> <reload speed> <fire rate> <ammo> <spread> <effect>
gives a gun with custom stats

<hr/>

    /skgunsgivedefault <player> <gun id> <effect>
gives a gun with default stats

<hr/>

    /skgunsgiveammo <player> <ammo type> <amount>
gives ammo

<hr/>

    /skgunsgivearguments
sends a list of the arguments required for /skgunsgive

<hr/>

    /skgunsgivedefaultarguments
sends a list of the arguments required for /skgunsgivedefault

<hr/>

    /skgunsgiveammoarguments
sends a list of the arguments required for /skgunsgiveammo

<hr/>

    /skgunsgivelistgunids
sends a list of all valid gun ids and their names

<hr/>
    /skgunsgivelisteffects
sends a list of all valid gun effects

## Arguments For Commands

### Gun ID
    1 = Peace Keeper
    2 = Beretta
    3 = Hornet
    11 = AK-1000
    12 = MX-101
    13 = Ranger
    14 = AK-47
    15 = M16
    16 = Musket
    21 = Ole Tongo
    22 = Double Barrel
    23 = Brass Punk
    31 = Railgun
    32 = Scout Rifle
    33 = Rapid Fire Precision
    41 = UNP
    42 = Torrent
    43 = Pocket SMG
    51 = Rocket Launcher
    52 = Grenade Launcher
    61 = Minigun

### Damage
amount of damage a single shot does in half hearts or the power of the explosion if it is an explosive weapon

### Reload Speed
amount of time in seconds it takes to reload

### Fire Rate
amount of time in seconds between shots

### Ammo
maximum ammo in a gun

### Spread
the amount the bullet might deviate from the crosshair

### Effect
easond/SKGuns/blob/mai

### Ammo Type
    Pistol
    Rifle
    Shotgun
    Sniper
    SMG
    Explosive
    LMG

## Controls
<strong>Right Click</strong> (Place / Interact) to fire gun

<strong>Left Click</strong> (Attack / Destroy) to scope with snipers

<strong>F</strong> (Swap Item Hand) to reload

## List Of Guns

### Pistols
- Peace Keeper
- Beretta
- Hornet

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Pistols.png?raw=true" alt="Pistols.png">

<strong>Rifles:</strong>
- AK-1000
- MX-101
- Ranger
- AK-47
- M16

Musket

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Rifles.png?raw=true" alt="Rifles.png">

Shotguns:</strong>
- Ole Tongo
- Double Barrel
- Brass Punk

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Shotguns.png?raw=true" alt="Shotguns.png">


<strong>Snipers:</strong>
- Railgun
- Scout Rifle
- Rapid Fire Precision

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Snipers.png?raw=true" alt="Snipers.png">


<strong>SMGs:</strong>
- UNP
- Torrent
- Pocket SMG

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/SMGs.png?raw=true" alt="SMGs.png">

<strong>Launchers:</strong>
- Rocket Launcher
- Grenade Launcher

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/Launchers.png?raw=true" alt="Launchers.png">

<strong>Machine Guns:</strong>
- Minigun

<img src="https://github.com/JasminDreasond/SKGuns/blob/main/img/machinegun1.png?raw=true" alt="machinegun1.png">

<hr/>

## Future Plans
- Adding Modern &amp; Past Weapons
- Tutorial on making custom weapons
- Grenades?
- Artillery?

## Change Log

<strong>Ver 1.1.3:</strong>
- Armor now mitigates damage received from damage dealt by guns
- bug fixes

<strong>Ver 1.1.2:</strong>
- added new kind of weapon &amp; ammo: Machine Guns
- added Minigun
- bug fixes

<strong>Ver 1.1.1:</strong>
- added AK-47
- added M16
- added Musket
- fixed an issue with the plugin destroying the offhand item
- updated reloading sounds

<strong>Ver 1.1.0:</strong>
- Fixed a Texture in the Resource pack
- Added a new kind of weapon: Launchers
- Added a new kind of ammo: Explosive ammo
- Added Rocket Launcher
- Added Grenade Launcher
- Fixed a bug with scoping

<strong>Ver 1.0.2:</strong>
- Changed some features with scoping

<strong>Ver 1.0.1:</strong>
- Fixed a bug with Electric guns creating invincible entities

<strong>Ver 1.0:</strong>
- Release
- Futuristic weapons
