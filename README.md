# Fixin' X

_A compilation, merging, and tweaking of small individual changes that make the game feel more polished and less tedious!_

---

## Acknowledgements First

A big __thank you__ to all the modders who made the individual tweaks I've pulled together, especially g_BonE and his mod pack g_Pack, it was a great starting off point for learning how all these files work together and modify the base game.  
If you enjoy this pack please follow the links to the individual mods below and give them an endorsement, their work is what made this possible. Also if you have any suggestions for values to tweak post it in the comments and we'll discuss!

---

## Installation

__Linux:__ Download the archive file and extract it to ~/.local/share/Steam/steamapps/common/X4\ Foundations/extensions  

__Windows:__ It should be fine in the extensions folder but I have no way to test this, so let me know if it doesn't work!

---

## General Gameplay Changes

- Lower station scan percentage needed for info
- Fix for illegal goods not being sellable
- Buildtime for all station modules reduced to 80% of their original speed
- Range and strength of repair laser increaced
- Visibility range of satellites bumped up mildly
- Learning All The Things (Custom Configuration)
- No more random equipment mods
- Traders occassionally carry equipment mod parts
- Stronger and longer range tractor beam
- No more obnoxious chair swapping noise
- Reduction of travel engine charge time for L and XL ships
- More NPC's populate docks and bars
- Probably more I'm forgetting

---

## Backend Changes

- Changed all file and folder names to lowercase as well as references within files to scripts and such; fellow Linux gamers, you're welcome!
- Cleaned up indentations in places.. because that sort of thing bugs me :)
- Added documentation and explanations where I thought they could be useful
- Noted areas in XML files where users can add or remove specified features
- Credits to the original authors are included both in the files themselves and below

---

## Re-Enable

_There are a handful of things that I have outright disabled out of preference. These have full documentation in their respective files for how to re-activate them and also what they do. This includes:_

1. Dynamic Scaleplate relations
2. SETA parts sold by traders
3. Legal Inventory

---

## Specific Mods Adapted Into This Merge:

[G_Pack](https://www.nexusmods.com/x4foundations/mods/290) by ___g_BonE___

- Insert "Yo dawg.." joke here. Mod packs in mod packs people!! But jokes aside, there are some very important distinctions.
    1. I have heavily reduced the number of equipment mod parts vendors sell, and the likelihood that they have them. Higher tier equipment is much less common to be for sale and the quantity that vendors have is appropriately lower.
    2. SETA parts are no longer sold at traders; the code is still in there if you want this function, but I don't like it so there!
    3. Skip Station Scans is more like alleviate station scanning tedium. Most info is unlocked almost instantly after fly-by of your first module - i.e. in the 0-15% scanned range. However, if you want detailed military and economic info you should have to get that percentage up in the 40-60 range.
    4. Legal inventory is out, the code is still there if you want to activate it, but I like my smuggling to actually be smuggling.

[Learning All The Things](https://www.nexusmods.com/x4foundations/mods/8) and [Improved Repair Laser](https://www.nexusmods.com/x4foundations/mods/5) by ___iforgotmysocks___

- I have the % chance to improve 1 point set to 35% each hour along with that experience not being locked to the current job, and it now includes a dividing factor that reduces the chances of leveling with each star the pilot currently has. I've found that this gives a good natural growth feeling for the crew if you play long sessions. Those which want more arcade like progression may want to set % chance to 50ish and set the dividing option to false
- My preference has an additional doubling of both the reach and the repair rate. I know that this is borderline cheese but I don't find taping my mouse button down or fighting the spacesuit thrusters to be engaging gameplay.

[More NPCs](https://www.nexusmods.com/x4foundations/mods/96) by ___Shamon___

- By default this is set at 100, I dropped mine down to 50 because while it feels great out on the docking platforms it becomes quite silly in the smaller rooms and offices. I remember walking into a bar to deliver illegal wares and having to crouch jump up the railing because there were too many NPCs loitering about the place XD. If you're running on minimum specs as is, consider either deleting this file entirely or setting it to a much lower value (I believe the game default is 20?) More NPCs being rendered means more strain on both your CPU and GPU!

[Better Tractor Beam](https://www.nexusmods.com/x4foundations/mods/55) and [Shorter Travel Drive for Big Ships](https://www.nexusmods.com/x4foundations/mods/99) by ___Spacecop42___  

- I played with the defaults for a while and settled on reducing the speed of the containers a smidge as well as boosting the range by 0.5 km. Nothing drastic, but just enough to make it feel right.
- Added in Split engines and Linux compatibility, all L and XL All-Round drives have their charge times reduced to 7 and 10 seconds respectively while Travel varients are 10 and 12 for L/XL.

[Build Time Reduction](https://www.nexusmods.com/x4foundations/mods/139) ___mjr121___  

- Big changes here. The original mod cuts all construction except for Xenon by 10 fold. This means connectors build in like 10 seconds. I appreciate the wait for a complicated module to build, but the vanilla game just chugs when you want to start throwing down super factories. After many hundreds of hours of playing with this, I've currently gotten the times cut down by 40%. I will likely change this again as the game develops. ADDITIONALLY, I've added all the split architecture as well!

[Skip Station Scan]() by ___navik659___  

- You can check out the exact values in the file, but in general you will get more information with less scanning. Things which are more secretive or should not be general knowlege will still require up to 70% of the station to be scanned

[Fix Illegal Buy]() by ___TheLich___  

- Blackmarket dealers no longer refuse to buy hacking tools due to your "reputation being too low"

[Rare Modparts Sold]() by ___t12121970___  

- Traders have a small chance to sell mod parts in very limited quantities

---

_If any of the mod owners do not want their scripts included please let me know and I will remove them immediately! I'm not doing this to step on anyones toes, I just really love this game series and want to start being more active in the community that makes it better!_
