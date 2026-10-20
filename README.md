# xrevive

### **English** · [**Deutsch**](translations/README.de.md) · [**Français**](translations/README.fr.md) · [**Español**](translations/README.es.md) · [**Italiano**](translations/README.it.md) · [**Português (Brasil)**](translations/README.pt-BR.md) · [**Русский**](translations/README.ru.md) · [**العربية**](translations/README.ar.md) · [**日本語**](translations/README.ja.md) · [**简体中文**](translations/README.zh-CN.md)

A desktop launcher for original Xbox games recompiled with [Xrecomp](https://github.com/Teraflopping/Xrecomp), with online services from the Xbox Live revival at [xb.live](https://xb.live).

## Download

[Download for Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Download for Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [All installers and release notes](https://github.com/Teraflopping/xrevive/releases/latest)

The hosted game executables currently support **Windows x64**. On Linux they can run through Wine or Proton (experimental). macOS packages can't play games yet.

## Features

- Add your own ISO or extracted game folder, then download its matching executable. xrevive uses a game's Release build when there is one, and asks first before installing a Beta or Alpha build. Region-free, media-patched, renamed or re-signed dumps of a supported game are recognized too. A game installed from Beta or Alpha updates to its Release build once there is one for your copy.
- Browse any Release, Beta or Alpha game before installing it: activity, updates, leaderboards, achievements, addons and the live player and lobby count, with **INSTALL** right on its page.
- Automatic game and launcher update checks. Game updates remove the old executables they replace, and game downloads come from a server near you and resume if the connection drops.
- Sign in with xb.live (starting with Midnight Club 3 online), add friends by gamertag, and see live lobbies, community events and XB Online announcements. If xb.live is down, games still start offline.
- Manage installed games with play, local-file browsing, uninstall, and a DLC/Addons tab where every mod has an On/Off switch and its creator's credits. **▶ PLAY** starts the game with the mods that are on, and addons keep working across game updates.
- Saves tab on each game's page with backup, restore, import, **Move…** to a folder you choose, PS2 save conversion (no Xbox profile needed), and save editors for Midnight Club 3 and NINJA GAIDEN Black.
- Saves import from xemu even when another console signed them: NINJA GAIDEN Black saves and others with a known layout are re-signed for this PC and listed as unverified.
- Custom soundtracks: a Music screen to create soundtracks and add MP3, FLAC, Ogg, WAV, M4A or AAC songs that every supported game plays (Midnight Club 3 from its 1.0.7 update).
- Title updates from XB Online and DLC install automatically while the game is closed, and each game's Add-ons list shows its title update with a switch. Online play needs the title update: if it's missing or switched off, Play asks whether to download it (or turn it back on) or play offline this time.
- A game with DLC on XB Online's store lists it in its DLC/Addons tab with Download and Remove, and the game finds it the next time it starts.
- Per-game settings from the game menu: fullscreen, resolution, VSync, aspect ratio, brightness, contrast, saturation, anti-aliasing, FPS limit, and DirectX 12, DirectX 11 or Vulkan. Midnight Club 3 also has its own Language list, including the Portuguese, Russian and Arabic translation addons.
- Play time for each game, and game EXEs that keep one name across updates so NVIDIA Control Panel profiles stay applied.
- Settings lets you choose whether closing the window keeps xrevive running in the tray or quits it. Games that restart into their title update keep showing as playing, with play time and the online session carried over.
- Settings > Disc inspector reads a disc image's title, title ID, version and region and copies a report ready to paste into a bug report.
- Shader cache stays with the game, so only the first launch compiles shaders.
- Clear error messages that explain what went wrong and how to fix it, including an **Allow xrevive in Windows Security** button when Controlled folder access blocks an install.
- Choose from 10 languages under Settings > Language: English, German, French, Spanish, Italian, Brazilian Portuguese, Russian, Arabic, Japanese and Simplified Chinese. Arabic shows the whole window right to left.
- Add installed games to Steam (Settings or library), with cover art and Steam Input on Deck.
- Make each game your own: right-click a game and open Manage to choose your own banner and icon (PNG or JPEG). Otherwise the game list shows each game's own save icon from its default.xbe, and Add to Steam uses the same art.
- System check for Windows 8.1+ and Direct3D 11, with optional Play anyway.
- XB Online saves from the old `XBL-Hosted` folder are copied into each game's usual save folder when you press Play. Existing saves are never replaced and nothing is deleted; once you've checked your saves, you can delete `SaveData\XBL-Hosted` yourself.

## You bring the games

xrevive does not include game ISOs or assets. Supply your own game files. This version downloads published executables instead of compiling games locally; titles without an available executable can be extracted for later use.

The Windows launcher and installer are Authenticode-signed. Launcher updates are signed with the xrevive update key. macOS packages are not notarized, so first-install security prompts may appear on macOS.

---

xrevive is a fan project. It is not affiliated with or endorsed by Microsoft.
