# SkinsRich - Wear skins in offline worlds. 

<img src="https://github.com/Shiwaru/SkinsRich/blob/main/avatarHead.png" width="150" height="150"></img>

[![GitHub Releases](https://img.shields.io/badge/latest-downloads-8A2BE2?style=for-the-badge)](https://github.com/Shiwaru/SkinsRich/releases)
[![GitHub Releases](https://img.shields.io/badge/CurseForge%20Downloads-F08437?style=for-the-badge)](https://www.curseforge.com/minecraft/mc-mods/skinsrich)
[![GitHub Releases](https://img.shields.io/badge/neoforge-releases-a94e0d?style=for-the-badge)](https://neoforged.net/)

Minecraft Java plugin for NeoForge.
 
NeoForge is a direct dependency.
For 1.21.11 - NeoForge 21.11.37-beta at least, is needed.
For 1.21.10 - NeoForge last version is required.

Current version is v0.2 in both 1.21.10 and 1.21.11

Known issues are right now:
- Others cannot see your skin in LAN worlds (Which is my priority right now)
- Skins with weird ascii chars doesn't fetch properly
- OptiFine capes tend to break

Planned features:
- LAN/Server fix overall
- Elytra support
- HD Skins support
- "/skin" info section
- Multiple languages
- Fix different language messages in Spanish/English cause it's messy but I'm lazy enough to fix it all bruh
- Cache skins
- Load latest skin used (Cache skins required)
- Change /skinsrich info

Commands:
/skin - Base command

/skin set <nickname> - Skin change command

This command requests a skin through a valid Minecraft account username.
Checks on Mojang servers and returns a skin.
 

/skin refresh - Skin refresh command

Tries to refresh in case skin does not automatically refresh for any reason.
 

/skinsrich - Credits/Info command 

Info is not available at the moment. (And will be moved to "/skin" command)
