### About

A simple SDDM theme inspired on FBSD SLiM theme.

### Preview!
![SDDM Gentoo Black Theme](https://github.com/lebarondemerde/sddm-gentoo-black-theme/blob/master/screenshot.png)

### Installation
```shell
git clone https://github.com/lebarondemerde/sddm-gentoo-black-theme.git
cp -R sddm-gentoo-black-theme /usr/share/sddm/themes
```

- Open up `/etc/sddm.conf` file and set `sddm-gentoo-black-theme` as your current theme.
```shell
[Theme]
# Current theme name
Current=sddm-gentoo-black-theme
```

### Configuration
- The theme uses the Liberation Sans font by default, but you can change it editing the `/usr/share/sddm/themes/sddm-gentoo-black-theme/theme.conf` file and setting the desired font in the `displayFont` variable.

```shell
[General]
background=background.png
displayFont="Liberation Sans"
```
