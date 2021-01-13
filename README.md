# koji-theme-prolinux
ProLinux's koji theme, web interface for ProLinux Koji RPM build system.

## How to change koji theme
> Place static theme content under `/usr/share/koji-web/static/themes` directory

> Content under koji-static/theme/$NAME/ will be used instead of the normal
> files under koji-static/ if KojiTheme is set to $NAME. Any absent files
> will fall back to the normal koji-static/ path.

Clone repository to koji-web's theme directory
```shell
git clone https://github.com/sophalHong/koji-theme-prolinux.git /usr/share/koji-web/static/themes/prolinux-koji
```

Edit `/etc/kojiweb/web.conf`
```shell
KojiTheme = prolinux-koji
```
