# Boo for [SDDM](https://github.com/sddm/sddm/)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)[![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge)](https://aur.archlinux.org/packages/boo-sddm-git)

> A dark [SDDM](https://github.com/sddm/sddm/) theme based on Corners

![Screenshot](./assets/sddm.png)

## Installation

### AUR

For Arch users, the theme is available from the AUR [here](https://aur.archlinux.org/packages/boo-sddm-git).

1. Install it with your favorite AUR helper: `paru boo-sddm-git`

2. Follow steps 3. and 4. given below.

### Manually

#### Dependencies

- SDDM
- Qt Graphical Effects
- Qt SVG
- Qt Quick Controls 2

on Arch, simply run `pacman -Syu sddm qt5-graphicaleffects qt5-svg qt5-quickcontrols2`

1. Clone this repo or download the .zip

```bash
$ git clone https://github.com/PROxZIMA/boo-sddm.git
$ cd boo-sddm
```

2. Copy the whole `boo` directory to sddm themes

```bash
$ sudo cp -r boo /usr/share/sddm/themes
```

3. Edit sddm config file

```bash
$ sudo vim /etc/sddm.conf
```

Make the following changes

```conf
[Theme]
Current=boo
```

4. Reboot and voila

## Configuration

https://github.com/aczw/sddm-theme-corners#configuration

## Potential problems and solutions

Never had one but still refer to the following article.

https://wiki.archlinux.org/title/SDDM#Configuration

## Credits

- [Corners](https://github.com/aczw/sddm-theme-corners): Changes are made in the configuration file, logo, background, font and some UI tweaks.

## License

[GPLv3 License](LICENSE).
