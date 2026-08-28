# Action Half-Life: Way Of The Gun (`ahl_wayofthegun`)

An archival repository preserving the original source files, assets, and final playable build of **`ahl_wayofthegun`**, a classic map for the Half-Life mod **Action Half-Life (AHL)** created by **ThRaShErUk]c[**.

Based on the intense final shootout from the film [*The Way of the Gun* (2000)](https://www.imdb.com/title/tt0202677/), the map features a run-down Mexican hotel courtyard complete with tactical cover, destructible elements, custom soundscapes, and fast-paced stunt gameplay.

Note: Contact information has been updated

---

## 📸 Screenshots

![Screenshot 1](screenshots/1.png?raw=true)

![Screenshot 2](screenshots/2.png?raw=true)

![Screenshot 3](screenshots/3.png?raw=true)

![Screenshot 4](screenshots/4.png?raw=true)

![Screenshot 5](screenshots/5.png?raw=true)

![Screenshot 6](screenshots/6.png?raw=true)

![Screenshot 7](screenshots/7.png?raw=true)

![Screenshot 8](screenshots/8.png?raw=true)

![Screenshot 9](screenshots/9.png?raw=true)

![Screenshot 10](screenshots/10.png?raw=true)

![Overview](screenshots/overview.png?raw=true)


---

## 🚀 Installation & Playable Setup

To install and play `ahl_wayofthegun` on a client or dedicated server:

1. Download [`ahl_wayofthegun.zip`](https://github.com/NeilInnes/ahl_wayofthegun/raw/master/ahl_wayofthegun.zip)
2. Extract the contents (`wayofthegun.wad` plus `gfx/`, `maps/` and `sound/` folders) directly into your Action Half-Life directory (`half-life/action/` or `steamapps/common/Half-Life/action/`).
3. Launch Action Half-Life and load the map via the Start Server option or via the console:
   ```sv
   map ahl_wayofthegun
   ```
   
---

## 🪞Community & Mirrors

You can find this map, leave reviews, or discuss it on the following platforms:

[![](https://gamebanana.com/mods/embeddables/710760?type=large)](https://gamebanana.com/mods/710760)

[![](https://button.moddb.com/download/medium/315428.png)](https://www.moddb.com/mods/action-half-life/addons/way-of-the-gun-ahl-wayofthegun)

[![](https://img.shields.io/badge/TWHL-View_in_Vault-2a2a2a?style=for-the-badge)](https://twhl.info/vault/view/7246)

---

## 📁 Repository Structure

```text
ahl_wayofthegun/
├── README.md               <-- Repository overview
├── LICENCE                 <-- Licence file
├── ahl_wayofthegun.zip     <-- Pre-packaged, drop-in zip release
├── screenshots/            <-- Screenshots of map in AHL
│
└── source/                 <-- GoldSrc build & source assets
    ├── wayofthegun.rmf     <-- Primary Worldcraft / Valve Hammer Editor file
    ├── wayofthegun.map     <-- Plain-text geometry & entity map format
    ├── wayofthegun.log     <-- Sanitized ZHLT build log
    └── assets/             <-- Raw texture & sound sources
        ├── wayofthegun.wad
        ├── gfx/
        │   └── env/
        │       ├── desert2bk.tga
        │       ├── desert2dn.tga
        │       ├── desert2ft.tga
        │       ├── desert2lf.tga
        │       ├── desert2rt.tga
        │       └── desert2up.tga
        └── sound/
            ├── jinx/
            │   ├── borg_crickets.wav
            │   └── od_dam_wind.wav
            └── wayofthegun/
                └── intro.wav
```

---

## 🛠️ Mapping & Compilation Notes

* **Master Source File**: `source/wayofthegun.rmf` represents the final HL1 / GoldSrc build. 
* **Texture Dependencies**: Re-compiling the map requires `halflife.wad`, `bored.wad` (by X-Tender), and `wayofthegun.wad`.

---

## ⚖️ Licensing
The original map geometry, source files (`.rmf`, `.map`), and compiled BSP created by Neil Innes are licensed under the **MIT License**. 

Please note that third-party assets included in this archive (custom textures, skyboxes, and audio by Christopher Buecheler, Sock, X-Tender, ComaWhite, and Jinx) retain their original respective copyrights and may not fall under the MIT license.

---

## 📜 Original Release Documentation (2005)

```text
Action Half-Life Map Information

-------------------------------------------------------------------------------

Title       :  Way Of The Gun
File name   :  ahl_wayofthegun.zip
Game type   :  Deathmatch
Author      :  ThRaShErUk]c[
Contact     :  http://github.com/NeilInnes/ahl_wayofthegun
Released    :  February 2005
Players     :  3-6
Spawns      :  12

-------------------------------------------------------------------------------


Info
----
Based on the final shoot-out in the film "Way Of The Gun" set in a remote run-down hotel/brothel in Mexico. The original idea was to include a few rooms (including the 'birth' room from the film) but it was collectively decided that these should be left out (another plan was to add a cellar from behind the bar that would have other entrances outside).

R_speeds are pretty high maxing out at 1000+ (when looking at the front of the building). This is mainly due to the nature of the map layout. However, this is my first map so theres probably loads of tricks I could have used to reduce this, though this shouldn't be a problem on a relatively modern system. I feel if I started again, knowing what I know now, I could probably make a better job. I may revisit this map at some point and make everything nicer, with rooms, working etc.

P.S. - The drum sound at the start of the map is taken directly from the film.
P.S.S - A .WLF file is included to remove the NV Goggles and Flashlight (ph33r!) as they aren't really neccessary on this map and I know how much they annoy people.
P.S.S.S - The original idea for the 'glass fountain' was to have the trigger_hurt turn off on a nade, however for some reasons nades won't trigger the func_breakable, answers on a postcard please (or alternatively an email).

The custom models that are mentioned in the .ini file are available from http://www.clan-ici.co.uk/.

Update
------

Updated the map as follows:
	Added some clip brushes on the roof staircase entrance as people were getting stuck.
	Added the washing on the roof for extra cover.
	Removed a roof spawn near the east tower as it was becoming a frag haven.
	Made the wooden frames on the ground climbable.
	Added another wooden frame to add an extra route from the east and west wings.
	Added a wooden plank to get from the truck outside the wall.
	Fixed the broken crate so it now conforms to the laws of gravity.
	Fixed the coke machine so it is  pushable and causes a touch more damage when it breaks.
	Made the ammo boxes a touch easier to blow up and a bit more lethal.

Credits
-------
Clan ]c[ for constructive criticism and play testing.
Christopher Buecheler for his great stone textures (http://www.texturestudio.com/).
Sock for the fantastic desert skybox (http://www.planetquake.com/simland/).
X-Tender for bored.wad
ComaWhite for the vehicle prefabs.
Jinx for some amazing ambient sounds.
AHL Map Depot for the helpful tutorials (http://ahlmd.telefragged.com/).
The Action Halflife: Directors Cut team for breathing life back into AHL and getting me into mapping.
And anyone else I have left out.


Installing
----------
Unzip and drop everything into the half-life folder.


Distribution, Copyright and Legal Garbage
-----------------------------------------
The software may be distributed for non-commercial purposes only, the authors
reserve all rights. All custom media and textures are copyright their
respective owners.
```
