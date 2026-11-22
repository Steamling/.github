<p align="center">
  <img src="assets/steamling-social.png" alt="Steamling: a little red dragon absorbed in his handheld, beside the steamling wordmark" width="760">
</p>

<h3 align="center">A SteamOS-style gaming system for Snapdragon handhelds, built on Arch Linux ARM</h3>

<p align="center">Turn it on, land in Steam, pick a game and play.</p>

<p align="center">
  <a href="https://sourceforge.net/projects/steamling/files/latest/download"><b>Download</b></a> ·
  <a href="https://github.com/Steamling/steamling/blob/main/docs/install.md"><b>Install</b></a> ·
  <a href="https://github.com/Steamling/steamling/blob/main/docs/README.md"><b>Docs</b></a> ·
  <a href="https://github.com/Steamling/steamling/releases"><b>Releases</b></a>
</p>

Steamling brings the Steam Deck experience to ARM handhelds. You boot straight into Steam's gaming
mode, Proton is picked for you, and Windows games run through FEX. Underneath it's a normal Arch
Linux ARM system, so you can drop into a desktop, install Flatpaks, or open a terminal whenever
you like.

> [!WARNING]
> Steamling is new and experimental. Installing it means replacing your handheld's bootloader, so
> read the [install guide](https://github.com/Steamling/steamling/blob/main/docs/install.md) first.

## Get it

1. [Download the latest image](https://sourceforge.net/projects/steamling/files/latest/download)
   for the Snapdragon 8 Gen 2 handhelds, the Retroid Pocket 6 and others. Other chips can
   [build their own](https://github.com/Steamling/steamling/blob/main/docs/building/README.md).
2. Follow the [install guide](https://github.com/Steamling/steamling/blob/main/docs/install.md):
   flash the card, install the bootloader, boot.
3. After that, updates arrive over the internet from **Governor → System**. There's no need to
   reflash for a new release.

The **Retroid Pocket 6** is the reference device. Retroid, AYN, AYANEO, MANGMI and KONKR handhelds
on the Snapdragon 865, 8 Gen 2, 8 Gen 3 and 8 Elite are supported as untested ports:
[Supported devices](https://github.com/Steamling/steamling/blob/main/docs/devices.md) has the full
list, and how to help test one.

## The repos

| Repo | What's in it |
| --- | --- |
| [steamling](https://github.com/Steamling/steamling) | Everything Steamling is made of: the build, the kernel and packages, the docs, and the SD images on its Releases page |
| [packages](https://github.com/Steamling/packages) | The package repos handhelds update from: Steamling's own kernel, Mesa, gamescope, Governor and the rest |
| [base](https://github.com/Steamling/base) | The frozen snapshot of Arch Linux ARM every build and handheld installs from |

## Get involved

- Found a bug, or something that doesn't work on your handheld? Open an
  [issue](https://github.com/Steamling/steamling/issues), and check
  [Known issues](https://github.com/Steamling/steamling/blob/main/docs/known-issues.md) first.
- Own one of the untested handhelds? Trying Steamling on it and reporting back is the most useful
  thing you can do right now.
- Want to change something? [CONTRIBUTING.md](https://github.com/Steamling/steamling/blob/main/CONTRIBUTING.md)
  explains how to build, test on a device and send a pull request.

## Thanks

Steamling stands on a lot of other people's work: Pocknix, ROCKNIX, armada, PortareOS, Valve's
SteamOS and Steam Frame sources, Arch Linux ARM and many more.
[About Steamling](https://github.com/Steamling/steamling/blob/main/docs/about.md) names them all.
Steamling's own code is [GPL-2.0-or-later](https://github.com/Steamling/steamling/blob/main/LICENSE.md).
