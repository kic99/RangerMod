# RangerMod by kic
## Disclosure: This is a personal project and is designed, primarily, for my enjoyment and use on my YT channel. I'm releasing it to the public in case someone is interested in it. Because it's a personal project, that's the primary lens through which I view balancing, features, etc., but I welcome constructive feedback.

----------------
### Download and Installation

If you're staring at this on github, look for the folder named "insertfoldernamehere" and go into that. You'll see a .zip file for each release of the mod. The larger the version number at the end of the file name, the more recent. You can also look at the date as well. ;)

For installation, unzip the RangerMod.zip file and put the resulting RangerMod folder into your 7DaystoDie/Mods folder. It's the same as pretty much every other modlet. If you're putting it on a server, it needs to be on both server and client machines. If you're installing on a Mac or Linux, google how to install mods on those. (For Mac, I know it involves finding the 7 Days to Die package, opening those contents, and then adding a mods folder in the resulting folder, into which the RangerMod folder should go. Really, just google it.)

----------------
### Author's mindless babbling

As noted in the disclosure, this is a personal project that spawned from a desite to improve archery in the game. Archery is fun, but it's limited: it's not end-game viable, and mod diversity for bows is practically nonexistent. I aimed to address what I saw as a problem, and from there, I kept going. I'm not saying this is perfect, nor everything addressed, not by any stretch. Rather, this is a good starting point, but I have no specific end-game plans because modding definitely isn't something I'm adept at and I'm not sure I have the time required to learn to do all the things I want (and I'm fairly certain some of them would require dll editing, not just easy xml changes, and I'm definitely not going there).

This mod originally started as a trick arrow mod, inspired by the likes of City of Heroes and Marvel's Hawkeye character, as well as countless other Hollywood and print legends. I'll continue tweaking things here and there, but don't expect large changes. I've tried some other ideas for arrows, but I can't make them work. I may hit up some modders to see if I can get some hints or outright help, but getting these other ideas to work will take a while, if at all. I've tried to focus on adding something that's fun, so that's where we are. While I'd like to add more arrows, I'm also a little concerned with cluttering up the radial ammo menu even more, so I'm debating how to resolve that, assuming I ever get any of the other arrow ideas to work.

If you're looking for a description of what is in the mod and how it works, then you're in luck. If you don't want things spoiled, then **stop reading immediately**. From this point forward, consider this file a spoiler.

----------------
### Spoilery contents

* Five trick arrows
* Three mods
* One spear
* Miscellaneous schematics

Be aware there are no new meshes in the mod. All of the items I've added are recycled from existing in-game graphics. The icons are modified, and the items themselves (arrows) have tinting on them to make it easier to quickly identify, but there are no new models. The arrows pretty much look like colored steel arrows, and when you find a quiver and install it on the chest armor, you won't see anything change on your armor. This is, more or less, how the game works already with respect to some mods, but the reason there aren't new models is that I'm not a modeler. If you are and want to contribute some models, get in touch with me and we can talk. Otherwise, I have no plans to change this at the current time.

