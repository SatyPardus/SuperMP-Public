# SuperMP-Public

A public test for my Supermarket Simulator Multiplayer Mod.
Use the Issues tab to report any problems you found with the mod!

My discord for questions and feedback: https://discord.gg/rtYbKZrpeY
If you want to support me financially and get your name into the mods donator page, check out my itch:
https://satypardus.itch.io/supermarket-simulator-multiplayer-mod

# Known Issues
- Restockers are not fully synced and invisible on clients. The boxes they carry just float magically around.
- Sounds are not properly synced, playing sounds sometimes when they shouldn't, and not when they should.
- Bank loans are not synced and can be abused for infinite money.
- Players can be pushed through walls when boxes are thrown at them.
- When cashiers scan items, the computer doesn't show the products properly.
- The mod uses a "mod checker", so host and client need the same mods. It will not show a proper error when a client connects and just fails to connect you.
- Auto paid bills are not synced correctly, maybe.
- There are no proper animations for the players.

# How to install
- Download https://www.nexusmods.com/supermarketsimulator/mods/9 and install it. Install instructions for the mod loader are on the Nexus page.
- Download my Release.zip
- Unpack the SupermarketMultiplayer.dll into your game folder->BepinEx->plugins
- Enjoy :p

If everything worked, you should see a version number at the top left of the game.
You can start and join a Multiplayer Game over the Computer in your store.

# Will this corrupt my game file?
It should not. For people who connect, the Save file system is completely disabled.
For the host, the save file is modified as if he would play alone.
In theory this should not cause any corruption, if it does, I apologize! Let me know if anything unexpected happens.

# Disclaimer
The mod uses a custom Telemetry system which **can not be turned off yet**.
I will add a opt-out before I completely release this mod.

This statistic collects: SteamID, Steam Display Name, When you started a network session, when you closed a network session and the current version of the mod.
