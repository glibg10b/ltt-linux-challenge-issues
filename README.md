# LTT Linux daily driver challenge issues

A list of issues Linus and Luke experienced during the LTT Linux Daily Driver Challenge. 

## The issues

Note: Just because LTT considers these problems, doesn't mean all of them are.

### [Part 1](https://www.youtube.com/watch?v=0506yDSgU7M)

- [ ] [GoXLR compatibility.](https://youtu.be/0506yDSgU7M?t=552)
- [ ] [**Pop!\_OS**: no alternative to HWiNFO.](https://youtu.be/0506yDSgU7M?t=579)
  - **Possible fix:** Make it ship with Hardinfo.
- [x] [**Pop!\_OS:** + **Apt**: Installing Steam uninstalled essential packages and it isn't clear that this is bad.](https://youtu.be/0506yDSgU7M?t=607) ([**Fixed**](https://github.com/pop-os/apt/pull/1))
- [ ] [USB errors on boot.](https://youtu.be/0506yDSgU7M?t=870)
  - **Possible fix:** https://www.spinics.net/lists/usb/msg02644.html
- [ ] [**Mint**: "Removing..." when installing Steam.](https://youtu.be/0506yDSgU7M?t=921)
- [ ] [**Plasma**: "Configure Audio Volume..." button unintuitive.](https://youtu.be/0506yDSgU7M?t=982) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/11))
- [ ] [**Plasma**: Check boxes under "Hardware Configuration" look like radio buttons.](https://youtu.be/0506yDSgU7M?t=991) ([Open issue](https://gitlab.manjaro.org/applications/manjaro-settings-manager/-/issues/194))
- [ ] [**Cave Story+**: Off-center.](https://youtu.be/0506yDSgU7M?t=1101)

### [Part 2](https://youtu.be/3E8IGy6I9Wo)

- [ ] [**Manjaro**: `command not found: apt` isn't enough.](https://youtu.be/3E8IGy6I9Wo?t=107)
  - **Possible fix:** Maybe command-not-found can show a warning for it? Or [#10](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/10).
- [ ] [**NVIDIA**: X Server Settings is lacking.](https://youtu.be/3E8IGy6I9Wo?t=183)
- [ ] [**OBS**: Requires restart for some things to work correctly, but doesn't say so.](https://youtu.be/3E8IGy6I9Wo?t=224)
- [ ] [**Manjaro**: The option to show Snap, Flatpak, and AUR packages in Pamac is "hidden".](https://youtu.be/3E8IGy6I9Wo?t=540)
  - **Possible fix:** [#20](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/20)
- [ ] [**Plasma**: Mouse wheel in "Audio Volume" scrolls through both devices and levels of devices.](https://youtu.be/3E8IGy6I9Wo?t=573) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/9))

### [Part 3](https://youtu.be/TtsglXhbxno)

- [ ] [**Plasma**: Notifications easy to miss on large screens.](https://youtu.be/TtsglXhbxno?t=163) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/4))
- [ ] [**Plasma**: Okular signature support is broken.](https://youtu.be/TtsglXhbxno?t=281) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/5), [open bug report](https://bugs.kde.org/show_bug.cgi?id=315930))
- [ ] [**Linux Mint**: Can't drag a folder of fonts onto font previewer to install them.](https://youtu.be/TtsglXhbxno?t=455) ([Open issue](https://gitlab.gnome.org/GNOME/gnome-font-viewer/-/issues/5))
- [ ] [**Ark**: Dragging files on top of a folder in Dolphin copies them into the parent folder.](https://youtu.be/TtsglXhbxno?t=499) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/8))
- [ ] [**Ark**: Compression appears to finish instantly when, in fact, it does not.](https://youtu.be/TtsglXhbxno?t=732) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/3))
- [x] [**Ark**: Weird extension when compressing.](https://youtu.be/TtsglXhbxno?t=732) ([**Fixed**](https://invent.kde.org/utilities/ark/-/merge_requests/79))
- [ ] [**Ark**: Doesn't prompt for filename when compressing multiple files.](https://youtu.be/TtsglXhbxno?t=816) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/10))
- [ ] [**Dolphin**: Right-click drag doesn't work like in Windows.](https://youtu.be/TtsglXhbxno?t=1024)
  - **Workaround:** Use left-click drag.
- [ ] [Fullscreen doesn't work in VLC media player.](https://youtu.be/TtsglXhbxno?t=1234)
  - **Workaround:** Set the rendering backend to OpenGL 3.1 (System Settings/Hardware/Display and Monitor/Compositor)
- [ ] [**Mint:** Window movement while a game is open is laggy.](https://youtu.be/TtsglXhbxno?t=1294) ([Open issue](https://github.com/linuxmint/Cinnamon/issues/2465))
- [ ] [**Arch**: obs-studio doesn't come installed with the Browser Source plugin.](https://youtu.be/TtsglXhbxno?t=1408)
  - **Possible fix:** Arch should package it with the Browser Source plugin. 
  - **Workaround**: Use the AUR.
- [ ] [**Dolphin**: Doesn't work as root.](https://youtu.be/TtsglXhbxno?t=1496) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/6))
  - **Workaround:** [Open Dolphin as root](https://store.kde.org/p/1384645/) service menu.
    - **For Arch:** [aur/root](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/22)

### WAN show

- [ ] [**Plasma**: "Show Desktop" doesn't work like in Windows.](https://youtu.be/fJB9fdXWiiw?t=497)
  - **Workaround:** Replace it with the "Minimize all Windows" applet ([#13](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/13)).
- [ ] [**Plasma**: Applications' names don't represent their jobs (e.g. "Kate").](https://youtu.be/fJB9fdXWiiw?t=702)
  - **Possible fix:** Put the applications' descriptions in parentheses next to their names (e.g. "Kate (text editor)").
- [x] [Luke's system locks up when his TV turns on.](https://youtu.be/sS25mCLyQyk?t=416) ([**Fixed**](https://bugs.kde.org/show_bug.cgi?id=446699))

## Contributing

If you have a workaround for one of these issues, please [create an issue](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/new/choose) or submit a pull request. Discussions can be started [here](https://github.com/glibg10b/ltt-linux-challenge-issues/discussions/categories/general). 

*Links to bug reports/merge requests are greatly appreciated!*
