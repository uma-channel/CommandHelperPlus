English | [日本語](README_ja.md)

![CHP](https://github.com/uma-channel/CommandHelperPlus/blob/main/logos/chp_logo.png)

### Command Helper Plus makes Minecraft commands easier and more comfortable. 
### An essential mod that refines every single detail.

# Overview

- **Please check the [Official Website](https://chp.clpc.club) for all details.**
- **You can download the mod from [Modrinth](https://modrinth.com/mod/cmd-helper-plus).**

# Feature List

Click on any category below to expand and view its detailed features.

<details>
<summary><b>1. Completion</b> — Comfortable command input, thanks to completion.</summary>

* **SpyglassMC completion**: Merges SpyglassMC suggestions into vanilla completion in the chat box and in the command block (block and minecart) editor.
* **Structural symbols**: Suggests `[ { " ] } , = :` and adds the separator after key suggestions.
* **Auto-close**: Closes brackets and quotes automatically. Typing a closing symbol overwrites it, Backspace removes the pair, and it also works after confirming with Tab or a click.
* **Type labels**: Shows the type as a dim label on the right of each suggestion, such as `[boolean]` or `[float]`.
* **Inside {Command:"…"}**: Completes the contents of the string as a single command, with auto-close and auto-escape for the inner layer.
* **Permission-aware**: At the command name position, narrows suggestions to the commands your permission level can use.
* **Follows your version**: Suggests what fits the Minecraft version you are playing. You can also choose any version in the settings.

</details>

<details>
<summary><b>2. Syntax check</b> — Spot mistakes before you run.</summary>

* **Underlined errors**: Shortly after you stop typing, the faulty part is underlined. Errors are red and warnings are yellow.
* **Reasons as tooltips**: Hover over an underline to read the message. It works even while a long command is scrolled sideways.
* **In command blocks too**: Works both in the chat box and in the command block editor.
* **Inside {Command:"…"}**: Mistakes inside the nested string are underlined as well.
* **Checking existing IDs**: IDs such as data pack functions, and custom commands added by plugins or mods, raise no warnings. IDs that do not exist turn yellow.

</details>

<details>
<summary><b>3. History & favorites</b> — Find and reuse the commands you typed.</summary>

* **History button**: Adds a History button above the chat input. It opens a screen with two tabs: history and favorites.
* **Search**: Filter history and favorites by keywords. Words are separated by spaces and combined with AND, ignoring case.
* **Click to reuse**: Click a row to go back to the chat with it in the input box. Right-click to copy.
* **Larger history**: Vanilla keeps 50 entries. This mod keeps 1000 by default, adjustable from 50 to 100000 in the settings.
* **Automatic de-duplication**: Identical commands are merged into one and ordered by last use. The Up and Down arrow history updates right away.
* **Favorites**: Star a command to save it, star again to remove it. Favorites are stored separately, outside the history limit and de-duplication.
* **Shortcut keys**: Assign a key combination containing Ctrl, Alt or Super to a favorite. Pressing it replaces the input with that command without running it.
* **Deletion needs confirmation**: A confirmation screen appears before anything is deleted. Only deleting history can skip the confirmation, through a setting.

</details>

<details>
<summary><b>4. Command blocks</b> — See long commands at a glance.</summary>

* **Horizontal scrolling**: When a command does not fit the input box, a scroll bar appears below it. Drag it, click it or use the mouse wheel. The cursor does not move.
* **Minecarts too**: Works in the editor of both command blocks and command block minecarts.
* **Aim to see contents** `[op required]`: Aim at a command block to see its contents at the lower right. Long commands are cut off after 8 lines. You can switch it in the settings.

</details>

<details>
<summary><b>5. Long commands</b> — Go beyond 256 characters.</summary>

* **Raised limit**: Only commands starting with `/` can be typed and sent up to 32767 characters by default. Adjustable from 256 to 32767.
* **Horizontal scrolling**: Scroll sideways with the vertical mouse wheel. The cursor does not move.
* **Normal chat unchanged**: Messages without a leading `/` stay at the vanilla 256 characters.
* **Safety for signed commands**: Commands with signed arguments, such as `/say` and `/msg`, are trimmed to 256 characters when sent so the connection does not drop.
* **Survives going back**: Long input is not trimmed when you return from the history screen or resize the window.

</details>

<details>
<summary><b>6. Game controls</b> — Redo things with one button.</summary>

* **Rejoin**: Adds a button to the pause screen. It re-enters the same world in singleplayer or the same server in multiplayer. Realms is not supported.
* **Restart**: Adds a button to the title screen that relaunches the game with the same launch setup. The confirmation screen hides the launch command at first.
* **Faster data pack reload**: Optimizes the `/reload` process. When installed on the server side, it also functions in multiplayer.
* **Open the data pack folder**: A pause screen button opens the datapacks folder of the world (singleplayer).
* **Open the config file**: Open the config file and the config folder right from the settings screen.
* **Skip experimental prompts**: Automatically skips the confirmation about experimental settings when opening or creating a world. Off by default.

</details>

<details>
<summary><b>7. Display</b> — Make the unseen visible.</summary>

* **Scoreboard HUD** `[op required]`: Shows several scoreboards at once at the top left. Choose the target selector in the settings; fake players can be added too (up to 4).
* **Translucent invisible entities**: Invisible entities look translucent. Works without spectator mode and needs no op.
* **Marker display** `[op required]`: Shows markers, which are never sent to the client, as particle crosses.
* **Forced name tags**: Shows name tags hidden by team settings or invisibility. For invisibility, it applies only while translucent display is on.

</details>

<details>
<summary><b>8. Settings</b> — Turn on only what you need.</summary>

* **Settings screen**: Open it from Mod Menu, or with the key assigned to Open Settings in the controls (`O` by default).
* **Many options**: Completion, auto-close, syntax check, length limit, history size, HUD and more can each be switched.
* **No restart needed**: Changes made on the screen apply to the game right away.

</details>

# Supported Versions
✅: Implemented | 📝: Planned
| Loader | Version | Status |
|---|---|---|
| Fabric | 1.21.10 | ✅ |
| Fabric | 1.21.11 | ✅ |
| Fabric | 26.3 | ✅ |
| Fabric | Latest Release | 📝 |

## **Can't find the version you're looking for?**
If there is enough feedback on [Discord](https://dsc.gg/cmd-helper-plus), we might take action.

# Prerequisites

- **Minecraft**: Java Edition
- **Mod Loader**: Fabric
- **Required Mod**: [Fabric API](https://modrinth.com/mod/fabric-api/versions?c=release)
- **Recommended Mod**: [ModMenu](https://modrinth.com/mod/modmenu/versions?c=release&l=fabric)
- **Environments**: Client-side only, Server-side only, or both

# Super Thanks
[Copyright (c) 2019-2025 SPGoding and SpyglassMC contributors](https://spyglassmc.com)

# LICENSE

© 2026 Command Helper Plus / UMA. All rights reserved.
> See [LICENSE](https://github.com/uma-channel/CommandHelperPlus/blob/main/LICENSE) for more details.
