# CFP's build of surf

## Applied patches:
- [bookmarking](https://surf.suckless.org/patches/bookmarking/)
- [cachedir](https://surf.suckless.org/patches/cachedir/)
- [clipboard instead of primary](https://surf.suckless.org/patches/clipboard-instead-of-primary/)
- [homepage](https://surf.suckless.org/patches/homepage/)
- [modal](https://surf.suckless.org/patches/modal/)
- [playexternal](https://surf.suckless.org/patches/playexternal/)
- [quit-hotkey](https://surf.suckless.org/patches/quit-hotkey/)
- [web search](https://surf.suckless.org/patches/web-search/)

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
