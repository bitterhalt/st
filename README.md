## ST - simple terminal (suckless) terminal

Nothing to see here. This is just my minimal build of [suckless terminal (st)](https://st.suckless.org/)

### Patches:
* st-bold-is-not-bright
* st-desktopentry
* st-glyph-wide-support
* st-scrollback
* st-w3m
* xresources

## Installation
```
git clone https://github.com/bitterhalt/st
cd st
sudo make install
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


