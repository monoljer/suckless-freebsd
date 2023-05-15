# Custom prepatched Suckless ST (0.8.5) for FreeBSD 13.2

## Patches

* alpha
* anysize
* blinking cursor
* boxdraw
* ligatures
* scrollback


## Dependencies

### HarfBuzz

Install from /usr/ports/print/harfbuzz

### Nerdfonts (Inconsolata LGC Nerd Font)

## Instalation

doas git clone https://git.suckless.org/st
cd st
doas patch < st-freebsd-0.1.diff
doas make install


