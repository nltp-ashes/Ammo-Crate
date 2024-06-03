# AMMO CRATE [![License](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

Adds a new "Ammunition crate" item to store your ammo and keep your inventory clean.

---

### ABOUT

Based on the idea of DerChrom's Ammo Box, this addon adds a new item to the game : an ammunition crate. This item allows you to store your ammunition inside it, thus cleaning your inventory.
The original addon had a ton of issues, some of which were not that easy to fix. This new addon was remade from the ground up, and should be as bug free as it gets.
A note to other modders : when ammunition is put in the crate, the ID isn't kept (because the item is released and re-created later). Be careful if this is relevant for your scripts.

---

### REQUIREMENTS
This addon requires the following :
1. [S.T.A.L.K.E.R. Anomaly 1.5.2](https://www.moddb.com/mods/stalker-anomaly/downloads/stalker-anomaly-151-to-152)

---

### INSTALLATION

To install the addon :
- Download this addon;
- Merge the contents of the `gamedata` folder with your game's folder of the same name :
  - with a mod manager (highly recommended);
  - or manually (highly unrecommended).

To uninstall the addon :
- Start your game and open the MCM settings;
- Enable the "Addon removal" option;
- Load your save-game. Once loaded, save again;
- Close your game, and remove the files added by the addon.

---

### CHANGELOG

> v1.2.0 - 04/03/2023 - Major Update
> - Added full Mags Redux compatibility. You can now put magazines in the ammo crate;
> - Updated addon removal so that it will give you back the magazines contained in the various crates.

> v1.1.2 - 14/02/2023 - Hotfix
> - Fixed an issue due to which the weight of the crate was incorrect after loading a save game;
> - Updated addon removal so that it will give you back the ammo contained in the various crates.

> v1.1.1 - 11/02/2023 - Hotfix
> - Added a CTD when trader_autoinject.script is outdated;
> - Added a separate icon for the crate, to avoid conflicts with icon addons (Thanks 191830221zhang);
> - Fixed a CTD that sometimes occurred after closing the ammo crate (Thanks Matumba_4).

> v1.1.0 - 02/02/2023 - Minor Update
> - Added the item for sale to mechanics;
> - Army soldiers can now spawn the item when killed.

> v1.0.0 - 01/02/2023 - Initial Release
> - Adds a new item to the game : an ammunition crate;
> - You can (only) store ammunition inside it;
> - The crate does not have a carrying capacity. The limit is your own carrying capacity;
> - Ammunition inside the crate cannot be reloaded. You first have to pull it out of it.

---

### KNOWN ISSUES

- A pack of old meat might appear for a split second when using FDDA. This will probably never get fixed, as the "issue" lies on FDDA's side.

---

### SUPPORT & SUGGESTIONS

If you need help with anything, or if you have any suggestions, you can :
- ✅ Message me on [ModDB](https://www.moddb.com/members/nltp-ashes) (recommended);
- ✅ Message me on Discord : @nltp_ashes (formerly NLTP_ASHES#0117) (recommended);
- ✅ Message me on my [Discord](https://discord.gg/7Z8S2qg) server (recommended);
- ⚠️ Leave a comment on [ModDB](https://www.moddb.com/mods/stalker-anomaly/addons/ammo-crate/) (not recommended);

---

### SPECIAL THANKS & CREDITS

Credits goes to these people for their work contained in this addon :
- [DerChrom](https://www.moddb.com/members/na4448334) - For the original idea;
- [HarukaSai](https://www.moddb.com/members/funkypunk) - For letting me reuse his script functions.

Special thanks to these people for their help in the making of this addon :
- [RavenAscendant](https://www.moddb.com/members/ravenascendant) and [xcvb](https://www.moddb.com/members/bvcx) - For implementation ideas and tips;
- [RavenAscendant](https://www.moddb.com/members/ravenascendant) - For providing help with mitigating a crash;
- [RavenAscendant](https://www.moddb.com/members/ravenascendant) - For providing help implementing Mags Redux support.

---

### LICENSE

Everything contained in Western Goods and made by me, NLTP_ASHES, is licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This means you're allowed to redistribute and/or adapt the work, as long as you respect the following criteria :
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes (this includes donations).
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

For the work that wasn't made by me, unless a licence is specified in the [Credits](#special-thanks--credits) or in the files themselves, consider these works proprietary. If you want to reuse those, please get in touch with their original authors.
