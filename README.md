# Lua-DataStores
Simple code to import DataStores in your game, this will also set up a leaderboard in the act.

(If you're using Lua-Roblox please insert this code into a regular Script inside of Game/ServerScripts.

You may have to enable various setting within the game to do with online / multiplayer connections, depending on what software yout using (Epic Games, Roblox etc) and
there may be a direct way to turn on/off datastores

This will automatically create a leaderstat folder as well as 2 Interger Values ('Cash' and 'Wins') however these can be changed to support your desire.

You may need to add 'wait()' before the inital connecting of the player's client as depending on how fast they connect could mean the code runs too fast for the player
connecting so it can't find the correct places for the files either braking the code or most unlikey misplacing the folders howver I doubt the second result may happen,
a wait time of around 5-30 seconds is best as it could take too long for a player who loaded ralatively fast.
