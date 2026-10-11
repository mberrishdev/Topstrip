<div align="center">

# Topstrip

**An [Omarchy](https://omarchy.org/manual/the-top-bar/)-style top bar for Windows.**

Workspaces, a centered clock, your tray apps and system status in one thin strip across the top of the screen.

[**Download**](https://github.com/mberrishdev/Topstrip/releases/latest) · [Report a bug](https://github.com/mberrishdev/Topstrip/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/mberrishdev/Topstrip/issues/new?template=feature_request.yml)

![Topstrip with the Tokyo Night theme and the tray drawer open](docs/images/hero.png)

</div>

## Features

- **Workspaces 1–5:** your Windows virtual desktops. Click a number to switch; Topstrip creates the desktop if it doesn't exist yet.
- **Centered clock:** click for notifications and calendar, right-click to change the format.
- **Tray drawer:** hover the `‹` to reveal the apps that normally sit next to the Windows clock (Discord, Steam, OneDrive…). Left-, right- and middle-click them as usual.
- **Status:** Bluetooth, Wi-Fi signal, volume and battery.
- **Real space reservation:** maximized windows stop below the bar, just like they stop above the taskbar.
- **11 themes:** Tokyo Night, Catppuccin, Catppuccin Latte, Everforest, Gruvbox, Kanagawa, Matte Black, Nord, Osaka Jade, Ristretto and Rosé Pine.

![All themes](docs/images/themes.png)

## Install

1. Download `Topstrip.exe` from the [latest release](https://github.com/mberrishdev/Topstrip/releases/latest).
2. Run it. Nothing else to install.
3. Optional: in the Topstrip menu, turn on **Open at Login**.

Windows SmartScreen may warn about an unrecognized app the first time, because the exe isn't code-signed yet. Choose **More info → Run anyway**.

**Requirements:** Windows 10 or 11, 64-bit.

For the exact Omarchy look, install a [Nerd Font](https://www.nerdfonts.com/) such as *JetBrainsMono Nerd Font*. Otherwise Topstrip uses Cascadia Mono or Consolas.

## Using it

| Widget | Left click | Right click | Other |
|---|---|---|---|
| Menu (logo) | Menu: settings, apps, theme, transparency, open at login, lock, restart, shut down | Open a terminal | |
| Workspaces | Switch to that desktop | | |
| Clock | Notifications & calendar | Change format | |
| Tray `‹` | | | Hover to show tray apps |
| Bluetooth | Bluetooth settings | Turn on / off | |
| Network | Wi-Fi list | | Icon shows signal strength |
| Audio | Sound settings | Mute | Scroll to change volume |
| Power | Power settings | Show battery % | |

Double-click an empty part of the bar to toggle transparency.

Settings are stored in `%APPDATA%\Topstrip\settings.json`.

## FAQ

**Does it replace the Windows taskbar?**
No. The taskbar keeps working; Topstrip sits at the top. Many people set the taskbar to auto-hide.

**The Wi-Fi name doesn't show.**
On Windows 11 24H2 and later, apps need location access to read the network name. Signal strength works either way.

**How do I uninstall it?**
Choose **Quit Topstrip** from the menu, turn off **Open at Login** first if you enabled it, then delete `Topstrip.exe` and `%APPDATA%\Topstrip`.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/mberrishdev/Topstrip/issues/new/choose).

## Credits

Inspired by [Omarchy](https://omarchy.org)'s top bar. Tray support is ported from [Zebar](https://github.com/glzr-io/zebar)'s systray-util. See [third-party notices](THIRD-PARTY-NOTICES.md).
