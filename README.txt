Adds a new "Ammunition crate" item to store your ammo and keep your inventory clean.

[ ABOUT ]
Based on the idea of DerChrom's Ammo Box, this addon adds a new item to the game : an ammunition crate. This item allows you to store your ammunition inside it, thus cleaning your inventory.
The original addon had a ton of issues, some of which were not that easy to fix. This new addon was remade from the ground up, and should be as bug free as it gets.
A note to other modders : when ammunition is put in the crate, the ID isn't kept (because the item is released and re-created later). Be careful if this is relevant for your scripts.


[ REQUIREMENTS ]
This addon requires the following :
1. S.T.A.L.K.E.R. Anomaly 1.5.2 : https://www.moddb.com/mods/stalker-anomaly/downloads/stalker-anomaly-151-to-152


[ INSTALLATION ]
To install the addon :
1. Download this addon;
2. Merge the contents of the gamedata folder with your game's folder of the same name;
2.bis. Do that either with a mod manager (highly recommended) or manually (highly unrecommended).

To uninstall the addon :
1. Locate the folder ~\gamedata\scripts\;
2. Open the file ammo_crate_removal.script (with notepad);
3. Replace the line 12 with the following : local CONST_ADDON_REMOVAL = true
4. Start your game, load your save game;
5. Once the game finishes loading, save your game;
6. Close your game, and remove the files added by the addon;
7. You can now load your newly created save without the addon.


[ CHANGELOG ]
v1.2.0 - 04/03/2023 - Major Update
• Added full Mags Redux compatibility. You can now put magazines in the ammo crate;
• Updated addon removal so that it will give you back the magazines contained in the various crates.

v1.1.2 - 14/02/2023 - Hotfix
• Fixed an issue due to which the weight of the crate was incorrect after loading a save game;
• Updated addon removal so that it will give you back the ammo contained in the various crates.

v1.1.1 - 11/02/2023 - Hotfix
• Added a CTD when trader_autoinject.script is outdated;
• Added a separate icon for the crate, to avoid conflicts with icon addons (Thanks 191830221zhang);
• Fixed a CTD that sometimes occurred after closing the ammo crate (Thanks Matumba_4).

v1.1.0 - 02/02/2023 - Minor Update
• Added the item for sale to mechanics;
• Army soldiers can now spawn the item when killed.

v1.0.0 - 01/02/2023 - Initial Release
• Adds a new item to the game : an ammunition crate;
• You can (only) store ammunition inside it;
• The crate does not have a carrying capacity. The limit is your own carrying capacity;
• Ammunition inside the crate cannot be reloaded. You first have to pull it out of it.

[ KNOWN ISSUES ]
• A pack of old meat might appear for a split second when using FDDA. This will probably never get fixed, as the "issue" lies on FDDA's side.


[ SUPPORT & SUGGESTIONS ]
If you need help with anything, or if you have any suggestions, you can :
• Leave a comment on moddb (not recommended);
• Message me on moddb (recommended);
• Message me on Discord : NLTP_ASHES#0117 (recommended);
• Ask me on my Discord : https://discord.gg/7Z8S2qg.


[ SPECIAL THANKS & CREDITS ]
Credits goes to these people for their work contained in this addon :
• DerChrom - For the original idea;
• HarukaSai - For letting me reuse his script functions.

Special thanks to these people for their help in the making of this addon :
• RavenAscendant and xcvb - For implementation ideas and tips;
• RavenAscendant - For providing help with mitigating a crash;
• RavenAscendant - For providing help implementing Mags Redux support.