### Arrows
The arrows all require your target to be directly hit. As in, you must hit a zombie or an animal. Hitting the floor, the tree next to the zed, or whatever, will result in nothing happening (except for the breach arrow; more on that below). Also, all arrows can only be crafted. You will **not** find them in loot or in the traders' stores, but you will find schematics in loot and traders (minus Black Talon). I'm considering adding a "quest rewards package" similar to what you can get for flaming/exploding arrows, but this is not currently in the mod. All bundles are for 75 arrows with the resource costs discounted for bulk crafting (similar to standard, vanilla large-quantity crafting). At this time, the special effects don't work on players, or at least, they shouldn't. That's a whole other problem/balancing issue I'm not sure how I want to address, if at all.
* Black Talon - this is your single-target, high damage arrow. It does more damage than a standard steel arrow, has slightly higher velocity, and has an incredibly effective damage over time (DoT) that does roughly 70 additional damage in about six seconds. Additionally, based on your Penetrator perk (yes, Penetrator), this arrow does armor shred, more heavily weighted towards full perk level (4). This arrow is unlocked by reaching Archery perk level 5: both single arrow and bundle. **NOTE:** enemies that die to the DoT *may* not provide exp! I've had reports of this, but I haven't personally noticed it. I also don't know a way to code around this, so be warned. 
* Breach - this is the only arrow you can hit a block with and do something useful, because it's a shotgun breach shell turned into an arrow, and made more effective to account for the reload time of the bow, though not massively more effective. You'll still need a handful of arrows for the more fortified "hardened chest," but it's a valid way of getting access without endlessly drilling or smashing with a pickaxe or using lockpicks. I'm not saying it's a better choice, rather, it's an option. This also works against doors, and you might find those a better target. Same damage, but doors tend to be much weaker. You'll destroy all but the most hardened doors in one shot. Don't use this arrow against zeds: it'll do less damage than you expect. It's meant for structures, not squishies. Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Bulldozer - that tightly packed group of enemies in front of you is a great target for this arrow. Does standard steel arrow damage to the target it hits and applies a ragdoll (knock up and brief stun) effect to that target and those nearby. The radius of the ragdoll effect is based on your Archery perk: the higher your perk, the larger the radius. It's also weighted more towards full perk value (5). Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Entangling - Another arrow meant for crowd control, this one does standard steel arrow damage to the target enemy, as well as slows them. Has a radius of effect that'll apply a slow effect to nearby zeds and animals based on your Archery perk level, weighted more towards full perk value (5). It may sometimes look like it's not working, but if you watch the creature's movement carefully, you'll often notice that they're in rage (running) mode, but they're moving slowly for that mode (it still looks similar to fast walking). That means it's working as intended. Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Shock - everyone who has written an arrow mod has done of these why, but this one zaps a group. Like the other crowd control arrows, the area of effect scales based on Archery perk level, weighted more towards full perk level (5). Single target damage is standard steel arrow, plus the addition of the shock (everyone takes shock damage, so keep that in mind in case of things dying and potentially losing EXP -- I can't confirm this, but I won't be surprised by it. I also can't fix it if so). This is also known as the "dance party" arrow if you can cluster up the zombies well enough.

### Item Mods
All of the mods can be found as schematics in loot or for sale by the trader, or as functional items in loot or for sale by the traders. These are meant for bows, but one item (noted below) works with crossbows.
* Stabilizer - a long stabilizer to attach to your bow. This will tighten your reticle and provide more accurate shots. It can be attached to any bow. I forget which specific "part" of the weapon it is (weapons have "parts" for which they can have a mod, and only one mod can be applied at any give time per "part"), but it may be barrel or something that previously had no part, meaning you can now have four total mods on your bow. What a novel idea!
* Upgraded cams - high quality cams that increase draw strength, leading to increased arrow velocity and less drop-off. Like the stabilizer, these can be applied to any bow. Yes, that means the primitive and wooden bow. Why? Because I didn't feel like limiting it to only the compound, which would have likely required making my own compound bow that wouldn't functionally be any different and would only serve to clutter up the game. This mod can also be installed on crossbows.
* Trick arrow quiver - this attaches to chest armor, and chest armor only. Why? Because it's inspired by the horribly-inaccurate-but-looks-awesome Hollywood/comic/etc. stuff of yore. The quiver applies a reload bonus so you can fire arrows faster. Primarily, you'll notice that draw time is reduced (faster draw) the more you increase your Archery perk, with the weighting of the effect being more heavily towards the full perk value (5). It's not a massive increase, but it's noticeable, especially if you're used to the vanilla speeds.

### Spear
I've added a stabby spear to the game. This is an in-progress item (meaning it's incomplete-but-functional) and is exactly what it sounds like: a spear that stabs, and only stabs. You can't throw this thing and lose it. You also can't throw it and do a ton of damage based on your Spear perk, so you're limited to stabbing, and stabbing harder. Why? Because I don't like throwing my spear, running around trying to find it, tapping the key to pick it up only to not pick it up and now spam the button in panic while a zombie closes in only to have to run away and switch to another weapon, kill the zed, and then go back to get the stupid spear. That annoys the crap out of me, so I added the stabby spear.

It's currently **only** the steel spear, but the plan is for to be stone, iron, and steel. To do that, I need to rebuild the spear entirely, so it's going to be a hiccup or three before it's done. You can find the steel stabby spear in loot, for sale by the trader, or craft it. Steel spear crafting unlocks via one of the spear books normally, and now it unlocks the stabby spear as well. I'm trying to figure out the least obnoxious way to add a "converter" to allow you to turn the regular steel spear into a stabby one and vice versa, but that's also stuck on the "to-do" list.

If it's not abundantly clear, this is an incomplete item. Spears in this game are meant to be thrown, and the Spear perk grants additional damage and effects to throws. I've not yet had a chance to address this with respect to a spear that can't be thrown, so it just does damage and nothing more right now. I don't expect its current implementation to be final, whether speaking of the damage, endurance required, or other. And if you're at all curious how this was done, yes, it's a shovel. That's literally what it is, just made into a spear. Weapon animations are tied to "hold types" in this game, and I don't know how to implement one "hold type" for the basic attack and another for the power attack. I suspect you can't, which means you get a shovel converted into a spear, which means the attack patterns aren't ideal, nor the range particularly accurate with respect to the animation. That may be reason enough to not add this to the mod, but it was a personal challenge to see if I could make one, ugly or not, and here we are.


### If you made it this far and actually read everything, be sure to award yourself 10 points. You've earned them.
