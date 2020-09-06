<!-- + Bryan's Preferred FoundryVTT Modules + -->

<img src="https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Full%20-%20Social%20-%20On%20Dark.png" width="0" height="0">

![Bryan's Preferred FoundryVTT Modules](https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Title%20-%20On%20White.png)

My personally cultivated list of FoundryVTT Modules that play nicely together without creating an overwhelming amount of UI options or causing noticeable FPS drops; not everyone has a new computer. Collectively they set up a solid foundation for any D&D 5e and Pathfinder 2e campaign.

## Core Settings
- Configure Audio / Video > Audio / Video Conference Mode: Disabled
  - Even having this enabled and not using it will cause idle FPS to drop 30-50%. Use Discord for now.

## Quality of Life Improvements For Everyone
- [Chat Portrait](https://foundryvtt.com/packages/ChatPortrait/) - Show Actor’s portrait in chat.
- [Compendium Folders](https://foundryvtt.com/packages/compendium-folders/) - Adds a nested folder structure, and option for hiding entries, for your compendiums
- [Cursor Zoom](https://gitlab.com/foundry-azzurite/cursor-hider) - Mouse scroll zooming will center around the cursor instead of around the center of the screen.
- [Deselection](https://github.com/Sky-Captain-13/foundry/tree/master/deselection) - Allows you to deselect a token or tokens by clicking any empty spot on the map.
- [Dice So Nice](https://gitlab.com/riccisi/foundryvtt-dice-so-nice) - Adds the ability to show a 3D dice simulation when a roll is made.
  - Hide FX: None
  - Sound Effects: Off
  - Shadows Quality: Off
  - Advanced Lighting: Off
- [Haste](https://gitlab.com/jesusafier/haste) - Performance enhancement and tweaks. - Suggested by jniezink on the FoundryVTT Subreddit
  - Configure Settings > Module Settings > Fix CPU on token movement
  - Configure Settings > Module Settings > Experimental Adaptive GPU fps tweak
- [Less Fog](https://github.com/trdischat/lessfog) - Tweaks fog of war visibility for GM and Players.
- [Polyglot](https://foundryvtt.com/packages/polyglot/) - Talk to others using a language your selected character can understand and scrambles in-character text you can't understand. - Suggested by jniezink on the FoundryVTT Subreddit
- [Quick Insert](https://foundryvtt.com/packages/quick-insert) - Quick Insert (control + space) provides a context-aware search/autocomplete tool that can be used
in most parts of FoundryVTT. Find actors, items, spells etc. and insert them wherever you need them right now - the map, character sheets, roll tables, journals, you name it. - Suggested by LorduFreeman on The Foundry Discord
  - The default short key (control + space) must be changed as it's already in use by Search Anywhere. This can be done in the module's settings.
- [Search Anywhere](https://gitlab.com/riccisi/foundryvtt-search-anywhere) - Press (control + space) to quickly search for any entity by name via a handy auto-complete widget.
- [Show Drag Distance](https://github.com/wsaunders1014/showdragdistance) - Shows distance you've dragged the token as if you used the Ruler tool.

## Quality of Life Improvements For GameMasters
- [Actually Private Rolls](https://github.com/syl3r86/Actually-Private-Rolls) - Hides Private GM Rolls completely rather than just obfuscating the result. This can be toggled on or off in the Settings Menu.
- [Background Volume](https://github.com/mtvjr/background-volume) - Allows the DM to configure the volume of a scene's background
- [GM Notes](https://foundryvtt.com/packages/gm-notes/) - Add GM-Only notes to entities (Actor, Items (including owned items), RollTable, and JournalEntry).
- [GM Scene Background](https://github.com/death-save/gm-bg) - Allows GMs to set a GM-only background image.
- [GM Token-Drag Visibility](https://github.com/SteffanPoulsen/token-drag-visibility) - Module that disables the vision limitation when dragging a token as a GM. Useful for moving players between floors on the same map.
- [Group Roll Checks and Saves](https://github.com/trdischat/grouproll) - Facilitates D&D 5e and Pathfinder 2e Group Rolls.
- [QuickSceneView](https://gitlab.com/reichler/quicksceneview) Foundry VTT module that adds a Scene Directory context menu to directly view a scene. - Suggested by jniezink on the FoundryVTT Subreddit
- [Token Info Icons](https://github.com/jopeek/fvtt-token-info-icons) - Displays Speed, AC, and Passive Perception on Tokens for the GM.
- [Trigger Happy](https://foundryvtt.com/packages/trigger-happy/) - Create triggers for your players to spring traps or anything you can think of.
- [Virtual Tabletop Assets - Tokenizer](https://www.vttassets.com/assets/vtta-tokenizer) - A tool to help generate token “token” images and their avatars.
  - NOTE: If you try to edit an actor who is in already placed in a scene, it will edit their Compendium entry but not the version of them already placed into the scene.

## General Ambiance
- [Ambient Doors](https://github.com/EndlesNights/ambientdoors) - Customized sounds effects that trigger for all users when interacting with doors.
- [Dancing Lights v2](https://github.com/BlitzKraig/fvtt-DancingLights) - Better ambient lighting & Token light toolkit - Suggested by jniezink on the FoundryVTT Subreddit
  - This feature will be coming soon to FoundryVTT 7 core. Once it is, this module can be removed.
- [Maestro](https://github.com/death-save/maestro) - Adds player hype tracks, item tracks, combat tracks, and more.
  - Enable Hype Track: On
  - Enable Combat Track: On
  - Create Combat Tracks Playlist: On
  - Disable Dice Sounds: On
  - Enable Critical Success / Failure Tracks
- [Music Assistant](https://github.com/temportalflux/MusicAssist) - Adds support for youtube tracks in audio playlists.
  - Note: I've had issues with music not playing and having to stop/start tracks. Still worth it.

## Combat
- [Combat Enhancements](https://gitlab.com/asacolips-projects/foundry-mods/combat-enhancements) - Improved initiatives tab with health tracking and drag and drop reordering.
- [Combat Ready!](https://github.com/smilligan93/combatready) - Shows a graphic + sound for players a round just before a player's turn (Next Up) and during their turn.
  - Disable ‘Next Up’ notification: Off
  - Disable Timer: On
  - Show End Turn Dialog: On
  - Ticking Sound: Off
  
## Dungeon and Dragons 5e (D&D 5e) Specific
- [Plutonium by 5e Tools](https://wiki.5e.tools/index.php/FoundryTool_Install) - What could this be?
  - Cog > Actors > Enable Sheet Popout Button
  - Cog > Actors > Auto-Roll Multiattacks
  - Cog > Tokens > Display missing Health
  - Cog > UI > Compact Header Buttons
  - Cog > UI > Compact Scenes Directory
  - Cog > UI > Compact Actors Directory
  - Cog > UI > Compact Items Directory 
  - Cog > UI > Compact Journal Entries 
  - Cog > UI > Compact Rollable Tables 
  - Cog > UI > Name Browser Tab After Active Scene
  - Cog > UI > Display Detected Backend
  - Cog > UI > Fast Animations
  - Cog > UI > Fix Esc Key
- [Token Bar](https://github.com/Kekilla0/TokenBar) - It populates an action bar for the token you have selected.
- [Tidy 5e Sheet](https://github.com/sdenec/tidy5e-sheet) - D&D 5e Only. An alternative Character Sheet
- [Darker Vision for 5e](https://foundryvtt.com/packages/darker-vision-for-5e/) - Adjust's Foundry's handling of Darker Vision to match D&D 5e's rules as written. - Suggested by LorduFreeman on The Foundry Discord
- [Torch](https://foundryvtt.com/packages/torch/) - Adds a HUD button to toggle light of a specific radius.
  - Configure Settings > Module Settings > GM Uses Inventory
  
## Pathfinder 2e (P2E) Specific
- [Pathfinder 2e Quick Rolls](https://gitlab.com/mcarthur.alford/pf2qr) - Adds features to speed up rolling in chat.
- [Pathfinder Ui](https://gitlab.com/sasmira/pathfinder-ui) - Theme for Pathfinder 1e and 2e.
- [PF2e GM Screen](https://gitlab.com/atakanaltiner6/pf2e-gm-screen/) - A GM Screen for PF2e Game System.
- [Virtual Tabletop Assets - Iconizer](https://www.vttassets.com/assets/vtta-iconizer) - Whenever an item is created or updated, Iconizer looks up its name in its dictionaries. If it finds an entry, it will use the icon references there to update the image of that item.
  - Could be helpful for Pathfinder 2e, but not needed for D&D 5e as Plutonium already imagery for nearly every entry in its database.

## Modules Pending their First Review
- None at the moment!

## Modules Scheduled for Re-Review at a Later Date
- [Compendium Browser](https://foundryvtt.com/packages/compendium-browser/) - Easily browse and filter spells as well as NPCs loaded from the compendium. - Review 2020 Sep 06 - Seems incredibly useful but there is currently an issue with Shared compendiums that can crash a game (https://github.com/syl3r86/compendium-browser/issues/13). Will revisit once it's had time to stew some more.
- [FXMaster](https://gitlab.com/mesfoliesludiques/foundryvtt-fxmaster) - Adds various special effects. - Review 2020 Sep 06 - Seems like an incredible module, but there are 20+ outstanding issues on the repository. Too risky an interuption to regular gameplay in its current state.
- [Grid Scaler](https://github.com/UberV/scaleGrid) - Adds tool to help to set the Foundry grid on the background image - Review 2020 Sep 06 - Seems super helpful, but a number of issues exist. Defintely going to revist.
- [Loot Sheet NPC 5E](https://github.com/jopeek/fvtt-loot-sheet-npc-5e) - Adds an additional NPC sheet which can be used for loot containers such as chests. - Review 2020 Sep 06 - This looks incredible but a number of outstanding issues has me putting this aside to revisit at a later date.
- [Forien's Unidentified Items](https://github.com/Forien/foundryvtt-forien-unidentified-items) - Handle unidentified items and their identification. - Review 2020 Sep 06 - Love everything about this but don't have a need for it. Going to place this for re-review at a later time.
- [Cozy Player](https://foundryvtt.com/packages/cozy-player/) - Token toolstips and Quality of Life enhancements - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - Tons of usefull enhancements but a bit overkill. Some of the tooltip options that it can show seem unique to this module and I haven't seeen them elsewhere. There is an open issue to split the module so it's more granular, hopefully that happens.
- [Group Initiative](https://foundryvtt.com/packages/group-initiative/) - Suggested by LorduFreeman on The Foundry Discord - Review 2020 Sep 06 - Great idea but seems to be broken (https://github.com/tonifisler/foundry-group-initiative/issues/4).
- [Sheet To Token](https://foundryvtt.com/packages/sheet-to-token/) - Automatically updates an actor's Prototype Token to match its actor image when updated. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Fantastic idea, but haven't actually needed it in practice so far.
- [Permission Viewer](https://foundryvtt.com/packages/permission_viewer/) - Quickly see which entities (Journal entries, Actors, etc..) are visible to all players or visible to a specific player. - Suggested by KaKaRoTo on The Forge Discord and jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Love it, but the UI is so obtuse, I can't remember what each shape means and so it's not actually helpful.
- [Drag Upload](https://foundryvtt.com/packages/dragupload/) - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - In concept I like it, but has the potential for too many mistakes.
- [Forien's Quest Log](https://foundryvtt.com/packages/forien-quest-log/) Provides comprehensive Quest Log system for players and Game Masters - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Looks awesome for a big epic game, but seems like overkill for the ones I'm running. Will revisit at a later date.
- [Foundry VTT Macros Repository](https://github.com/foundry-vtt-community/macros) - Foundry community-contributed macros. - Review 2020 Sep 06 - Was looking into this to help out with thing like "Barbarian Rage" but I'd rather just wait at the moment and see if these start to sneak their way in without the need for Macro's.
- [Popout Resizer](https://github.com/Cardagon/popout-resizer) - Give the users the ability to resize their pop-out windows from the side toolbar. - Retired 2020 Sep 06 - Haven't needed this, but might as things continue to get more complicated. Setting this for Re-Review.
- [Chat Images](https://github.com/bmarian/chat-images) - Copy and Paste, Drag and Drop images into chat. - Retired 2020 Sep 06 - See issue linked below
  - This Module inserts images as base64 encoded data which can grow the chat log to the point it can start to impact gameplay (https://github.com/bmarian/chat-images/issues/7). This could cause large base64 encoded images to be inserted (e.g. 24mb) every time a chat message is posted. Whereas normal images will be resized, compressed, and cached by the browser. - Flagged by an Anonymous user on The Forge Discord
- [Virtual Tabletop Assets - Party Overview](https://www.vttassets.com/assets/vtta-party) - Adds a party overview window, granting you information about some vital stats quickly and without hassle. - Retired 2020 Sep 06 - I don't like to know everything about the part, but I'm willing to revisit at a later date.
  - Grant Players access to the overview?: Off
  - Enable tooltips?: Off - Similar information is already provided by Token Info Icons

## Modules Reviewed or Retired, and not in active use
These modules are no longer used as they’ve become redundant to features provided by other modules, they caused other issues (e.g. lag), or there was nothing wrong with them but I just didn't find their use out weighed creating a more complex buildout.
- [Turn Alert](https://github.com/schultzcole/FVTT-Turn-Alert) - Set alerts to trigger on a particular round of combat or on a particular token's turn. - Retired 2020 Aug 09 - Turn altering is handled by Combat Ready
- [Turn Marker](https://github.com/Brunhine/TurnMarker) - Adds an image under a token who is currently active in the combat tracker. - Retired 2020 Aug 09 - Turn marking is handled by Combat Ready
- [Token Mold](https://github.com/Moerill/token-mold) - For minting tokens that auto append a counter or descriptor to the tokens name. Also can handle automatic token scaling. - Retired 2020 Aug 09 - Great concept but limited utility at the moment. Retiring to reduce UI clutter, will revisit in the future.
- [Easy Target](https://bitbucket.org/Fyorl/easy-target/) - Toggles the targeting tool while holding option key (alt on Windows). Also allows for option+clicking inside an AoE to target all tokens within that AoE. Holding the option key while placing a template will also target all tokens within that template when placed. - Retired 2020 Sep 06 - Nothing wrong with this, but I found myself just manually selecting the targets after the AOE was placed.
- [Health Estimate](https://gitlab.com/tsuki.no.mai/healthestimate) - Shows estimated health level of an enemy on mouseover. - Retired 2020 Sep 06 - Nothing wrong this, just felt like overkill given all the other info that can be so quickly gleemed.
  - GM Only: On
- [Follow Me](https://github.com/Brunhine/FollowMe) - Allows tokens to follow other tokens. - Retired 2020 Sep 06 - Nothing wrong with this, just felt like overkill.
- [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator) - Adds a Dice Tray below the chat. - Retired 2020 Sep 06 - Nothing wrong with this, just felt like overkill. Everything has an option to autoroll, or a user can type "/roll 1d20+2" if they need to. Wasn't saving any time.
- [Tidy UI - Game Settings](https://github.com/sdenec/tidy-ui_game-settings) - A module to make the game settings menu a bit more comfortable to use. - Retired 2020 Sep 06 - Nothing wrong with this, just felt unnecisary since I'm not messing around the the game settings that often after the instance has been set up. Still nice to have during your first build out but unnecessary.
- [Compendium Image Mapper](https://gitlab.com/Wilco7302/compendium-image-mapper) - select a folder containing images, and then automatically search for compendium entries that best match your images. - Review 2020 Sep 06 - Fantastic module if you have a huge library of well named images you want mapped to compendium entried. I do not.
- [Better Rolls for 5e](https://foundryvtt.com/packages/betterrolls5e/) - Overhauls most rolls on the 5th edition character sheet, and provides a way to customize roll messages per-item. - Review 2020 Sep 06 - This is a well thought out module but much of what it can do is more quickly done with "Token Bar". If you often have compound rolls (e.g. higher levels with multiple attacks) then you might want to consider this. I personally don't mind just clicking the attack roll multiple times.
- [Community Tables](https://foundryvtt.com/packages/foundry_community_tables/) - A collection of Tables added by the FoundryVTT Community. - Review 2020 Sep 06 - Cool idea, but not enough content to warrant installing it.
- [Encounter Builder for 5e](https://foundryvtt.com/packages/encounter-builder-5e/) - D&D 5e Only. Aid in building D&D5E combat encounters. - Review 2020 Sep 06 - Great idea and well executed, but I don't have the need. If you you need help balancing an enounter, give this a try.
- [Mess - Moerills enhancing super-suit(e)](https://github.com/Moerill/mess) - Many features, possible compatibility issues. - Review 2020 Sep 06 - So much work clearly went into this module, but it's stated not caring about creating potential conflicts is too big a risk to have this be a daily driver. Nice work though.
- [Expander](https://github.com/Sky-Captain-13/foundry/tree/master/expander) - Expands the chat window when you click on the chat icon instead of only by clicking on the arrow at the bottom. - Review 2020 Sep 06 - I love everything about this, but I'm not going install a whole module just for this small change. Hopefully it makes its way into FoundryVTT core one day.
- [DNDBeyond Character Sheet](https://foundryvtt.com/packages/dndbeyond-character-sheet/) - Replacement of a character sheet with a version more similar in style to that of D&D Beyond's. - Review 2020 Sep 06 - Great work, but superseded by Tidy 5e Sheet. The module also has outstanding issues with its responsiveness and content being cut off. 
- [Token Health](https://github.com/tonifisler/foundry-token-health) - Apply damage/healing to all selected tokens. - Review 2020 Sep 06 - Great idea but overkill and one more keyboard shortcut I would need to remember.
- [Foundry VTT Modules for DnD 5E](https://github.com/foundry-vtt-community/modules/tree/master/Foundry%20VTT%20Modules%20for%20DnD%205E) - Marked for review, seems outdated. - Review 2020 Sep 06 - This was a list of modules with many of them that seem to be in FoundryVTT core now and other just outdated for problems that no longer exist.
- [Better NPC Sheet 5e](https://github.com/syl3r86/BetterNPCSheet5e) - Review 2020 Sep 06 - Nice for what it does but superseded by Tidy 5e Sheet
- [D&D 5e Conditions](https://github.com/trdischat/conditions5e) - Review 2020 Sep 06 - Great idea, but not needed with everything else we have running.
- [D&D5E Dark Mode](https://github.com/Stryxin/dnd5edark-foundryvtt) - Review 2020 Sep 06 - Cool! I just have no need for dark mode.
- [Layer Hotkeys](https://github.com/Moerill/Layer-Hotkeys) - Review 2020 Sep 06 - The last thing I want is more hotkeys, nice if you do though.
- [VTT Modbox](https://gitlab.com/mesfoliesludiques/foundryvtt-modbox) - Creates an input field to add a modifier to the next roll - Review 2020 Sep 06 - I see the value, I just don't need it.
- [Kobold Press OGL](http://kpogl.wikidot.com/) - All the 5e OGL Content Kobold Press has released - Review 2020 Sep 06 - This is awesome if you want Kobold Press content. Some of their content is already in Plutonium, but I don't think all of it.
- [MiniMap](https://gitlab.com/jesusafier/minimap) - Shows a minimap - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - This is such a cool idea but it's so easy to quickly Zoom out that it's not actually that helpful in practice.
- [WhisperBox](https://github.com/Sk1mble/WhisperBox) - Create a dedicated box for whispering to a specific player - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - This is an excellent idea, but some UX leaves me wanting. Hopefully something similar gets built out in FoundryVTT core.
- [Batch Permission Change By Folder](https://foundryvtt.com/packages/BatchPermissionsByFolder/) - Adds a context option to folders in Items, Journals, and Roll to change the permission of each entity(Foundry's codeword for Item, Journal Entry, or Roll Table) inside the folder. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Not a bad idea, but haven't had the need for it.
- [ConditionIconHoverZoom](https://github.com/Sparkasaurusmex/ConditionIconHoverZoom) - Makes condition icons more legible by increasing their size. Also enlarges and makes them opaque on hover. - Review 2020 Sep 06 - I thought I wanted this when I first saw it, but I don't really need it.
- [Escape Window](https://foundryvtt.com/packages/escape-window/) - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - Not neccisary. I can double click on the title bar of a sheet / pop-up to minimize it.
- [The Furnace](https://foundryvtt.com/packages/furnace/) - Many features to improve the Quality of Life of the DM/Players. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Lot's of rich features, but nothing not already being provided elsewhere.
  - Advanced Macros: Off
  - Advanced Drawing Tools: Off
  - Improve the Playlists UI: Off
- [PopOut!](https://github.com/kakaroto/fvtt-module-popout) - Lets you pop out actor sheets and journal entries into their own windows. - Retired 2020 Sep 06 - Nothing wrong with this but it wasn't actually needed in the end.
- [Vance's Sidebar Resizer](https://github.com/VanceCole/vance-sidebar-resizer) - Allows the sidebar to be resized. - Retired 2020 Sep 06 - Nothing wrong with this, just ended up never needing it.

## Free Map-Pack Resources
Not tested, shared for ease of reference.
- [Forgotten Adventures](https://www.forgotten-adventures.net/live-gallery/)
- [Fantastic Maps](http://www.fantasticmaps.com/free-stuff/)

## Free Tokens Resources
Not tested, shared for ease of reference.
- [Forgotten Adventures](https://www.forgotten-adventures.net/live-gallery/)
- [Devin Nights Token Packs 1-20](https://immortalnights.com/tokensite/?product=all-free-tokens-in-one-file)

## Free Sound and Music Resources
Not tested, shared for ease of reference.
- [Gameaudio GDC Bundle](https://foundry-vtt-community.github.io/wiki/Community-Media/#gameaudiogdc-bundle)

## Free Icon Resources
Not tested, shared for ease of reference.
- [Game-icons.net](https://foundry-vtt-community.github.io/wiki/Community-Media/#game-iconsnet)
- [Bundle WOW-Icons](https://foundry-vtt-community.github.io/wiki/Community-Media/#bundle-wow-icons)

## Content Creators
Not endorsed, shared for ease of reference.
- [2-Minute Tabletop - Patreon](https://www.patreon.com/2minutetabletop) - 2-Minute Tabletop is creating Hand-Drawn Maps & Assets for D&D
- [Afternoonmaps - Patreon](https://www.patreon.com/afternoonmaps/posts) - Afternoon Maps is creating RPG and DnD battlemaps
- [Caeora - Patreon](https://www.patreon.com/caeora) - “Caeora is creating Tabletop Maps & Tokens
- [Cze and Peku - Patreon](https://www.patreon.com/czepeku/posts) - “Cze and Peku are creating maps for DnD, Pathfinder and other RPGs
- [Dungeon Mapster - Patreon](https://www.patreon.com/dungeonmapster/posts) - Dungeon Mapster is creating maps for pathfinder, tabletop games, and dungeons and dragons”, Dungeon Mapster, Patreon
- [Eightfold - Patreon](https://www.patreon.com/EightfoldPaper/posts) - Eightfold Paper is creating Battlemaps and Item Cards for Tabletop RPGs
- [Forgotten Adventures - Patreon](https://www.patreon.com/forgottenadventures) - Forgotten Adventures are creating Digital Assets and resources for Tabletop RPGs.
- [Gabriel Pickard - Roll20](https://marketplace.roll20.net/browse/publisher/64/gabriel-pickard) - Gabriel Pickard is a long time rpg lover residing in the Seattle Washington, he’s traded chef’s knives for digital art and apparently talking in the third person
- [Heroic Maps - Patreon](https://www.patreon.com/heroicmaps/posts) - Heroic Maps are creating battlemaps for tabletop RPGs
- [Jesper Nilsson Cyren - Patreon](https://www.patreon.com/CyrensMaps/posts) - Jesper Nilsson Cyren is creating RPG maps
- [Maphammer - Patreon](https://www.patreon.com/maphammer/posts) - Maphammer is creating battle maps for D&D, Pathfinder and other tabletop games
- [Neutral Party - Patreon](https://www.patreon.com/neutralparty/posts) - Neutral Party is creating RPG Maps
- [PogS Props - Patreon](https://www.patreon.com/PogS_Props) - PogS Props is creating Battlemaps, maps, tokens, stuff for RPGs
- [The Drafting Table - Patreon](https://www.patreon.com/draftingtable) - The Drafting Table is creating Map assets, battlemaps, RPG Maps, and more!
- [Animated Dungeon Maps - Patreon](https://www.patreon.com/animatedmaps/posts) - Animated Dungeon Maps is creating animated maps for D&D and other tabletop games
- [Dynamic Dungeons - Patreon](https://www.patreon.com/dynamicdungeons/overview) - Dynamic Dungeons is creating animated maps for tabletop RPG and miniature games
- [Living Realms - Patreon](https://www.patreon.com/LivingRealms/posts) - Living Realms is creating Animated Maps for Tabletop RPG Games
- [Adventure Music - Patreon](https://www.patreon.com/adventuremusicjr) - Adventure Music is creating Instrumental Music for Dnd, Pathfinder and other RPG’s
- [Michael Ghelfi - Patreon](https://www.patreon.com/MichaelGhelfi) - RPG ambiences library
- [Music d20 - Patreon](https://www.patreon.com/musicd20) - Music and sound effects for games
- [Sword Coast Soundscapes - Patreon](https://www.patreon.com/swordcoastsoundscapes) - Sword Coast Soundscapes is creating Ambient Soundscapes
- [Vindsvept - Patreon](https://www.patreon.com/Vindsvept) - Vindsvept is creating Fantasy Music

## Miscellaneous Resources
- [Module usage statistics from The Forge - July 2020](https://i.imgur.com/xRVVed1.png)
- [Official FoundryVTT Sub-Reddit Module Wiki](https://www.reddit.com/r/FoundryVTT/wiki/index/modules)
- [Foundry VTT Community](https://foundry-vtt-community.github.io/)
- [Intro to Dynamic (Character Stat) Effects](https://www.reddit.com/r/FoundryVTT/comments/ibfphc/a_very_simple_intro_to_dynamic_effects/)
- [All D&D 5e Monster Tokens](https://www.reddit.com/r/dndnext/comments/ij8ljk/i_made_monster_tokens_for_every_monster_in_the/)
