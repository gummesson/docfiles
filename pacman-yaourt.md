# pacman-yaourt

[pacman](https://www.archlinux.org/pacman/) is a utility which manages software
packages in Linux.

[yaourt](https://archlinux.fr/yaourt-en) is a command line interface program
which completes [pacman](https://www.archlinux.org/pacman/) for installing
software on Arch Linux.

## Usage

### Update repositories and (AUR) packages

```
pacman -Syyu
yaourt -Syyua
```

### Remove a package, its configuration and unneeded dependencies

```
pacman -Rns
yaourt -Rns
```

### Delete old versions of (AUR) packages

```
pacman -Sc
yaourt -Sc
```
