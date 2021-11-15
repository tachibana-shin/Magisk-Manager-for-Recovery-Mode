# Magisk Manager for Recovery Mode (mm)
<p align="left">
    <a href="https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode/releases">
        <img src="https://img.shields.io/github/downloads/Rikj000/Magisk-Manager-for-Recovery-Mode/total?label=Total%20Downloads&logo=github" alt="Total Releases Downloaded from GitHub">
    </a> <a href="https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode/releases/latest">
        <img src="https://img.shields.io/github/v/release/Rikj000/Magisk-Manager-for-Recovery-Mode?include_prereleases&label=Latest%20Release&logo=github" alt="Latest Official Release on GitHub">
    </a> <a href="https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode/blob/master/License.md">
        <img src="https://img.shields.io/github/license/Rikj000/Magisk-Manager-for-Recovery-Mode?label=License&logo=gnu" alt="GNU General Public License">
    </a> <a href="https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode#magisk-manager-for-recovery-mode-mm">
        <img src="https://img.shields.io/badge/Docs-mm-blue?logo=libreoffice&logoColor=white" alt="The current place where you can find all Magisk Manager for Recovery Mode (mm) Documentation!">
    </a><a href="https://www.iconomi.com/register?ref=JdFzz">
        <img src="https://img.shields.io/badge/Join-ICONOMI-blue?logo=bitcoin&logoColor=white" alt="ICONOMI - The world’s largest crypto strategy provider">
    </a> <a href="https://www.buymeacoffee.com/Rikj000">
        <img src="https://img.shields.io/badge/-Buy%20me%20a%20Coffee!-FFDD00?logo=buy-me-a-coffee&logoColor=black" alt="Buy me a Coffee as a way to sponsor this project!">
    </a>
</p>

## LEGAL

Copyright (C) 2017-2021, VR25 & Rikj000 @ xda-developers

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.



## DISCLAIMER

Always read/reread this reference prior to installing/upgrading this software.

While no cats have been harmed, the author assumes no responsibility for anything that might break due to the use/misuse of it.

To prevent fraud, do NOT mirror any link associated with this project; do NOT share builds (zips)! Share official links instead.



## DESCRIPTION

- Manage your Magisk modules from recovery (e.g., TWRP) -- run "sh /sdcard/mm" on recovery terminal.

Features list
- Automatically fix magisk.img (e2fsck -fy)
- List installed modules
- Toggle
  - Core only mode
  - Magic mount
  - Disable
  - Remove



## PREREQUISITE

- Magisk v19.X - v23.X



## SETUP

- Install
1. Flash live (e.g., from Magisk Manager) or from custom recovery (e.g., TWRP).

- Uninstall
- Use Magisk Manager app or mm itself (supports `uninstall.sh`, too).



## USAGE
- Store & save the MagiskManagerForRecovery_vX_XXXXXXXXX.zip file somewhere on your phone's internal storage (not on SD or external)
- Boot into TWRP
- Install the MagiskManagerForRecovery_vX_XXXXXXXXX.zip
- Open up the Terminal window in TWRP & run the `mm` command to start managing your modules
- Follow the instructions/wizard. Everything is interactive.



## LINKS

- [New Git repository](https://github.com/Rikj000/mm)
- [Old Git repository](https://github.com/Magisk-Modules-Repo/mm)
- [Original XDA thread](https://forum.xda-developers.com/apps/magisk/module-tool-magisk-manager-recovery-mode-t3693165)
- [VR25 Donate](https://paypal.me/vr25xda/)
- [VR25 Facebook page](https://facebook.com/VR25-at-xda-developers-258150974794782/)

## LATEST CHANGES
**2021.6.6 (202106060)**
- Updated [README.md](https://github.com/Rikj000/mm/) since still confirmed working on **Magisk v23.X**

**2020.4.17 (202004170)**
- **Magisk v19.X - v20.X** support

**2019.4.4 (201904040)**
- Complete redesign
- **Magisk v17-19** support (including `uninstall.sh`)
- Toggle core only mode
- Updated information (copyright, documentation, and module description)

**2018.8.1 (201808010)**
- General optimizations
- New & simplified installer
- Striped down (removed unnecessary code & files)
- Updated documentation

**2018.7.24 (201807240)**
- Fixed modPath detection issue on **Magisk v16.6**.
- Updated documentation
