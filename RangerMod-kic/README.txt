# RangerMod by kic (for 7 Days to Die alpha 20)
## Disclosure: This is a personal project and is designed, primarily, for my enjoyment and use on my [YT channel](https://youtube.com/kic). I'm releasing it to the public in case someone is interested in it. Because it's a personal project, that's the primary lens through which I view balancing, features, etc., but I welcome constructive feedback.

### Download and Installation

On github and can't find the file? Look under "Releases" on the right. That's what you want. On Nexus or some other site? Probably under "Files" or whatever.

Installing? Unzip the RangerMod.zip file and put the resulting RangerMod-kic folder (see note below) into your 7DaystoDie/Mods folder. It's the same as pretty much every other modlet. If you're putting it on a server, it needs to be on both server and client machines. If you're installing on a Mac or Linux, google how to install mods on those. (For Mac, I know it involves finding the 7 Days to Die package, opening those contents, and then adding a mods folder in the resulting folder, into which the RangerMod folder should go. Really, just google it, because I may have forgotten a step.) To be clear, this is for alpha 20. It has not been tested on previous versions and may or may not work on those.

**NOTE**: Slightly elongated installation instructions: when you unzip the release file, you'll get a folder as a result. That folder is what should go into your Mods directory. If things aren't working or things are funky, then make sure you mirror the structure that's listed on [github](https://github.com/kic99/RangerMod), meaning you want the "RangerMod-kic" folder that contains the Config and UIAtlas folders to be one that's in your Mods directory.

**NOTE part 2, the notening**: if you're already using mods that add arrows and include them on the radial menu, you're probably going to run into issues. While I'm grateful for the assistance I've received from XXX by way of XXX to include a modification that allows more than the standard number of arrows to be on the radial, you'll probably run into problems if you're using other mods. For the brave: go into my mod, dive into the XUi folder, open the windows.xml, and add another couple of lines of the "<radial entry/>" to that spot. You might need another six or so to work with other mods--just add one at a time until it works. If you can't get it to work, I'm sorry.

**NOTE part 3, the renotening**: I've been using the same game save as I update the mod--so far, everything works without breaking my save. That said, back up your save before updating the mod to be safe.

----------------
### Version history

.1 Initial release: 5 arrows, 3 item mods, 1 spear.
.2 Bug fixes and new items. Bugs fixed: arrows now scrap to metal and no longer generate particle effects errors in console. New items: 2 spears, 2 bows.
.3 Holy crap. So many more lines of code. New items: 3 arrows, 1 bow, 1 spear, 1 duster, 1 iron helmet, 1 shotgun pistol (I said it), 1 pair of shoes, 5 quests, 7 books, and all the crap behind the scenes to make that stuff work. Also, bug fixes, adjustments to Talon's and Titan's bows, items renamed, some recipes removed, and changed how some things are unlocked. This version is foundational, assuming I figure out how to do the other things I want.

----------------
### Thanks and stuff

Thanks to everyone who has downloaded and endorsed this mod on Nexus. I appreciate it. Thanks as well to everyone has provided feedback--both good and bad--so long as it was constructive. If it wasn't, no thanks to you.

Also, particular thanks to:
* Everyone who has reported bugs
* XRedMillenniumX for the code to let me use more arrows
* AuroraGiggleFairy also for the code to let me use more arrows
* So many modders in the 7 Days scene whose mods I looked at to help figure this stuff out. Even if I never talked to them, they've been immensely helpful.
* FletchSlade for playtesting and brainstorming
* A small assortment of folks on Pixabay who've made their creations free to use. I need to track down everyone and say thanks properly, but this is a start.

 
----------------
### Author's mindless babbling

