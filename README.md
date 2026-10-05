# Tenslo Code releases

Builds of [Tenslo Code](https://github.com/tenslo/tenslo-code), a calm workspace for running coding
agents in parallel on git worktrees, with real terminals and its own editor. This repo holds only
release tags, notes and installers. The app's source stays private.

## Download

Take the files from the [latest release](../../releases/latest).

| System | File | Notes |
| --- | --- | --- |
| macOS, Apple silicon | `Tenslo Code-<version>-arm64.dmg` | Signed and notarized. Open the disk image and drag the app to Applications. |
| Windows 11, x64 | `Tenslo-Code-Setup-<version>-x64.exe` | Installs for your user without an administrator prompt. Not code signed yet, so SmartScreen warns once per version: choose More info, then Run anyway. |

Projects can live on Windows itself and in any WSL 2 distro. The app installs what a distro needs
the first time you open a project there.

The `linux-runtime-<version>-x64` and `-arm64` archives are not installers. The app downloads its
own version of them the first time you connect to a Linux machine over SSH.

## Updates

Installed copies check this repo for updates automatically and offer to restart once a new version
is downloaded. Nothing else is needed.

## Changes

Each release lists what changed in its notes.
