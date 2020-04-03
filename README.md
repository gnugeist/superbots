# superbots
Dota 2 Superbots - Config Scripts to enhance the bot experience with GPM and levels.

This collection of scripts run on a localhost lobby improving item progression for the various dota 2 bot scripts.

## Installation
1. Clone/Download the repository
2. locate your SteamLibrary Directory and place all the files in the ```SteamLibrary\steamapps\common\dota 2 beta\game\dota\cfg``` subdirectory.

*(If you have console enabled in dota2, skip the rest of the section)*

3. In the Steam Library gamelist, right click on ```Dota 2``` and click ```properties```
4. Click the ```SET LAUNCH OPTIONS...``` button and add ```-console``` onto the list of launch options & click ```OK```.
5. Close the properties window and Launch ```Dota 2```
6. Open console and type ```exec start``` which will initialize the script for having bots on the dire team.

## First Run
1. Launch Dota 2 and assemble friends.
2. Create a custom lobby and pile on one team.
3. Under Settings, set Server to LocalHost, enable cheats, bots and pick a good script. (Suggested Bot Experiment script)
4. The moment you load as the server, hit ```kp_divide```(Keypad /) if the bots are on Radiant team, or hit ```kp_multiply``` (Keypad *) if the bots are on Dire team.
5. Start the game and once the game beings (-1:30 on the clock), hit ```kp_multiply```(Keypad *) to start the script
6. At 25:00 minutes into the game, the script will prompt you if you want to give the bots a neutral item to change the balance of the game without tipping the networth balance. Answer ```kp_divide```(Keypad /) for NO or ```kp_multiply```(Keypad *) for YES.

### Snippet from the in-console instructions when using ```exec start```
The majority of the script uses the keypad bindings to interact with the script.
KP_Divide [/] will be for selecting Radiant Bots and responding NO.
KP_Multiply [*] will be for selecting Dire Bots and responding YES.

1. Create a lobby, set your settings and start the game... on the pickscreen press / or * to prime the script.
2. After Hero introductions and the game actually starts ( -1 : 30 ) press the * button to start the scripts.
( Pressing /No will toggle between radiant and dire )
3. Enjoy the game, at 25 minutes the script will ask you more questions regarding neutral items.

 Keypad 9 - Alternative flat 100gpm script
 
 Keypad 8 - Spawn a Warlock Golem
 
 Keypad 7 - Spawn a Ancient Prowler ( micro to mess with friends )
 
 Keypad 6 - Give bots 600 rocketflare vision. lasts 1 sec.
 
 Keypad 5 - Spawn an invis Lycan Wolf ( no expire )
 
 Keypad 4 - Spawn Eye of the Forest. flying vision, but hp bar is visible.
 
 Keypad 3 - Give bots 1000g
 
 Keypad 2 - Give bots 500g
 
 Keypad 1 - Give bots 300g
 
 Keypad 0 - Give bots 1 Level
 
 Keypad Delete - Give bots a teleport scroll
