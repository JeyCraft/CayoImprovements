# CayoImprovements 🏝️

Designed for RP and exploration in mind, CayoImprovements enhances the island by removing obstructing collisions, adds more vegetation, street lights, heist props and socializing opportunities.

**This resource is for FiveM usage with the understanding that you will not modify, sell or reupload elsewhere without my permission.**

It is to work alongside [[pmms](https://github.com/kibook/pmms)] for playing content on the TV screens, as well as [[fivem-scenarios](https://github.com/kibook/fivem-scenarios)] for interacting with scenarios around the world, including Cayo Perico.

This is a passion project of mine that began in December of 2020 to self teach myself Codewalker and has been constantly updated and developed since.

Screenshots are provided in their respective folder.


I hope you enjoy 😊

---------------------------------------

# **REQUIREMENTS** ⚙️

- **Latest recommended artifacts** [for Windows](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) **or** [for Linux](https://runtime.fivem.net/artifacts/fivem/build_proot_linux/master/)

-  [Gamebuild 2189 or higher](https://forum.cfx.re/t/tutorial-forcing-gamebuild-to-casino-cayo-perico-or-tuners-update/4784977)

- [Poodle Multimedia Script](https://github.com/kibook/pmms) **for the TV at the Beach Party.** 

> By default, PMMS is set to admin only 
> access, you can change this in the 
> permissions.cfg provided with it, if you 
> would prefer all players can access it.
>
> you will need to read pmms installation 
> instructions on the GitHub repository, and if you
> can't figure it out, open an issue. 
>
> I'm **not** here to hold your hand.

---------------------------------------

**If you want the TV at the beach party to fade out nicely at a certain point, try these settings, then go to advanced settings and save it as an entity, call it Cayo Perico Beach TV:**

> Volume: 100
> 
> sameRoom: 2.4
> 
> diffRoom: 6.0
> 
> Range: 40

**In the future, any TV settings you want, save it as an entity. Saving it as model will save those settings for that TV, everywhere around the map.**

---------------------------------------

# CONTENTS 🏝️

- Working lighthouse

- **Heist props**  - Can be changed in the `entitysets.lua` file within the **scripts** folder

- Removed snow falling from North Yankton 🌨️

- Runway lights and a helipad

- Street lights around the main roads of the island

- Mansion Pool improvement and solid sun loungers, beach ball, floatie, tables and chairs

- Mansion entrance gate doors removed for access

- Side doors of mansion compound opened and lift doors removed for your teleporter script convenience

- Animal cage doors opened - I will **not** be providing doorlock support **#cringe**

- Illuminated Boat Shed near party area and beached whale

- Illuminated skull near grave, opposite party area

- Illuminated beach party area with buoys, DJ stand lights, bar lights and TVs

- Deleted and opened underwater gate below El Rubio's mansion

- Deleted all sea mines -- Want them back? Delete **h4_islandx_sea_mines** from the `ymap` folder.

- Removed invisible collisions

- Removed invisible collision at Beach DJ Booth

- Junk cleanup

- Opened hangar doors

- Sunken UFO & Loch Ness Monster

- Crashed plane

- Runway clearance lights

- Food stall, shop and Ice Cream parlor

- Vehicles

- NPC Peds -- can be removed or commented out in `peds_config.lua`

---------------------------------------

# BUGS 🐛

Due to the hangar being **modified** and additional props placed inside, having both islands active *(via removing the native)*, causes an issue with the hangar appearing.

 ⚠️ **TELEPORTING TO AND FROM THE ISLAND **MAY** CAUSE ISSUES. USE A BRIDGE, PLANE, HELICOPTER OR BOAT** ⚠️


---------------------------------------

# **VEHICLES, GATES AND HANGAR COLLISIONS** 🚘

`Original Hangar Collision`, `No Flight Or Water Vehicles`, and `NoVehicles` folders have now been combined and put inside the `OPTIONAL` folder.

If for whatever reason you would like to add the original gates back, but have them be accessible and not solid shut, *as well as the little button seen in the Cayo Perico Heist in Grand Theft Auto: Online,* I have provided the folder `OPTIONAL`. Place `tays_mansiongates` inside the `ymaps` folder.

# VEHICLES:

**"Vehicles - No Flight Or Water" and "Vehicles - Removed" options updated and provided within the `OPTIONAL` folder. Drag and drop the files you require into the CayoImprovements ymap folder.** Backups have been provided.

# **HANGAR COLLISIONS:**

The hangar collision file is also in the `OPTIONAL` folder.

If you happen to have the '"[Cayo Perico Shops MLO](https://forum.cfx.re/t/mlo-cayo-perico-shops/1994908)' resource, as well as mine, the server refuses to read the collision file for shops, but instead, read mine, making the shop collisions not work. 

Just copy and paste mine, or the Cayo Perico Shops collision file **(h4_islandairstrip_12)** into the ybn folder. 

---------------------------------------

# Frameworks & Other Cayo Perico Resources / Scripts Support:

I don't use any fancy frameworks or any other Cayo Perico related resources, so you'll have to troubleshoot it on your **own.** These are simply ymaps, therefore you may need to update the fxmanifest version to something newer, and then it should be good to go.

Check any collision (ybn) files of your maps if you face any conflictions.

---------------------------------------


# Installation: 

* Download repository and `CayoImprovements` to your server files

* Add `h4_islandairstrip_12` from the `Original Hangar Collison` folder, and insert it into `CayoImprovements` > `stream` > `ybn`. If you are using the Cayo Perico Shops resource, ignore this step


* Choose between `No Flight Or Water Vehicles` or `No Vehicles`, and insert the files into the `CayoImprovements` > `stream` > `ymap` folder, replacing the existing files. If you enjoy the vehicles spawning on the island, ignore this step. If at any time you need the vehicles back, grab the files from `Vehicles BACKUP` and place them into the `CayoImprovements` > `stream` > `ymap` folder.

* add `start CayImprovements` to your server.cfg

* Restart server or type `/start CayoImprovements` into the chat window 
