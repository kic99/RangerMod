
# RangerMod by kic (for 7 Days to Die alpha 20)
## Disclosure: This is a personal project and is designed, primarily, for my enjoyment and use on my [YT channel](https://youtube.com/kic). I'm releasing it to the public in case someone is interested in it. Because it's a personal project, that's the primary lens through which I view balancing, features, etc., but I welcome constructive feedback.

----------------
### Download and Installation

On github and can't find the file? Look under "Releases" on the right. That's what you want. On Nexus or some other site? Probably under "Files" or whatever.

Installing? Unzip the RangerMod.zip file and put the resulting RangerMod-kic folder (see note below) into your 7DaystoDie/Mods folder. It's the same as pretty much every other modlet. If you're putting it on a server, it needs to be on both server and client machines. If you're installing on a Mac or Linux, google how to install mods on those. (For Mac, I know it involves finding the 7 Days to Die package, opening those contents, and then adding a mods folder in the resulting folder, into which the RangerMod folder should go. Really, just google it, because I may have forgotten a step.) To be clear, this is for alpha 20. It has not been tested on previous versions and may or may not work on those.

**NOTE**: Slightly elongated installation instructions: when you unzip the release file, you'll get a folder as a result. That folder is what should go into your Mods directory. If things aren't working or things are funky, then make sure you mirror the structure that's listed on [github](https://github.com/kic99/RangerMod), meaning you want the "RangerMod-kic" folder that contains the Config and UIAtlas folders to be one that's in your Mods directory.

**NOTE part 2,the notening**: if you're already using mods that add arrows and include them on the radial menu, you're probably going to run into issues. RangerMod makes it so you have 10 arrows on the radial menu--11 is the maximum allowed before the game barfs and your bow stops working. I don't have a fix for this nor an ETA if I can even fix it (I've failed miserably thus far), so you have to decide which mod(s) you want to use. Additionally, some mods change the way bows/arrows are setup in the game, meaning that you're going to end up with conflicts. Basically, use other archery mods at your own risk. Even if the combination of mods does technically work, some mods modify vanilla game items, meaning that you're getting a weird combination of things that was never planned nor accounted for.

----------------
### Version history

.1 Initial release: 5 arrows, 3 item mods, 1 spear.
.2 Bug fixes and new items. Bugs fixed: arrows now scrap to metal and no longer generate particle effects errors in console. New items: 2 spears, 2 bows.

----------------
### Author's mindless babbling

As noted in the disclosure, this is a personal project that spawned from a desire to improve archery in the game. Archery is fun, but it's limited: it's not end-game viable, and mod diversity for bows is practically nonexistent. I aimed to address what I saw as a problem, and from there, I kept going. I'm not saying this is perfect, nor everything addressed, not by any stretch. Rather, this is a good starting point, but I have no specific end-game plans because modding definitely isn't something I'm adept at and I'm not sure I have the time required to learn to do all the things I want (and I'm fairly certain some of them would require dll editing, not just easy xml changes, and I'm definitely not going there).

This mod originally started as a trick arrow mod, inspired by the likes of City of Heroes and Marvel's Hawkeye character, as well as countless other Hollywood and print legends. I'll continue tweaking things here and there, but don't expect large changes. I've tried some other ideas for arrows, but I can't make them work. I may hit up some actual modders to see if I can get some hints or outright help, but getting these other ideas to work will take a while, if at all. I've tried to focus on adding something that's fun, so that's where we are. While I'd like to add more arrows, I'm also a little concerned with cluttering up the radial ammo menu even more, so I'm debating how to resolve that, assuming I ever get any of the other arrow ideas to work.

If you're looking for a description of what is in the mod and how it works, then you're in luck. If you don't want things spoiled, then **stop reading immediately**. From this point forward, consider this file a spoiler.

----------------
### Spoilery contents

* Five trick arrows
* Two bows
* Three mods
* Three spears
* Miscellaneous schematics

