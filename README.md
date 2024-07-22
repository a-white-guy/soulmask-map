# soulmask-map

This is a map for the game soulmask which will be populated with locations for npcs and key locations within the game.

The map image was taken from the wiki site https://soulmask.fandom.com/.  The npc pictures were screenshots I made from the in game hunting gallery.  The various other icons were taken from the wiki page or screenshots from in game.

All npc locations should be 100% accurate to where they actually spawn at.  The method to obtain the precise spawn locations is reproducable.  These are the steps I used.  Spawn into a multiplayer world, enable admin for yourself, in the player console type debuginfo 1, from outside the game run the rcon command stopai, from your player console run the command gm clear_all_npcs, afk about 10-15 minutes, from outside the game run the rcon command dap, from outside the game navigate to your server's saved folder and located the .log file, open up the file and parse out duplicate entries and sort the file, match your npc class names with in game npc names, you now have all locations.

This method does not take in to account for npcs who spawn in and wander around while activly rendered or move for other reasons like patrols etc.  So this map is strictly accurate to where the npc spawns at.







This map uses a modified version of the craftopia interactive map setup by kregap at https://github.com/Kregap/craftopia-map.  With his assistance I was able to set this map up.
