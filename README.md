# Broadcast Creator

**Build your own TV presentation package for College Football 27: score bug, other-game scores, pregame,
loading screen, touchdown and field goal graphics, play-call screens, fonts and more.**

Pick a starter look (or start blank), change the names, colours, fonts and pieces, and build a `.fbmod` you import in the
Mod Manager. No code or file editing.

**[Download the latest release](https://github.com/sdmart3/broadcast-creator-releases/releases/latest)**

## What you need

- Windows 10 or 11 (64-bit), College Football 27, and the Mod Manager you already use for CFB 27.
- About 2 GB of free disk space. Python and every tool the app needs come in the zip.

## Quick start

1. Download the zip from the latest release and unzip the whole folder somewhere you can write to (not Program Files).
2. Run `Broadcast Creator.exe` and let **Setup check** find your game and Mod Manager.
3. **New package**: pick one of the 8 starters or **Start blank**, name your network, and press **Create package**.
4. Change colours, fonts, the score bug and the other screens, then **Build & check**.
5. Import the `.fbmod` in the Mod Manager, turn it on (one score bug mod at a time), and launch the game from the Mod Manager.

`HOW-TO.md` in the zip walks through every page step by step.

## Beta

This is a beta. Pages marked **experimental** work but may still change. If something looks wrong or
confusing, open an issue here or say so in the Discord.

## Latest: beta 3

Text size fixes: every text box in the layout editor has a **When too long** setting (Shrink to fit, Let it overflow,
Cut off at the box), the preview draws text at the game's size, and the Check list warns you when a size will be drawn
smaller in the game. `CHANGELOG.md` in the zip lists everything.

## Moving to a new version (keep your themes)

Your themes live in the `packages` folder inside the app's folder.

1. Unzip the new version into a **new** folder, next to the old one.
2. Open the app. If it finds your old folder, it offers to copy your themes in (Home, or Settings > Themes from an
   older install). It never changes the old folder.
3. Or copy the old `packages` folder into the new one yourself, or point Settings > Folders > Packages at the old one.
4. Rebuild each theme and replace the old `.fbmod` in the Mod Manager.