As noted in the disclosure, this is a personal project that spawned from a desire to improve archery in the game. Archery is fun, but it's limited: it's not end-game viable, and mod diversity for bows is practically nonexistent. I aimed to address what I saw as a problem, and from there, I kept going. I'm not saying this is perfect, nor everything addressed, not by any stretch. Rather, this is a good starting point, but I have no specific end-game plans because modding definitely isn't something I'm adept at and I'm not sure I have the time required to learn to do all the things I want (and I'm fairly certain some of them would require dll editing, not just easy xml changes, and I'm definitely not going there). That said, I do have plans, but whether I can get those things done, I don't know.

This mod originally started as a trick arrow mod, inspired by the likes of City of Heroes and Marvel's Hawkeye character, as well as countless other Hollywood and print legends. I'll continue tweaking things here and there, but don't expect large changes. I've tried some other ideas for arrows, but I can't make them work. I may hit up some actual modders to see if I can get some hints or outright help, but getting these other ideas to work will take a while, if at all. I've tried to focus on adding something that's fun, so that's where we are. While I'd like to add more arrows, the radial menu is already a nightmare, so adding even more arrows may not be a good idea.

If you're looking for a description of what is in the mod and how it works, then you're in luck. If you don't want things spoiled, then **stop reading immediately**. From this point forward, consider this file a spoiler.

----------------
----------
------
-----
----
----

### SPOILER -- RangerMod contains -- SPOILER

* Eight trick arrows
* Three bows
* Three mods
* Four spears
* Seven books
* Five quests
* One firearm
* A few pieces of clothing/armor
* One token
* Lore
* Lots of commented XML that you can use to help guide you to make this mod work differently if you so desire

Be aware there are no new meshes in the mod. All of the items I've added are recycled from existing in-game graphics. The icons are modified, and the items themselves (arrows) have tinting on them to make it easier to quickly identify, but there are no new models. The arrows pretty much look like colored vanilla arrows, and when you find a quiver and install it on the chest armor, you won't see anything change on your armor. This is, more or less, how the game works already with respect to some mods, but the reason there aren't new models is that I'm not a modeler. If you are and want to contribute some models, get in touch with me and we can talk. Otherwise, I have no plans to change this at the current time.

