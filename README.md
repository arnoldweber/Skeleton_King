# Skeleton King Restoration Mod for Dota 2
(updated **December 20, 2018**)

!["Death has no grip on me!"](https://d1u5p3l4wpay3k.cloudfront.net/dota2_gamepedia/0/07/Skeleton_King_icon.png)

This is a restoration mod for Dota 2 that returns our rightful ruler, the Skeleton King, to his proper place on the throne of bone. It includes the original model, spell icons, UI/minimap icons, voiceover lines and skill names/descriptions.

It's a client-side mod, meaning only you the user will see the effects. To the best of my knowledge this type of modding is not currently ripe for VAC banning, but I take no responsibility if that should change in the future.

Cosmetics aside from the original model aren't currently available, as... I've no knowledge whatsoever of modelling and it seems like work. If anyone would like to help out with that, I'd love to hear about it. Also, as I'm afraid I only speak English the text has only been changed for that language. If you'd like to submit translations for another language I'd be more than happy to add them.

If you have any questions or feedback, feel free to hit me up here or on reddit at https://www.reddit.com/user/apekillape

Enjoy!

## How to Install
1. Download the pak01_dir.vpk file from this page
1. Go to SteamLibrary\steamapps\common\dota 2 beta\game and create a folder named "skeleton_king_returns".
2. Drop the pak01_dir.vpk file there.
3. Open teamLibrary\steamapps\common\dota 2 beta\gamedota\gameinfo.gi in notepad.
4. Under the line "Game_LowViolence	dota_lv" but above the line "Game	dota", add the line "Game	skeleton_king_returns".
5. Save that file and you're done!

## How to Uninstall
You can simply remove the line "Game	skeleton_king_returns" from your gameinfo.gi file, delete the pak01_dir.vpk file/folder, or both.

## Do I need to update this mod when Dota 2 is updated?
Not always, but there are some key times when it'll be necessary:
- When a new hero is added, as they'll have no minimap icon
- When there's a new event, as the dota_english.txt file won't have it

I'll do my best to get the mod updated in a timely fashion, but if I've fallen behind feel free to bug me about it.

## Shout-Outs
I'm a terrible programmer and a worse modeller, so this couldn't possibly have been done without some key insight from a few people:
- SanyaBane and ShutnikMods, whose guides helped me create the original version of the mod
- Ohh_Noes, who fixed the model on the previous version
- TheZett, whose post on [this thread](https://www.reddit.com/r/DotA2/comments/8yymx9/item_icons_mods_dont_work_since_one_of_latest/) finally clued me in how the wonky new png to vtex_c conversion works
- Arktomys, who reminded me to get back to work on this
