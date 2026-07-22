# Why This Flatpak Fork Exists
This is a fork of [Simple64's Flathub release](https://github.com/flathub/io.github.simple64.simple64), and it was made for installing 2 copies of [Simple64](https://github.com/simple64) flatpak at once. That way the VRU can be left on for 2 games that support it. This is quick and dirty workaround with no support whatsoever, it was made with help from people in the linux community and the guidance of Gemini Ai.

# How to Install
1. Download the contents of this github.
2. Open the Terminal in the folder of the download.
3. Run this command to install it
* flatpak run org.flatpak.Builder --user --install --force-clean build-dir io.github.simple64.simple64.yaml

# How to Run It
1. Install it properly
2. If you want to run it directly from the terminal use this command.
* flatpak run io.github.simple64.simple64.vru

# How to Build it
1. Use this command for building it if youo need to make any modifications.
  * flatpak run org.flatpak.Builder --user --install-deps-from=flathub --force-clean build-dir io.github.simple64.simple64.yaml

# Other Notes
1. You can change the applications name and icon with your distro's built in menu editor or plenty other options like these.

Menu Editors
* Menu Editor (KDE Plasma)
* Pins: https://flathub.org/en/apps/io.github.fabrialberio.pinapp
* AppEditor: https://flathub.org/en/apps/com.github.donadigo.appeditor
* MenuLibre: https://github.com/bluesabre/menulibre
* Alacarte (Linux Mint): https://community.linuxmint.com/software/view/alacarte
* Meow: https://pnmougel.github.io/meow/