### Arrows
The arrows all require your target to be directly hit. As in, you must hit a zombie or an animal. Hitting the floor, the tree next to the zed, or even other players, will result in nothing happening (except for the breach arrow; more on that below). Also, all arrows can only be crafted. You will **not** find them in loot or in the traders' stores, but you will find the books in stores. I'm considering adding a "quest rewards package" similar to what you can get for flaming/exploding arrows, but this is not currently in the mod. All bundles are for 75 arrows with the resource costs discounted for bulk crafting (similar to standard, vanilla large-quantity crafting). At this time, the special effects don't work on players, or at least, they shouldn't. That's a whole other problem/balancing issue I'm not sure how I want to address, if at all.
* Shredder (previously Black Talon) - this is your single-target, armor-wrecking arrow. It does more damage than a standard steel arrow, has slightly higher velocity, and has an incredibly effective damage over time (DoT) that does roughly 70 additional damage in about six seconds. Additionally, based on your Penetrator perk (yes, Penetrator), this arrow blasts through armor, more heavily weighted towards full perk level (4). This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting). **NOTE:** enemies that die to the DoT *may* not provide exp! I've had reports of this, but I haven't personally noticed it. I also don't know a way to code around this, so be warned. 
* Breach - this is the only arrow you can hit a block with and do something useful, because it's a shotgun breach shell turned into an arrow, and made more effective to account for the reload time of the bow, though not massively more effective. You'll still need a handful of arrows for the more fortified "hardened chest," but it's a valid way of getting access without endlessly drilling or smashing with a pickaxe or using lockpicks or doing the smart thing and using timed charges. I'm not saying it's a better choice, rather, it's an option. This also works against doors, and you might find those a better target. Same damage, but doors tend to be much weaker. You'll destroy all but the most hardened doors in one shot. Don't use this arrow against zeds: it'll do less damage than you expect. It's meant for structures, not squishies. This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Bulldozer - that tightly packed group of enemies in front of you is a great target for this arrow. Does standard steel arrow damage to the target it hits and applies a ragdoll (knock up and brief stun) effect to that target and those nearby. The radius of the ragdoll effect is based on your Archery perk: the higher your perk, the larger the radius. It's also weighted more towards full perk value (5). This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Entangling - Another arrow meant for crowd control, this one does standard steel arrow damage to the target enemy, as well as slows them. Has a radius of effect that'll apply a slow effect to nearby zeds and animals based on your Archery perk level, weighted more towards full perk value (5). It may sometimes look like it's not working, but if you watch the creature's movement carefully, you'll often notice that they're in rage (running) mode, but they're moving slowly for that mode (it still looks similar to fast walking). This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Shock - everyone who has written an arrow mod has done of these, but this one zaps a group. Like the other crowd control arrows, the area of effect scales based on Archery perk level, weighted more towards full perk level (5). Single target damage is standard steel arrow, plus the addition of the shock (everyone takes shock damage, so keep that in mind in case of things dying and potentially losing EXP -- I can't confirm this, but I won't be surprised by it. I also can't fix it if so). This is also known as the "dance party" arrow if you can cluster up the zombies well enough. This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Jester’s Joking Jab (arrow) – Jester’s arrow adds a little spice to the mod, as well as some humor. I warned everyone long ago that this isn’t a realistic mod, and this arrow underscores that. Jester and Bedlam worked some magic to create this arrow (though it wasn’t destructive enough for Bedlam’s taste, so he refused to take credit for it) which has a chance to issue one of a few random effects upon impact with an enemy: increase their size, give them a big head, make them bleed, set them on fire, or shock them. Why add this? Because Jester had a sense of humor. This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Pulverizer  arrow – where the Shredder arrow (see above) does its damage over time, the pulverizer arrow is meant to do it all up front. The most expensive arrow to craft, and the most deadly in terms of pure damage numbers, this is meant to be used against only the largest, most dangerous enemies. Sure, you can waste it on a chicken, but that’s on you. However, when combined with Titan’s or Talon’s bows (see below) and archery 5, you can spit out a lot of damage in a short amount of time. Has higher armor penetration than the steel arrow, but not as much as the shredder does at high archery skill. This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).
* Immolation arrow – Bedlam enjoyed using flaming arrows, but they just weren’t potent enough. With some work, testing, and a snicker or two, he came up with the immolation arrow. Light your foes on fire, and their nearby friends. Because why not? Does a significant amount of fire damage. This arrow is unlocked via the Midnight's Secrets book series (for both single and bundle crafting).


### Bows
Version .2 introduces new bows to the mod. Why? Because I wanted to. You don't have to use them, but the whole point of this mod is to spice up your archery (and spear) game. Version .3 added one more bow. See the individual item descriptions for more information.

