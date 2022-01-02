# Are we Linus yet?

Is Linux up to Linus Sebastian's Standards Yet?

## Let's see...

### General issues

- [x] [[**Fixed**](https://github.com/pop-os/apt/pull/1)] [**Pop!\_OS:** + **Apt**: Installing Steam doesn't uninstall essential packages. Apt also prevents you from uninstalling essential packages](https://youtu.be/0506yDSgU7M?t=607)
- [ ] [**Mint**: "Removing..." when installing Steam](https://youtu.be/0506yDSgU7M?t=921)
- [ ] [Fullscreen doesn't work in VLC media player](https://youtu.be/TtsglXhbxno?t=1234)
  - **Workaround:** Set the rendering backend to OpenGL 3.1 (System Settings/Hardware/Display and Monitor/Compositor)
- [ ] [[Open issue](https://github.com/linuxmint/Cinnamon/issues/2465)] [**Mint:** Window movement while a game is open is laggy](https://youtu.be/TtsglXhbxno?t=1294)
- [ ] [**Arch**: obs-studio doesn't come installed with the Browser Source plugin](https://youtu.be/TtsglXhbxno?t=1408)
  - **Possible fix:** Arch should package it with the Browser Source plugin
  - **Workaround**: Use the AUR
- [ ] [**NVIDIA**: X Server Settings is lacking](https://youtu.be/3E8IGy6I9Wo?t=183)

### Usability

- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/11)] [**Plasma**: "Configure Audio Volume..." button unintuitive.](https://youtu.be/0506yDSgU7M?t=982)
- [ ] [[Open issue](https://gitlab.manjaro.org/applications/manjaro-settings-manager/-/issues/194)] [**Mint**: Check boxes under "Hardware Configuration" look like radio buttons](https://youtu.be/0506yDSgU7M?t=991)
- [ ] [[WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/4)] [**Plasma**: Notifications easy to miss on large screens](https://youtu.be/TtsglXhbxno?t=163)
- [x] [[**Fixed**](https://invent.kde.org/graphics/okular/-/merge_requests/516)] [**Plasma**: Okular doesn't ask you to draw a rectangle if you have no signatures](https://youtu.be/TtsglXhbxno?t=266).
- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/5), [open bug report](https://bugs.kde.org/show_bug.cgi?id=315930)] [**Plasma**: Okular signature support is broken](https://youtu.be/TtsglXhbxno?t=281)
- [ ] [[Open issue](https://gitlab.gnome.org/GNOME/gnome-font-viewer/-/issues/5)] [**Linux Mint**: Can't drag a folder of fonts onto font previewer to install them.](https://youtu.be/TtsglXhbxno?t=455)
- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/8)] [**Ark**: Dragging files on top of a folder in Dolphin copies them into the parent folder](https://youtu.be/TtsglXhbxno?t=499)
- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/3)] [**Ark**: Compression appears to finish instantly when, in fact, it does not](https://youtu.be/TtsglXhbxno?t=732)
- [x] [[**Fixed**](https://invent.kde.org/utilities/ark/-/merge_requests/79)] [**Ark**: Compressing files have a user-friendly .part extension](https://youtu.be/TtsglXhbxno?t=732)
- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/10)] [**Ark**: Doesn't prompt for filename when compressing multiple files](https://youtu.be/TtsglXhbxno?t=816)
- [ ] [**Dolphin**: Right-click drag doesn't work like in Windows](https://youtu.be/TtsglXhbxno?t=1024)
  - **Workaround:** Use left-click drag
- [ ] [**Manjaro**: `command not found: apt` apparently isn't enough](https://youtu.be/3E8IGy6I9Wo?t=107)
  - **Possible fix:** Maybe command-not-found can show a warning for it? Or [#10](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/10)
- [ ] [**OBS**: Requires restart for some things to work correctly, but doesn't say so](https://youtu.be/3E8IGy6I9Wo?t=224)
- [ ] [**Manjaro**: The option to show Snap, Flatpak, and AUR packages in Pamac is "hidden"](https://youtu.be/3E8IGy6I9Wo?t=540)
  - **Possible fix:** [#20](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/20)
- [x] [[**Fixed**](https://invent.kde.org/teams/usability/issue-board/-/issues/9)] [**Plasma**: Mouse wheel in "Audio Volume" doesn't scroll through devices and levels of devices at the same time](https://youtu.be/3E8IGy6I9Wo?t=573)
- [x] [[**Fixed**](https://invent.kde.org/teams/usability/issue-board/-/issues/6)] [**Dolphin**: Supports root access](https://youtu.be/TtsglXhbxno?t=1496)
- [ ] [[Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/12)] [**Plasma**: "Show Desktop" doesn't work like in Windows](https://youtu.be/fJB9fdXWiiw?t=497)
- [ ] [**Plasma**: Applications' names don't represent their jobs (e.g. "Kate")](https://youtu.be/fJB9fdXWiiw?t=702)
  - **Possible fix:** Put the applications' descriptions in parentheses next to their names (e.g. "Kate (text editor)").

### Hardware

- [ ] [USB errors on boot](https://youtu.be/0506yDSgU7M?t=870)
  - **Possible fix:** https://www.spinics.net/lists/usb/msg02644.html
- [ ] [GoXLR compatibility](https://youtu.be/0506yDSgU7M?t=552)
- [ ] [**Mint**: Luke's system locked up when his TV turned on](https://youtu.be/sS25mCLyQyk?t=416)

### Gaming

- [ ] [**Cave Story+**: Off-center](https://youtu.be/0506yDSgU7M?t=1101)
  - **Workaround**: https://steamcommunity.com/sharedfiles/filedetails/?id=129059216
- [ ] [**Xbox One wireless controller**: Only works when plugged in](https://youtu.be/Rlg4K16ujFw?t=228)
- [ ] [**CS:GO**: Stutters](https://youtu.be/Rlg4K16ujFw?t=411)
- [ ] [**Easy Anti-Cheat**: Doesn't support Linux](https://youtu.be/Rlg4K16ujFw?t=421)
- [ ] [**It Takes Two**: Doesn't support multiple controllers](https://youtu.be/Rlg4K16ujFw?t=510)
- [ ] [**Forged Alliance Forever**: A pain to get working](https://youtu.be/Rlg4K16ujFw?t=572)
- [ ] [**Anno 1800**: Doesn't support multiplayer on Linux](https://youtu.be/Rlg4K16ujFw?t=717)
- [ ] [**Minecraft Dungeons**: Hard to get working through the Minecraft Launcher](https://youtu.be/Rlg4K16ujFw?t=757)
- [ ] [**Escape from Tarkov**: Is broken](https://youtu.be/Rlg4K16ujFw?t=834)
- [ ] [**Genshin Impact**: Doesn't support Linux](https://youtu.be/Rlg4K16ujFw?t=850)

## Contributing

If you have a workaround for one of these issues, please [create an issue](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/new/choose) or submit a pull request. Discussions can be started [here](https://github.com/glibg10b/ltt-linux-challenge-issues/discussions/categories/general)

Thanks to [u/Xornial](https://www.reddit.com/user/Xornial/) for hosting [arewelinusyet.com](https://arewelinusyet.com/)!

*Links to bug reports/merge requests are greatly appreciated!*
