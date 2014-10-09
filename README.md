chromebook-c720-touchpad
========================

ArchLinux PKGBUILD files for Chromebook C720 Touchpad Xorg driver module thingy

These are basically just some PKGBUILD files for a [ported version of xf86-input-cmt](https://github.com/hugegreenbug/xf86-input-cmt)

After installing copy `50-touchpad-cmt-peppy.conf` and `20-mouse.conf` from the `src`-directory to `/etc/X11/xorg.conf.d/`

This may work for other chromebooks, but I am only using this on a C720.
