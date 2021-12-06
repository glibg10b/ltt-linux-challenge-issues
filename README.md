# LTT Linux daily driver challenge issues

A list of issues Linus and Luke experienced during the LTT Linux Daily Driver Challenge. 

## The issues

Note: Some of these may be subjective, and some may have been fixed without my knowledge.

### [Part 1](https://www.youtube.com/watch?v=0506yDSgU7M)

- [ ] [Searching "Best Linux distro for gaming" on Google brings up really bad websites.](https://www.youtube.com/watch?v=0506yDSgU7M&t=67s)
  - **Possible fix:** Make some good lists and use SEO to get them to show first.
- [ ] [The Mint USB behaved strangely with Luke's monitors the first time.](https://youtu.be/0506yDSgU7M?t=398)
- [ ] [Mouse acceleration is on by default.](https://youtu.be/0506yDSgU7M?t=541)
  - **Possible fix:** Turn it off by default.
- [ ] [GoXLR acts as an input when configured as an output device.](https://youtu.be/0506yDSgU7M?t=552)
- [ ] [Pop!\_OS doesn't have a noob-friendly way of checking what hardware is connected and whether the drivers work.](https://youtu.be/0506yDSgU7M?t=579)
  - **Possible fix:** Make it ship with Hardinfo installed.
- [x] [Installing Steam uninstalls essential packages and it isn't clear that this is bad.](https://youtu.be/0506yDSgU7M?t=607) ([Fix](https://github.com/pop-os/apt/pull/1)) 
- [ ] [USB errors on boot.](https://youtu.be/0506yDSgU7M?t=870)
  - **Possible fix:** https://www.spinics.net/lists/usb/msg02644.html
- [ ] [Installing Steam from Mint Software Manager shows "Removing...".](https://youtu.be/0506yDSgU7M?t=921)
- [ ] [Linus doesn't like KDE Plasma's settings design.](https://youtu.be/0506yDSgU7M?t=982)
- [ ] [The check boxes under "Hardware Configuration" look like radio buttons.](https://youtu.be/0506yDSgU7M?t=991)
- [ ] [Cave Story+ looks weird.](https://youtu.be/0506yDSgU7M?t=1101)

### [Part 2](https://youtu.be/3E8IGy6I9Wo)

- [ ] [Using apt or apt-get on Manjaro doesn't warn you that you're using the wrong package manager.](https://youtu.be/3E8IGy6I9Wo?t=107)
  - **Possible fix:** Maybe command-not-found can show a warning for it? Or [#10](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/10).
- [ ] [NVIDIA X Server Settings is lacking.](https://youtu.be/3E8IGy6I9Wo?t=183)
- [ ] [OBS requires a restart (or something) for some things to work correctly, but doesn't say so.](https://youtu.be/3E8IGy6I9Wo?t=224)
- [ ] [The option to show Snap, Flatpak, and AUR packages in Pamac is "hidden".](https://youtu.be/3E8IGy6I9Wo?t=540)
- [x] [Scrolling with the mouse wheel in KDE's volume mixer applet scrolls through both devices and levels of devices.](https://youtu.be/3E8IGy6I9Wo?t=573) (Link wanted)

### [Part 3](https://youtu.be/TtsglXhbxno)

- [ ] [The "Moving" Dolphin notification is easy to miss on a large screen.](https://youtu.be/TtsglXhbxno?t=163)
  - **Possible fix:** Hide the file (dot prefix) until it's done moving.
- [ ] [Okular's dialog about "no available signing certificates" refers to a manual, which Linus completely ignored for some reason.](https://youtu.be/TtsglXhbxno?t=281)
- [ ] [LibreOffice Calc didn't export the bottom and right edges of a chart.](https://youtu.be/TtsglXhbxno?t=440) [Sgt-Miller](https://github.com/Sgt-Miller) says it did for them.
- [ ] [You can't drag a folder of fonts onto Linux Mint's font previewer to install them.](https://youtu.be/TtsglXhbxno?t=455)
- [ ] [Something about Ark?](https://youtu.be/TtsglXhbxno?t=499)
- [ ] [Compression appears to finish instantly when, in fact, it does not.](https://youtu.be/TtsglXhbxno?t=732)
  - **Possible fix:** Hide the archive (dot prefix) until it's done compressing.
- [ ] [Right-click drag doesn't work in Dolphin.](https://youtu.be/TtsglXhbxno?t=1024)
  - **Possible fix:** Use left-click drag.
- [ ] [Fullscreen doesn't work in MPlayer.](https://youtu.be/TtsglXhbxno?t=1234)
- [ ] [Window movement in Mint while a game is open is laggy.](https://youtu.be/TtsglXhbxno?t=1294)
  - **Bug report:** https://github.com/linuxmint/Cinnamon/issues/2465
- [ ] [Dolphin refuses to work as root.](https://youtu.be/TtsglXhbxno?t=1496)
  - **Possible fix:** [Open Dolphin as root](https://store.kde.org/p/1384645/) service menu.

### WAN show

- [ ] [The "show desktop" button in KDE doesn't minimize all windows by default.](https://youtu.be/fJB9fdXWiiw?t=497)
  - **Possible fix:** Replace it with the "Minimize all Windows" applet.
- [ ] [The application names don't represent the jobs of those applications (e.g. "Kate").](https://youtu.be/fJB9fdXWiiw?t=702)
  - **Possible fix:** Put the applications' descriptions in parentheses next to their names (e.g. "Kate (text editor)").
- [ ] [Luke's system locks up when his TV turns on.](https://youtu.be/sS25mCLyQyk?t=416)

## Some other suggestions for developers based on this challenge

- [ ] [Sgt-Miller](https://github.com/Sgt-Miller)
  > If Fastboot is turned on in Windows, the partition is mounted as read-only in Ubuntu. When copying, the error message says "no permission". Please make the error message more descriptive, like for NTFS systems it can say "It was mounted in read-only mode. To write to disk, ensure fast boot is disabled.
- [ ] [Sgt-Miller](https://github.com/Sgt-Miller)
  > Please turn on "Create link" option in Nautilus by default. Or provide creating shortcut by drag+ctrl+shift.
- [ ] [Sgt-Miller](https://github.com/Sgt-Miller)
  > I think gnome-tweaks should be installed by default. User shouldn't have to install an extra tool to change system fonts and to create startup programs.

## Contributing

If you have a fix for one of these issues or you can describe it better than is described here, please [create an issue](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/new/choose) or submit a pull request.

## Other users' experience

- [#1](https://github.com/glibg10b/ltt-linux-challenge-issues/issues/1)
