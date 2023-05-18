# Custom (prepatched) Suckless software for FreeBSD

## Components

### ST

**Patches**

* alpha
* anysize
* blinking cursor
* boxdraw
* ligatures
* scrollback

**Dependencies**

* HarfBuzz (Install from /usr/ports/print/harfbuzz)
* Nerdfonts (Inconsolata LGC Nerd Font)


### SLOCK

**Patches**

* dwmlogoandblurscreen
* capscolor
* user
* dpms

**Dependencies**

TBD

### DWM

**Patches**

* attachaside
* exitmenu
* vanitygaps
* alpha

**Dependencies**

TBD

## General installation

doas git clone https://git.suckless.org/**[tool]
cd [tool]
doas patch < [tool]-freebsd-0.1.diff
doas make install





