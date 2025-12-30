# Godot Beta (Arch Linux Repository)

This repository provides daily builds of the latest Godot Engine beta versions for Arch Linux.  
> Note: Since aur is deleting packages for no reason, i deploy my packages via github.

## Installation

To install packages from this repository, add the following to your `/etc/pacman.conf`:

```ini
[godot-beta]
SigLevel = Optional TrustAll
Server = https://freehuntx.github.io/godot-beta-aur/x86_64
```

Then update your database and install the package:

```bash
sudo pacman -Syu godot-beta-bin
```

## Package Details

- **godot-beta-bin**: The latest beta build of Godot Engine (repackaged from official GitHub releases).

## Updates

The repository is updated automatically via GitHub Actions whenever a new beta release is published by the Godot team.
