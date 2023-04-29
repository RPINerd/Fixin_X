[center][heading]Fixin' X[/heading][/center]

[center]A compilation, merging, and tweaking of mods that make the game feel more polished and less tedious![/center]


[heading]Acknowledgements[/heading]
[line]

A big [u]thank[/u] you to all the modders who made the individual tweaks I've pulled together. And thank you to g_BonE and his mod pack g_Pack, it was a great starting off point for learning how all these files work together and modify the base game. If you enjoy this pack please follow the links to the individual mods below and give them an endorsement, their work is what made this possible. Also if you have any suggestions for values to tweak post it in the comments and we'll discuss!


[heading]What Is This Mod?[/heading]
[line]

[list]
[*] Brought together a ton of small single value tweaks
[*] Merged together files where possible/necessary
[*] Cleaned up indentations in places.. because that sort of thing bugs me :)
[*] Added documentation and explanations where I thought they could be useful
[*] Noted areas in XML files where users can add or remove specified features
[*] Added credits to the original authors, both in the files themselves and below
[*] Changed all file and folder names to lowercase as well as references within files to scripts and such; fellow Linux gamers, you're welcome!
[*] Tweaked values as felt appropriate during play. Specifics outlined in the mod credits below.
[/list]


[heading]Installation[/heading]
[line]

[b]Linux[/b] Download the archive file and extract it to ~/.local/share/Steam/steamapps/common/X4\ Foundations/extensions

[b]GoG[/b] Extract to ~/.config/EgoSoft/X4/extensions/
[i]Thanks to [url=https://www.nexusmods.com/x4foundations/users/2839077]Malefacius[/url] who pointed this out![/i]

[b]Windows[/b] It should be fine in the root directory where X4 is installed but I have no way to test this, so let me know if it doesn't work!


[heading]Mod Features[/heading]
[line]

[i]Keep in mind, basically all of these can be tweaked as you see fit![/i]

[u]Miscellaneous[/u]
[list=1]
[*] Both satellite types have their range bumped up slightly
[*] Mod equipping is no longer a slot machine, when you buy a part mod you know that you are going to get the max benefit.
[*] Black market dealers will buy the hacking tools without complaining your relation is not high enough
[*] Crew constantly hopping from chair to chair will no longer give you an aneurism as the seats are now silent
[*] Sheild only hazard damage for The Void, Tharkas' Cascade and Sanctuary of Darkness
[/list]

[url=https://www.nexusmods.com/x4foundations/mods/8]Learning All The Things[/url] and [url=https://www.nexusmods.com/x4foundations/mods/5]Improved Repair Laser[/url]
Author: iforgotmysocks
Location(s):    md/learningallthethings.xml
                assets/fx/weaponfx/macros/bullet_spacesuit_repairlaser_01_mk1_macro.xml
[b]LATT[/b] I have the % chance to improve 1 point set to 35% each hour along with that experience not being locked to the current job, and it now includes a dividing factor that reduces the chances of leveling with each star the pilot currently has. I've found that this gives a good natural growth feeling for the crew if you play long sessions. Those which want more arcade like progression may want to set % chance to 50ish and set the dividing option to false
[b]Repair Laser[/b] The repair laser can reach 4x the distance (roughly 150m) and repairs 4x as fast (20 points per second). I know that this is borderline cheese but I don't find taping my mouse button down or fighting the spacesuit thrusters to be engaging gameplay.

[url=https://www.nexusmods.com/x4foundations/mods/96]More NPCs[/url]
Author: Shamon
Location(s):    md/npc_instantiation.xml
By default this is set at 100, I dropped mine down to 50 because while it feels great out on the docking platforms it becomes quite silly in the smaller rooms and offices. I remember walking into a bar to deliver illegal wares and having to crouch jump up the railing because there were too many NPCs loitering about the place XD. If you're running on minimum specs as is, consider either deleting this file entirely or setting it to a much lower value (I believe the game default is 20?). More NPCs being rendered means more strain on both your CPU and GPU!

[url=https://www.nexusmods.com/x4foundations/mods/290]G_Pack[/url]
Author: g_BonE
Location(s):    libraries/wares.xml
                libraries/equipmentmods.xml
                libraries/factions.xml
                libraries/infounlocklist.xml
                libraries/stock.xml

[b]Vendors Sell Mod Parts[/b] Station vendors sometimes sell equipment mod parts and supplies; the higher tier equipment is much less common to find and the vendors will have much fewer in stock - if any. Also be prepared to pay for the privledge, in vanilla some of these items are entire mission rewards! Compared to the base mod I have heavily reduced the number of equipment mod parts vendors sell, and the likelihood that they have them. Higher tier equipment is much less common to be for sale and the quantity that vendors have is appropriately lower.
[b]Skip Station Scans[/b] My flavor is more like alleviate station scanning tedium. MThe vast majority of information only needs about 20% while detailed military and economic information needs anywhere from 60-80% depending on the sensitivity of the data.
[b]Disabled[/b] Legal inventory and Vendors sell SETA are out, the code is still there if you want to activate it, but I like my smuggling to actually be smuggling and SETA is a nice earned milestone.

[url=https://www.nexusmods.com/x4foundations/mods/55]Better Tractor Beam[/url] and
[url=https://www.nexusmods.com/x4foundations/mods/99]Shorter Travel Drive for Big Ships[/url]
Author: Spacecop42
Location(s):    libraries/parameters.xml
                /assets/props/engines/macros/*
[b]Tractor Beam[/b] The tractor beam can now reach 5.5 km, however you still should come to a stop before trying to vacuum up an entire battlefield otherwise you will just have containers orbiting you forever.
[b]Travel Drives[/b] Added in DLC engines and Linux compatibility, all L and XL All-Round drives have their charge times reduced to 7 and 10 seconds respectively while Travel varients are 10 and 12 for L/XL.

[url=https://www.nexusmods.com/x4foundations/mods/139]Build Time Reduction[/url]
Author: mjr121
Location(s):  libraries/wares.xml
The original mod cuts all construction except for Xenon by 10 fold. This means connectors build in like 10 seconds. I appreciate the wait for a complicated module to build, but the vanilla game just chugs when you want to start throwing down super factories. After many hundreds of hours of playing with this, I've currently gotten the times cut down to 60% of their time. All the DLC modules have been added as well!

[line]

[i]If any of the mod owners do not want their scripts included please let me know and I will remove them immediately! I'm not doing this to step on anyones toes, I just really love this game series and want to start being more active in the community that makes it better![/i]