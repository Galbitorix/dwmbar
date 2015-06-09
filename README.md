# dwmbar

A personal status bar for DWM

## Installation

Clone the repository

```git clone git://github.com/Galbitorix/dwmbar.git```

Battery/network/spotify still being worked on

Now `make`, `sudo make install` and run `dwmbar`.

What needs to be done -> need to add colors

note: needs Ohsnap font from aur to work with unicode

to get unicode icons to work:
run -> #fc-cache -fs && mkfontscale /usr/share/fonts/local && mkfontdir /usr/share/fonts/local
add to .xinitrc -> xset +fp /usr/share/fonts/local
xset fp rehash

execute by default in .xinitrc with -> exec dwmbar
# dwmbar
# dwmbar
