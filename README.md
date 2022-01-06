# Are we Linus yet?

Is Linux up to Linus Sebastian's Standards Yet?

## Let's see...

### General

- [x] [**Pop!\_OS:** + **Apt**: Steam installs normally + apt prevents you from uninstalling essential packages](https://youtu.be/0506yDSgU7M?t=607) [<sup>(fix)</sup>](https://github.com/pop-os/apt/pull/1)
- [ ] [**Mint**: "Removing..." when installing Steam](https://youtu.be/0506yDSgU7M?t=921)
- [x] [4K videos play normally](https://youtu.be/TtsglXhbxno?t=974)
- [ ] [Fullscreen doesn't work in VLC media player](https://youtu.be/TtsglXhbxno?t=1234)
  - **Workaround:** Set the rendering backend to OpenGL 3.1 (System Settings/Hardware/Display and Monitor/Compositor)
- [ ] [**Mint:** Window movement while a game is open is laggy](https://youtu.be/TtsglXhbxno?t=1294) [<sup>(issue)</sup>](https://github.com/linuxmint/Cinnamon/issues/2465)
- [ ] [**Arch**: obs-studio doesn't come installed with the Browser Source plugin](https://youtu.be/TtsglXhbxno?t=1408) [<sup>(closed issue)</sup>](https://bugs.archlinux.org/task/66008)
  - **Workaround**: Install obs-browser
- [ ] [**NVIDIA**: X Server Settings is lacking](https://youtu.be/3E8IGy6I9Wo?t=183)

### Usability

- [ ] [**Plasma**: "Configure Audio Volume..." button unintuitive.](https://youtu.be/0506yDSgU7M?t=982) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/11)
- [ ] [**Mint**: Check boxes under "Hardware Configuration" look like radio buttons](https://youtu.be/0506yDSgU7M?t=991) [<sup>(issue)</sup>](https://gitlab.manjaro.org/applications/manjaro-settings-manager/-/issues/194)
- [ ] [**Manjaro**: `command not found: apt` apparently isn't enough](https://youtu.be/3E8IGy6I9Wo?t=107)
  - **Possible fix:** Maybe command-not-found can show a warning for it? Or [#10](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/10)
- [ ] [**OBS**: Requires restart for some things to work correctly, but doesn't say so](https://youtu.be/3E8IGy6I9Wo?t=224)
- [ ] [**Manjaro**: The option to show Snap, Flatpak, and AUR packages in Pamac is "hidden"](https://youtu.be/3E8IGy6I9Wo?t=540)
  - **Possible fix:** [#20](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/20)
- [x] [**Plasma**: Mouse wheel in "Audio Volume" works as expected](https://youtu.be/3E8IGy6I9Wo?t=573) [<sup>(fix)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/9)
- [ ] [**Plasma**: Notifications easy to miss on large screens](https://youtu.be/TtsglXhbxno?t=163) [<sup>(WIP fix)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/4)
- [ ] [**Plasma**: Okular signature support is broken](https://youtu.be/TtsglXhbxno?t=281) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/5) [<sup>(report)</sup>](https://bugs.kde.org/show_bug.cgi?id=315930)
- [x] [**LibreOffice Calc**: Exporting a chart is easy](https://youtu.be/TtsglXhbxno?t=423)
- [ ] [**Mint**: Can't drag a folder of fonts onto font previewer to install them.](https://youtu.be/TtsglXhbxno?t=455) [<sup>(issue)</sup>](https://gitlab.gnome.org/GNOME/gnome-font-viewer/-/issues/5)
- [x] [Installing fonts is easy](https://youtu.be/TtsglXhbxno?t=566)
- [ ] [**Ark**: Dragging files on top of a folder in Dolphin copies them into the parent folder](https://youtu.be/TtsglXhbxno?t=499) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/8)
- [ ] [**Ark**: Compression appears to finish instantly when, in fact, it does not](https://youtu.be/TtsglXhbxno?t=732) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/3)
- [x] [**Ark**: Compressing files have an idiot-proof .part extension](https://youtu.be/TtsglXhbxno?t=732) [<sup>(fix)</sup>](https://invent.kde.org/utilities/ark/-/merge_requests/79)
- [ ] [**Ark**: Doesn't prompt for filename when compressing multiple files](https://youtu.be/TtsglXhbxno?t=816) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/10)
- [x] [Taking a screenshot is easy](https://youtu.be/TtsglXhbxno?t=940)
- [x] [Adding startup applications is easy](https://youtu.be/TtsglXhbxno?t=964)
- [x] [Search keywords are user-friendly](https://youtu.be/TtsglXhbxno?t=1001)
- [ ] [**Dolphin**: Right-click drag doesn't work like in Windows](https://youtu.be/TtsglXhbxno?t=1024)
  - **Workaround:** Use left-click drag
- [x] [Making a shortcut is easy](https://youtu.be/TtsglXhbxno?t=1036)
- [x] [Mounting a network share is easy](https://youtu.be/TtsglXhbxno?t=1076)
- [x] [**Dolphin**: Supports root access](https://youtu.be/TtsglXhbxno?t=1496) [<sup>(fix)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/6)
- [ ] [**Plasma**: "Show Desktop" doesn't work like in Windows](https://youtu.be/fJB9fdXWiiw?t=497) [<sup>(issue)</sup>](https://invent.kde.org/teams/usability/issue-board/-/issues/12)
- [ ] [**Plasma**: Applications' names don't represent their jobs (e.g. "Kate")](https://youtu.be/fJB9fdXWiiw?t=702)
  - **Possible fix:** Put the applications' descriptions in parentheses next to their names (e.g. "Kate (text editor)").

### Hardware

- [x] [Thunderbolt just works](https://youtu.be/0506yDSgU7M?t=445)
- [ ] [GoXLR support](https://youtu.be/0506yDSgU7M?t=552)
- [ ] [USB errors on boot](https://youtu.be/0506yDSgU7M?t=870)
  - **Possible fix:** https://www.spinics.net/lists/usb/msg02644.html
- [x] [Controllers just work](https://youtu.be/0506yDSgU7M?t=987)
- [x] [Printing just works](https://youtu.be/TtsglXhbxno?t=600)

### Gaming

- [ ] [**Cave Story+**: Off-center](https://youtu.be/0506yDSgU7M?t=1101)
  - **Workaround**: https://steamcommunity.com/sharedfiles/filedetails/?id=129059216
- [x] [Native Linux games work well](https://youtu.be/Rlg4K16ujFw?t=218)
- [ ] [**Xbox One wireless controller**: Only works when plugged in](https://youtu.be/Rlg4K16ujFw?t=228)
  - **Workaround**: [xow](https://github.com/medusalix/xow)
- [x] [**Legion TD 2**](https://youtu.be/Rlg4K16ujFw?t=250)
- [x] [**Tower Fall Ascension**](https://youtu.be/Rlg4K16ujFw?t=252)
- [x] [**Faster Than Light**](https://youtu.be/Rlg4K16ujFw?t=253)
- [x] [**Slay the Spire**](https://youtu.be/Rlg4K16ujFw?t=254)
- [x] [**Path of Exile**](https://youtu.be/Rlg4K16ujFw?t=255)
- [x] [**Rust**](https://youtu.be/Rlg4K16ujFw?t=257)
- [x] [**DOOM Eternal**: Performance is great](https://youtu.be/Rlg4K16ujFw?t=369)
- [ ] [**CS:GO**: Stutters](https://youtu.be/Rlg4K16ujFw?t=411)
- [ ] [**Easy Anti-Cheat**: Doesn't support Linux](https://youtu.be/Rlg4K16ujFw?t=421)
- [ ] [**It Takes Two**: Doesn't support multiple controllers](https://youtu.be/Rlg4K16ujFw?t=510)
- [ ] [**Forged Alliance Forever**: A pain to get working](https://youtu.be/Rlg4K16ujFw?t=572)
- [ ] [**Anno 1800**: Doesn't support multiplayer on Linux](https://youtu.be/Rlg4K16ujFw?t=717)
- [ ] [**Minecraft Dungeons**: Hard to get working through the Minecraft Launcher](https://youtu.be/Rlg4K16ujFw?t=757)
- [ ] [**Escape from Tarkov**: Is broken](https://youtu.be/Rlg4K16ujFw?t=834)
- [ ] [**Genshin Impact**: Doesn't support Linux](https://youtu.be/Rlg4K16ujFw?t=850)
- [x] [**Minecraft Java**](https://youtu.be/Rlg4K16ujFw?t=908)
- [x] [**Don't starve together**](https://youtu.be/Rlg4K16ujFw?t=919)
- [x] [**Towerfall**](https://youtu.be/Rlg4K16ujFw?t=927)

## Contributing

If you have a workaround for one of these issues, please [create an issue](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/new/choose) or submit a pull request. Discussions can be started [here](https://github.com/glibg10b/ltt-linux-challenge-issues/discussions/categories/general)

Thanks to [u/Xornial](https://www.reddit.com/user/Xornial/) for hosting [arewelinusyet.com](https://arewelinusyet.com/)!

*Links to bug reports/merge requests are greatly appreciated!*
