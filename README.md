## ST - simple terminal (suckless) terminal

Nothing to see here. This is just my minimal build of [suckless terminal (st)](https://st.suckless.org/)

### Patches:
* [st-bold-is-not-bright](https://st.suckless.org/patches/bold-is-not-bright/)
* [st-boxdraw](https://st.suckless.org/patches/boxdraw/)
* [st-desktopentry](https://st.suckless.org/patches/desktopentry/)
* [st-glyph-wide-support](https://st.suckless.org/patches/glyph_wide_support/)
* [st-scrollback](https://st.suckless.org/patches/scrollback/)
* [st-w3m](https://st.suckless.org/patches/w3m/)
* [xresources](https://st.suckless.org/patches/xresources/)
* [patch_column](https://github.com/nimaipatel/st/blob/master/patches/7672445bab01cb4e861651dc540566ac22e25812.diff) This is golden one - it prevents cut text while resizing!)

## Installation
```
git clone https://github.com/bitterhalt/st
cd st
sudo make instalhttps://github.com/nimaipatel/st/blob/master/patches/7672445bab01cb4e861651dc540566ac22e25812.diffhttps://github.com/nimaipatel/st/blob/master/patches/7672445bab01cb4e861651dc540566ac22e25812.diff
```
### Keyboard Shortcuts
Action      | Key Combination
---         | ---
Copy        | `ctrl` + `shift` + `c`
Paste       | `ctrl` + `shift` + `v`
Zoom In     | `ctrl` + `+`
Zoom Out    | `ctrl` + `minus`
Reset Zoom  | `ctrl` + `0`
Scroll Up / Down      | `shift` + `PdgUp` / `PgDn`

### Theming
* This build of ST has xresources-patch, meaning you can manage colors, fonts etc. through your .Xresources -file
* You must run: ```xrdb -merge ~/.Xresources``` to apply colors
* If you want, you can copy contents of **example-xresources** to your **$HOME/.Xresources** and xrdb -merge it 


### Credits

* Forked from [https://st.suckless.org/](https://st.suckless.org/)
* Based on Aurélien APTEL aurelien.aptel@gmail.com bt source code.
* patch_column: https://github.com/nimaipatel/st/blob/master/patches/7672445bab01cb4e861651dc540566ac22e25812.diff  

 