Be aware there are no new meshes in the mod. All of the items I've added are recycled from existing in-game graphics. The icons are modified, and the items themselves (arrows) have tinting on them to make it easier to quickly identify, but there are no new models. The arrows pretty much look like colored steel arrows, and when you find a quiver and install it on the chest armor, you won't see anything change on your armor. This is, more or less, how the game works already with respect to some mods, but the reason there aren't new models is that I'm not a modeler. If you are and want to contribute some models, get in touch with me and we can talk. Otherwise, I have no plans to change this at the current time.

### Arrows
The arrows all require your target to be directly hit. As in, you must hit a zombie or an animal. Hitting the floor, the tree next to the zed, or whatever, will result in nothing happening (except for the breach arrow; more on that below). Also, all arrows can only be crafted. You will **not** find them in loot or in the traders' stores, but you will find schematics in loot and traders (minus Black Talon). I'm considering adding a "quest rewards package" similar to what you can get for flaming/exploding arrows, but this is not currently in the mod. All bundles are for 75 arrows with the resource costs discounted for bulk crafting (similar to standard, vanilla large-quantity crafting). At this time, the special effects don't work on players, or at least, they shouldn't. That's a whole other problem/balancing issue I'm not sure how I want to address, if at all.
* Black Talon - this is your single-target, high damage arrow. It does more damage than a standard steel arrow, has slightly higher velocity, and has an incredibly effective damage over time (DoT) that does roughly 70 additional damage in about six seconds. Additionally, based on your Penetrator perk (yes, Penetrator), this arrow does armor shred, more heavily weighted towards full perk level (4). This arrow is unlocked by reaching Archery perk level 5: both single arrow and bundle. **NOTE:** enemies that die to the DoT *may* not provide exp! I've had reports of this, but I haven't personally noticed it. I also don't know a way to code around this, so be warned. 
* Breach - this is the only arrow you can hit a block with and do something useful, because it's a shotgun breach shell turned into an arrow, and made more effective to account for the reload time of the bow, though not massively more effective. You'll still need a handful of arrows for the more fortified "hardened chest," but it's a valid way of getting access without endlessly drilling or smashing with a pickaxe or using lockpicks. I'm not saying it's a better choice, rather, it's an option. This also works against doors, and you might find those a better target. Same damage, but doors tend to be much weaker. You'll destroy all but the most hardened doors in one shot. Don't use this arrow against zeds: it'll do less damage than you expect. It's meant for structures, not squishies. Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Bulldozer - that tightly packed group of enemies in front of you is a great target for this arrow. Does standard steel arrow damage to the target it hits and applies a ragdoll (knock up and brief stun) effect to that target and those nearby. The radius of the ragdoll effect is based on your Archery perk: the higher your perk, the larger the radius. It's also weighted more towards full perk value (5). Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Entangling - Another arrow meant for crowd control, this one does standard steel arrow damage to the target enemy, as well as slows them. Has a radius of effect that'll apply a slow effect to nearby zeds and animals based on your Archery perk level, weighted more towards full perk value (5). It may sometimes look like it's not working, but if you watch the creature's movement carefully, you'll often notice that they're in rage (running) mode, but they're moving slowly for that mode (it still looks similar to fast walking). That means it's working as intended. Single arrow crafting is unlocked via schematic; bundle unlocked via completing the entire Ranger line of books.
* Shock - everyone who has written an arrow mod has done of these why, but this one zaps a group. Like the other crowd control arrows, the area of effect scales based on Archery perk level, weighted more towards full perk level (5). Single target damage is standard steel arrow, plus the addition of the shock (everyone takes shock damage, so keep that in mind in case of things dying and potentially losing EXP -- I can't confirm this, but I won't be surprised by it. I also can't fix it if so). This is also known as the "dance party" arrow if you can cluster up the zombies well enough.

### Bows
Version .2 introduces new bows to the mod. Why? Because I wanted to. You don't have to use them, but the whole point of this mod is to spice up your archery (and spear) game. Both bows have schematics that you can find in loot or purchase from a trader, luck depending, of course.

* Talon's bow - This bow is designed to fire arrows quickly. This is accomplished by a reduced draw time as well as allowing you to nock up to three arrows at a single time, thus letting you rapid-fire arrows in succession. Unfortunately, you're limited to nocking nocking only a single arrow type at given time. Keep that mind if you're using something other than standard stone/iron/steel arrows where you may not need/want to fire them off so rapidly (or maybe you do...). By default, this bow will only nock 1 arrow; at Archery perk level 3 you can nock 2, and at Archery 5 you can nock 3. You can tell how many arrows you have nocked because you'll see them nock on the bow--this is a vanilla function in the game and looks a little goofy, but it works reasonably well. Talon's bow is based on the wooden bow, meaning damage and velocity are roughly equivalent. While holding the bow, you'll also receive a minor run speed increase (5%).
* Titan bow - Where Talon's bow is more for rapid-fire, the titan bow requires you to really consider your target. At Archery perk 5, and only at Archery perk 5, you can not only nock 2 arrows, but you can fire them simultaneously, meaning you're doing double damage compared to a standard bow. Both arrows will follow the exact same path to your reticle, meaning you can't fire at separate targets. The titan bow is based on the compound bow, providing comparable (slightly higher) damage and velocity at the expense of longer draw time and recoil. This is not a good weapon for being up close and personal and needing to snap off shots; it's a great weapon from a distance to start a battle, or when you have range and only one or two targets to deal with. This is meant to provide some extra oomph at the later stages of the game, thus the Archery perk 5 requirement.


### Item Mods
All of the mods can be found as schematics in loot or for sale by the trader, or as functional items in loot or for sale by the traders. These are meant for bows, but one item (noted below) works with crossbows.
* Stabilizer - a long stabilizer to attach to your bow. This will tighten your reticle and provide more accurate shots. It can be attached to any bow. I forget which specific "part" of the weapon it is (weapons have "parts" for which they can have a mod, and only one mod can be applied at any give time per "part"), but it may be barrel or something that previously had no part, meaning you can now have four total mods on your bow. What a novel idea!
* Upgraded cams - high quality cams that increase draw strength, leading to increased arrow velocity and less drop-off. Like the stabilizer, these can be applied to any bow. Yes, that means the primitive and wooden bow. Why? Because I didn't feel like limiting it to only the compound, which would have likely required making my own compound bow that wouldn't functionally be any different and would only serve to clutter up the game. This mod can also be installed on crossbows.
* Trick arrow quiver - this attaches to chest armor, and chest armor only. Why? Because it's inspired by the horribly-inaccurate-but-looks-awesome Hollywood/comic/etc. stuff of yore. The quiver applies a reload bonus so you can fire arrows faster. Primarily, you'll notice that draw time is reduced (faster draw) the more you increase your Archery perk, with the weighting of the effect being more heavily towards the full perk value (5). It's not a massive increase, but it's noticeable, especially if you're used to the vanilla speeds.

### Spears
As of version .2 there are now stabby spears for all regular spears. Stabby spears are exactly what they sound like: they're stabby. If you're still confused by that, put plainly, you can't throw them--you can only stab with them.

Why would you want this? Because throwing spears is an exercise in frustration half of the time. Maybe you're better than me, or you have better luck, but when I throw a spear, I miss enough times that it's annoying to have to run around the mob, find the spear, and pick it up again to attack. And that's assuming that when I found the spear I was even presented with the option to press "E" and pray to get the spear, because half the time I don't, and the other half of the time, my sacrifices to Baal or whoever are insufficient because I'm rewarded with nothing but the clacking of my keyboard and an empty hand. So why am I yeeting this stupid thing again?

Thus, stabby spears. Stone is available from the start, iron and steel need schematics/books/whatever to learn them. Functionally, they're shovels, but they're spears, so stab away and enjoy never losing your spear again, unless you hit your hotkey for dropping your equipped item. Been there, noticed it minutes later after the item despawned.

The implementation of these is far from perfect, but they're intentionally janky so that anyone upgrading from a previous version of the mod (**the** previous version) doesn't get their character wiped and lose all progress. All hail the jank!

The spears are still considered to be in-development, meaning that damage, stamina usage, perk effects, etc. are still being tested and tweaked. The loss of damage via throwing the spear means that the stabby spears should have some other *something* to them, I'm just not sure what that is quite yet.

### If you made it this far and actually read everything, be sure to award yourself 10 points. You've earned them.