* Talon's Flurry (bow) - This bow is designed to fire arrows quickly. This is accomplished by a reduced draw time as well as allowing you to nock up to four arrows at a single time, thus letting you rapid-fire arrows in succession. Unfortunately, you're limited to nocking nocking only a single arrow type at given time--again, only one TYPE of arrow at a time. Keep that mind if you're using something other than standard stone/iron/steel arrows where you may not need/want to fire them off so rapidly (or maybe you do...). By default, this bow will only nock 1 arrow; at Archery perk level 3 you can nock 2, at Archery perk 4 you can nock 3, and at Archery 5 you can nock 4. You can tell how many arrows you have nocked because you'll see them nock on the string, as well as listed as X/Y in the ammo detail in the bottom right corner of your UI--this is a vanilla function in the game and looks a little goofy, but it works reasonably well. Talon's bow is based on the wooden bow, meaning damage and velocity are roughly equivalent. While holding the bow, you'll also receive a minor run speed increase (5%). HUGE NOTE: the game can be weird trying to load multiple arrows at once. Just shoot/reload/pray/etc. It'll work again eventually if it stops working. I can't figure out why this happens nor prevent it. This can only be found via questing (no crafting).
* Titan's Domination (bow) - Where Talon's bow is more for rapid-fire, Titan's bow requires you to really consider your target. At Archery perk 5, and only at Archery perk 5, you can not only nock 2 arrows, but you can fire them simultaneously, meaning you're doing double damage compared to a standard bow. Both arrows will follow the exact same path to your reticle, meaning you can't fire at separate targets. Titan's bow is based on the compound bow, providing comparable (slightly higher) damage and velocity at the expense of longer draw time and recoil. This is not a good weapon for being up close and personal and needing to snap off shots; it's a great weapon from a distance to start a battle, or when you have range and only one or two targets to deal with. This is meant to provide some extra oomph at the later stages of the game, thus the Archery perk 5 requirement. Reduced sneak attack damage because otherwise it'd be insanely powerful. This can only be found via questing (no crafting).
* Reaper Initiate's bow - In lore, this was given to those who wanted to be a Reaper. Give them a bow,  a spear, some arrows, and let them learn what it means to be a wasteland ranger. This bow provides something between the terrible primitive bow and the less crappy wooden bow (and let's be honest, the first one or two of the latter you find will be terrible if they're quality 1 or 2), this bow does slightly more damage than the primitive bow, reloads slightly faster, and allows one additional mod at quality 6 (though good like finding enough mods at this stage of the game to fill it up). This can only be found in loot (no crafting). If you blaze through the loot/game stages, but may pass this entirely. It's here just in case.


### Item Mods
All of the mods can be found as schematics in loot or for sale by the trader, or as functional items in loot or for sale by the traders. These are mainly for bows, but one item (noted below) works with crossbows.
* Stabilizer - a long stabilizer to attach to your bow. This will tighten your reticle and provide more accurate shots. It can be attached to any bow. I forget which specific "part" of the weapon it is (weapons have "parts" for which they can have a mod, and only one mod can be applied at any give time per "part"), but it may be barrel or something that previously had no part, meaning you can now have four total mods on your bow. What a novel idea!
* Upgraded cams - high quality cams that increase draw strength, leading to increased arrow velocity and less drop-off. Like the stabilizer, these can be applied to any bow. Yes, that means the primitive and wooden bow. Why? Because I didn't feel like limiting it to only the compound, which would have likely required making my own compound bow that wouldn't functionally be any different and would only serve to clutter up the game. This mod can also be installed on crossbows.
* Trick arrow quiver - this attaches to chest armor, and chest armor only. Why? Because it's inspired by the horribly-inaccurate-but-looks-awesome Hollywood/comic/etc. stuff of yore. The quiver applies a reload bonus so you can fire arrows faster. Primarily, you'll notice that draw time is reduced (faster draw) the more you increase your Archery perk, with the weighting of the effect being more heavily towards the full perk value (5). It's not a massive increase, but it's noticeable, especially if you're used to the vanilla speeds. When combined with high archery skill and Talon's Flurry, you can snap off a lot of shots in a short amount of time.

### Spears
As of version .2 there are now stabby spears for all regular spears. Now called Reaper spears as of version .3, they're spears you can't throw, attack slightly faster than standard spears, use slightly less stamina to attack, and also allow you to pole vault (jump one additional block height). Yes, this means they're slightly overpowered compared to regular spears, but regular spears are hands down the worst melee weapon in the game. Sad but true.

