# OPTCG UI Overhaul

A fan-made interface overhaul for OPTCG Sim. It only changes how the game looks and adds conveniences. It never changes game rules, your matches or anything sent to other players.

**[Download the latest version](https://github.com/Brayden-Brezden/OPTCG-UI-Overhaul/releases/latest)** (v1.5.0, made for OPTCG Sim 1.44a). Grab the `.zip` under "Assets".

**[Join the Discord](https://discord.gg/A2zVg2dtv2)** for help, bug reports, new versions and card reveals.

## Install

1. Close OPTCG Sim.
2. Right-click the zip > **Extract All...**, click **Browse...** and pick your OPTCG Sim folder (the one with `OPTCGSim.exe`), then click **Extract**. If Windows asks, choose **Replace the files in the destination**.
3. Start the game. The first launch takes a few extra seconds. You'll see "OPTCG UI Overhaul v1.5.0 - F8 menu" in the bottom-left corner when it's working.

Already using other BepInEx mods? Only copy `BepInEx\plugins\OPTCGUIOverhaul` into your existing `BepInEx\plugins` folder (the mod needs BepInEx 5, x64).

## Updating

From 1.5.0 on, the main menu tells you when a new version is out here. **Update and restart** downloads it, installs it and starts the game again. You can also extract the new zip the same way and choose **Replace**. Your settings and your own files are kept either way.

When OPTCG Sim itself updates, the mod puts itself back by itself (see the README in the zip).

## What's in it

- A redesigned main menu, settings, lobby, deck editor and match screens, with presets, dark/light, your own accent colours and fonts.
- Customize: your own card backs, DON!! cards, playmats, music and alternate card art.
- Deck folders, a deck browser, deck previews, Undo / Redo, and deck Stats, Test hand (with draw odds) and Notes (tags and a ban-list check).
- In a match: your-turn alert, keyword tips, double-click to attack, see both decks after the match, Copy result (a picture for Discord) and a turn-by-turn Review.
- Meta: leader rankings, tournaments and your own match stats.
- Buddy: a little pixel-art friend in a box on your screen.

The full list is in the README inside the zip, and each release lists what's new.

## Turn it off / uninstall

- **Turn off** (keep everything): rename `winhttp.dll` to `winhttp.dll.off`. Rename it back to turn it on.
- **Uninstall**: delete `winhttp.dll`, `doorstop_config.ini`, `.doorstop_version` and the `BepInEx` folder from your game folder, and `OPTCGSim_Data\StreamingAssets\UIOverhaul_Restore`. Your settings are in `%USERPROFILE%\AppData\LocalLow\Batsu\OPTCGSim\UIOverhaul`.

## Help and bug reports

Ask in **#help** or post in **#bug-reports** on the [Discord](https://discord.gg/A2zVg2dtv2). Attach `BepInEx\LogOutput.log` from your game folder, and an F9 screenshot if it's something you can see.

## Credits

- BepInEx 5 and HarmonyX (MIT): the mod loader.
- Fonts: Inter, JetBrains Mono and Poppins (SIL Open Font License), Tabler Icons (MIT).
- Meta statistics: Car D. Kaizoku (cardkaizoku.com). Tournaments: Egman Events. ChinoizeCup: Limitless TCG.
- Not affiliated with OPTCG Sim, Bandai, Toei Animation or Shueisha. ONE PIECE (c) Eiichiro Oda / Shueisha / Toei Animation.
