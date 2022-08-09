# CFP's build of surf

## Applied patches:
- [bookmarks](https://surf.suckless.org/patches/bookmarks/)
- [cachedir](https://surf.suckless.org/patches/cachedir/)
- [clipboard](https://surf.suckless.org/patches/clipboard/)
- [homepage](https://surf.suckless.org/patches/homepage/)
- [modal](https://surf.suckless.org/patches/modal/)
- [playexternal](https://surf.suckless.org/patches/playexternal/)
- [quit-hotkey](https://surf.suckless.org/patches/quit-hotkey/)
- [websearch](https://surf.suckless.org/patches/websearch/)

## Requirements:
gcr, webkit2gtk. On Arch-based systems:

```bash
# pacman -S gcr webkit2gtk
```

## Installation:
Edit config.mk and config.h and run:

```bash
# make clean install
```