Why would you want this? Because throwing spears is an exercise in frustration half of the time. Maybe you're better than me, or you have better luck, but when I throw a spear, I miss enough times that it's annoying to have to run around the mob, find the spear, and pick it up again to attack. And that's assuming that when I found the spear I was even presented with the option to press "E" and pray to get the spear, because half the time I don't, and the other half of the time, my sacrifices to Baal or whoever are insufficient because I'm rewarded with nothing but the clacking of my keyboard and an empty hand. So why am I yeeting this stupid thing again?
* Reaper spear - Stone, iron, and steel stabby spears. Stone is available from the start (you can craft this immediately--I suggest you do for the jump bonus), iron and steel need schematics/books/whatever to learn them. Functionally, they're shovels, but they're spears, so stab away and enjoy never losing your spear again, unless you hit your hotkey for dropping your equipped item. Been there, noticed it minutes later after the item despawned. Iron and steel can be found via loot or purchased at a trader.
* Bedlam’s Turning Point – Distance is always the best first choice with the undead, but Bedlam sometimes liked to get closer. His spear, while mostly the same as other Reaper spears, had an extra touch: a built-in taser. Though not as potent as a stun baton, the range offered by the spear makes it an interesting choice. Can only be obtained via questing.


### Clothing and Armor

Version .3 includes a few clothing and armor pieces. One of the major focuses of version .3 is lore, and these items, specifically, fill in some of the blanks with respect to each character (Talon and Titan aside as they already have bows as of version .2).
* Midnight’s Shroud – a unique duster worn by Midnight as she led her rag-tag group of rangers on missions throughout the wastelands. The duster has more elemental protection than standard dusters and offers a slight stealth bonus. Can only be obtained via questing.
* Jester’s Delightfully Dreadful Dancing Shoes – where some of the Reapers made logical choices with regards to protective, sensible clothing, Jester wore these absurd shoes as she danced about the battlefield, slinging arrows and bad jokes. While wearing these shoes, she zipped around, a seemingly endless bundle of energy. Provides extra movement speed and stamina regeneration. Can only be obtained via questing.
* Bedlam’s Cage – an iron helmet designed to intimidate, Bedlam’s cage provides solid protection from the dangers of the wasteland, including being relatively difficult to bite through (and thus get infected – can this be done?). Also not bad for intimidating others for better negotiations results. Being a big, metal helmet, it offers some protection against infection. Can only be obtained via questing.


### Firearms

Version .3 adds a gun. Yes, a gun, in what is otherwise an archery heavy mod. Why? Because version .3 begins to introduce the lore elements of this mod, and as it turns out, someone used a gun. In fact, everyone probably did (records are hard to come by in the apocalypse), but Midnight, specifically, had a particular gun she used when things went sideways. You may be interested in finding it.
* Midnight’s Judgment – you might be asking why there’s a firearm in a mod about archery, but the mod’s not about archery. It’s called RangerMod, not ArcheryMod. Midnight, the leader of the wasteland rangers known as the Reapers, used a pistol to put down the undead in addition to other tools. What makes her pistol unique? It fires shotgun shells. This short-barreled pistol shotgun holds four shells, does reasonable damage, and has a wide spray pattern to take down hordes of undead. Sure, it looks like a revolver, but it's not one. The best part? Shotgun and pistol perks affect it. Hint, hint. Does **not** accept magazine/tube mods. This can only be obtained via questing.

### Quests

Five quests await you finding them. Unfortunately, these are all buried supply quests at this time. Fortunately, the rewards are good. If you skipped over all the stuff that told you how and where to find things, then here you go: these quests are how you find Reaper-specific stuff (outside of Reaper spears, initiate bows, mods, and books). If you want Talon or Titan's bow, find the quest. Want Midnight's sidearm? Quest. Want Jester's shoes? Quest. I think you see where this is going, so I'll stop, now.

Additional quests may be added in the future, assuming I can figure out how to add something beyond terrible digging quests. Don't hold your breath waiting for this.

### Miscellaneous

Seven books exist in RangerMod waiting to be found. These are how you unlock the recipes for all of the arrows in the mod, with the series completion award being the bundle (bulk crafting) recipes for all of them.

Additionally, there's an item called Reaper Token that currently has no use. I have plans for these, so don't throw them away or scrap them.

----
That's it. That's a really, really long readme, but it has useful stuff in there. I think. Enjoy the mod, tell your friends, and go save the wasteland. Someone's gotta do it.

### If you made it this far and actually read everything, be sure to award yourself 10 points. You've earned them.