# CS2 Team Deathmatch Server Setup

This is a **undocumented but working as intended** CS2 (Counter-Strike 2) team deathmatch dedicated server made for **public use**. It uses my version of a branch from CS2Fixes, a plugin that fixes some of the common issues and bugs found in the original game. You can find the source code of the version i used in this project in [my other repository](https://github.com/LifeDreamer24/CS2Fixes). I made this because i found nothing else similar to this for beginners.

## Features

- Instant respawns for both teams: Terrorists and Counter-Terrorists.
- Vote from one of the **10 official maps** at the end of each round except the one played in the current round.
- Automatically balances the teams based on the number of players.
- Many admin commands included with the plugin.
- Lua scripts supported: Empty directory tree for them and reloading script are both included in this project.
- Possibility to purchase anywhere in the map, without limitations (except for grenades and the taser).
- Hides the radar and the currency amount from the HUD as they are not needed.
- Automatic bunny-hopping enabled.

## Instructions

To start the server correctly, you need to follow these steps:

1. **Step 1:** Download the [latest release](https://github.com/LifeDreamer24/cs2-ds/releases/latest).
2. **Step 1A:** Unzip the archive in order to see it's uncompressed content.
3. **Step 2:** Drag and drop both the `game` folder and the `launch.bat` batch file in your game installation's root folder.
4. **Step 2A:** Make sure you overwrite everything! If you don't get the prompt to overwite or skip, you did something wrong.
5. **Step 2B:** If you do not have a game installation, download it using SteamCMD with [this guide](https://developer.valvesoftware.com/wiki/Counter-Strike_2/Dedicated_Servers).
6. **Step 3:** Replace `<gslt_token>` in the `launch.bat` batch file with your own GSLT token which can be taken from [here](https://steamcommunity.com/dev/managegameservers).
7. **Step 3A:** Modify both the RCON password and TV Password values in the `serverconfig_ld24.cfg` configuration file in the `cfg` folder.
8. **Step 3B:** Add yourself as an administrator on the server by modifying the `admins.cfg` configuration file in the `configs` folder.
9. **Step 4:** Launch your server using the `launch.bat` batch file.

## Credits & Special Thanks

- Credits to [Valve](https://github.com/ValveSoftware) for creating this masterpiece of a game.
- Credits to the awesome team who worked behind the original CS2Fixes aswell as their Zombie Extraction servers. They have a very impressive knowledge over the Source 2 game engine.
- I would like to thank [mihaigsm2003](https://github.com/mihaigsm2003) for helping me with some issues while using his branch of CS2Fixes.
- A massive thank you and shoutout to my friend [@rcon_password](https://github.com/rcon420) for helping me alot in various issues troughout this amazing journey of making CS2 content. They've been supporting me alot for quite a while already and making this would've not been possible without them. ([Their Discord](https://discord.gg/chill-lv-cs-go-cs2-538820484913954847))

## Feedback

If you have any feedback, suggestions, or bug reports, please feel free to contact me at **simon.lemay@bell.net**. I appreciate your support and interest in this project. Thank you! 🙏
