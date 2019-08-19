# gtk3-adwaita-compact-pkgbuild
Gtk3 patched to enable compact version of Adwaita theme. Currently only served as Arch Linux PKGBUILD

## Differences with original
There are no differences. But some widgets like headerbar, button, etc. paddings are reduced by changing `$_sizevariant` variable in `_common.scss` to `compact` 

### Instructions:
- Clone this repo
- Change directory `cd gtk3-adwaita-compact-pkgbuild`
- Run `makepkg -i`

### Credits
PKGBUILDs are based on [gtk3-typeahead](https://aur.archlinux.org/packages/gtk3-typeahead/) by twilinx
