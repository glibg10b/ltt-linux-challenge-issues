# LTT Linux daily driver challenge issues

A list of issues Linus and Luke experienced during the LTT Linux Daily Driver Challenge. 

## The issues

Note: Just because LTT considers these problems, doesn't mean all of them are.

### [Part 1](https://www.youtube.com/watch?v=0506yDSgU7M)

- [ ] [Searching "Best Linux distro for gaming" on Google brings up really bad websites.](https://www.youtube.com/watch?v=0506yDSgU7M&t=67s)
  - **Possible fix:** Try [Distrochooser](https://distrochooser.de/), it's really good.
- [ ] [The Mint USB behaved strangely with Luke's monitors the first time.](https://youtu.be/0506yDSgU7M?t=398)
- [ ] [GoXLR acts as an input when configured as an output device.](https://youtu.be/0506yDSgU7M?t=552)
- [ ] [Pop!\_OS doesn't have a noob-friendly way of checking what hardware is connected and whether the drivers work.](https://youtu.be/0506yDSgU7M?t=579)
  - **Possible fix:** Make it ship with Hardinfo installed.
- [x] [Installing Steam uninstalls essential packages and it isn't clear that this is bad.](https://youtu.be/0506yDSgU7M?t=607) ([Fixed](https://github.com/pop-os/apt/pull/1)) 
- [ ] [USB errors on boot.](https://youtu.be/0506yDSgU7M?t=870)
  - **Possible fix:** https://www.spinics.net/lists/usb/msg02644.html
- [ ] [Installing Steam from Mint Software Manager shows "Removing...".](https://youtu.be/0506yDSgU7M?t=921)
- [ ] [Linus doesn't like KDE Plasma's settings design.](https://youtu.be/0506yDSgU7M?t=982) ([WIP fix](https://invent.kde.org/plasma/systemsettings/-/issues/13))
- [ ] [The check boxes under "Hardware Configuration" look like radio buttons.](https://youtu.be/0506yDSgU7M?t=991) ([Open issue](https://gitlab.manjaro.org/applications/manjaro-settings-manager/-/issues/194))
- [ ] [Cave Story+ looks weird.](https://youtu.be/0506yDSgU7M?t=1101)

### [Part 2](https://youtu.be/3E8IGy6I9Wo)

- [ ] [Using apt or apt-get on Manjaro doesn't warn you that you're using the wrong package manager.](https://youtu.be/3E8IGy6I9Wo?t=107)
  - **Possible fix:** Maybe command-not-found can show a warning for it? Or [#10](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/10).
- [ ] [NVIDIA X Server Settings is lacking.](https://youtu.be/3E8IGy6I9Wo?t=183)
- [ ] [OBS requires a restart (or something) for some things to work correctly, but doesn't say so.](https://youtu.be/3E8IGy6I9Wo?t=224)
- [ ] [The option to show Snap, Flatpak, and AUR packages in Pamac is "hidden".](https://youtu.be/3E8IGy6I9Wo?t=540)
  - **Possible fix:** [#20](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/20)
- [ ] [Scrolling with the mouse wheel in KDE's volume mixer applet scrolls through both devices and levels of devices.](https://youtu.be/3E8IGy6I9Wo?t=573) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/9))

### [Part 3](https://youtu.be/TtsglXhbxno)

- [ ] [The "Moving" Dolphin notification is easy to miss on a large screen.](https://youtu.be/TtsglXhbxno?t=163) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/4))
- [x] [Linus can't find Dolphin's refresh button.](https://youtu.be/TtsglXhbxno?t=203) ([Fixed](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/12))
- [ ] [Okular's dialog about "no available signing certificates" refers to a manual, which does not explain the difference between a cryptographic signature and superimposing an image of a signature.](https://youtu.be/TtsglXhbxno?t=281) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/5), [open bug report](https://bugs.kde.org/show_bug.cgi?id=315930))
- [ ] [You can't drag a folder of fonts onto Linux Mint's font previewer to install them.](https://youtu.be/TtsglXhbxno?t=455) ([Open issue](https://gitlab.gnome.org/GNOME/gnome-font-viewer/-/issues/5))
- [ ] [Dragging files from Ark on top of a folder in Dolphin copies the files into the parent folder.](https://youtu.be/TtsglXhbxno?t=499) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/8))
- [ ] [Compression appears to finish instantly when, in fact, it does not.](https://youtu.be/TtsglXhbxno?t=732) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/3))
- [x] [Ark creates a temp file with a weird extension when compressing.](https://youtu.be/TtsglXhbxno?t=732) ([Fixed](https://invent.kde.org/utilities/ark/-/merge_requests/79))
- [ ] [Ark doesn't prompt for filename when compressing multiple files](https://youtu.be/TtsglXhbxno?t=816) ([Open issue](https://invent.kde.org/teams/usability/issue-board/-/issues/10))
- [ ] [Right-click drag doesn't work in Dolphin.](https://youtu.be/TtsglXhbxno?t=1024)
  - **Possible fix:** Use left-click drag.
- [ ] [Fullscreen doesn't work in VLC media player.](https://youtu.be/TtsglXhbxno?t=1234)
  - **Workaround:** Set the rendering backend to OpenGL 3.1 (System Settings/Hardware/Display and Monitor/Compositor)
- [ ] [Window movement in Mint while a game is open is laggy.](https://youtu.be/TtsglXhbxno?t=1294) ([Open issue](https://github.com/linuxmint/Cinnamon/issues/2465))
- [ ] [obs-studio on Arch doesn't come installed with the Browser Source plugin.](https://youtu.be/TtsglXhbxno?t=1408)
  - **Possible fix:** Arch should package it with the Browser Source plugin. Until then, use the AUR.
- [ ] [Dolphin refuses to work as root.](https://youtu.be/TtsglXhbxno?t=1496) ([WIP fix](https://invent.kde.org/teams/usability/issue-board/-/issues/6))
  - **Workaround:** [Open Dolphin as root](https://store.kde.org/p/1384645/) service menu.
    - **For Arch:** [aur/root](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/22)

### WAN show

- [ ] [The "show desktop" button in KDE doesn't minimize all windows by default.](https://youtu.be/fJB9fdXWiiw?t=497)
  - **Possible fix:** Replace it with the "Minimize all Windows" applet ([#13](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/13)).
- [ ] [The application names don't represent the jobs of those applications (e.g. "Kate").](https://youtu.be/fJB9fdXWiiw?t=702)
  - **Possible fix:** Put the applications' descriptions in parentheses next to their names (e.g. "Kate (text editor)").
- [x] [Luke's system locks up when his TV turns on.](https://youtu.be/sS25mCLyQyk?t=416) ([Fixed](https://bugs.kde.org/show_bug.cgi?id=446699))

## Contributing

If you have a fix for one of these issues or you can describe it better than is described here, please [create an issue](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/new/choose) or submit a pull request. *Links to bug reports/merge requests are greatly appreciated!*
