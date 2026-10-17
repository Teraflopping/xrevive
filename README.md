# xrevive

### **English** · [**Deutsch**](translations/README.de.md) · [**Français**](translations/README.fr.md) · [**Español**](translations/README.es.md) · [**Italiano**](translations/README.it.md) · [**Português (Brasil)**](translations/README.pt-BR.md) · [**Русский**](translations/README.ru.md) · [**العربية**](translations/README.ar.md) · [**日本語**](translations/README.ja.md) · [**简体中文**](translations/README.zh-CN.md)

A desktop launcher for original Xbox games recompiled with [Xrecomp](https://github.com/Teraflopping/Xrecomp), with online services from the Xbox Live revival at [xb.live](https://xb.live).

## Download v0.1.14

[Download for Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Download for Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [All installers and release notes](https://github.com/Teraflopping/xrevive/releases/latest)

The hosted game executables currently support **Windows x64**. On Linux they can run through Wine or Proton (experimental). macOS packages can't play games yet.

## Features

- Add your own ISO or extracted game folder, then download its matching executable. xrevive uses a game's Release build when there is one, and asks first before installing a Beta or Alpha build. Region-free, media-patched, renamed or re-signed dumps of a supported game are recognized too.
- Browse any Release, Beta or Alpha game before installing it: activity, updates, leaderboards, achievements, addons and the live player and lobby count, with **INSTALL** right on its page.
- Automatic game and launcher update checks. Game updates remove the old executables they replace, and game downloads come from a server near you and resume if the connection drops.
- Sign in with xb.live (starting with Midnight Club 3 online), and view friends, live lobbies, community events, and leaderboards. If xb.live is down, games still start offline.
- Manage installed games with play, local-file browsing, uninstall, and a DLC/Addons tab where every mod has an On/Off switch and its creator's credits. **▶ PLAY** starts the game with the mods that are on, and addons keep working across game updates.
- Saves tab with backup, restore, import, PS2 save conversion, and save editors for Midnight Club 3 and NINJA GAIDEN Black.
- Shader cache stays with the game, so only the first launch compiles shaders.
- Clear error messages that explain what went wrong and how to fix it, including an **Allow xrevive in Windows Security** button when Controlled folder access blocks an install.
- Spanish, Italian and Arabic are available under Settings > Language, and Arabic shows the whole window right to left.
- Add installed games to Steam (Settings or library), with cover art and Steam Input on Deck.
- System check for Windows 8.1+ and Direct3D 11, with optional Play anyway.
- XB Online saves from the old `XBL-Hosted` folder are copied into each game's usual save folder when you press Play. Existing saves are never replaced and nothing is deleted; once you've checked your saves, you can delete `SaveData\XBL-Hosted` yourself.

## You bring the games

xrevive does not include game ISOs or assets. Supply your own game files. This version downloads published executables instead of compiling games locally; titles without an available executable can be extracted for later use.

The Windows launcher and installer are Authenticode-signed. Launcher updates are signed with the xrevive update key. macOS packages are not notarized, so first-install security prompts may appear on macOS.

---

xrevive is a fan project. It is not affiliated with or endorsed by Microsoft.
