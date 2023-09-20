## ST - simple terminal (suckless) terminal

Nothing to see here. This is just my minimal build of [suckless terminal (st)](https://st.suckless.org/)
This build is suppose to be small as possible.

I just add features that I need, so not much fancy stuff here, like alpha transparency and ligatures 😬

![228566814-72c9b01e-b34a-4218-8e6a-c838605d8483](https://user-images.githubusercontent.com/95308907/228569294-94fd2e60-589b-48eb-ad70-38c3e87a0abf.png)

![228566831-9479822f-ff3f-4e83-8c80-037f98b1c0cb](https://user-images.githubusercontent.com/95308907/228569325-7ce55d44-5eb1-4c14-a049-da975f68baae.png)

### Patches:
* [st-bold-is-not-bright](https://st.suckless.org/patches/bold-is-not-bright/)
* [st-boxdraw](https://st.suckless.org/patches/boxdraw/)
* [st-desktopentry](https://st.suckless.org/patches/desktopentry/)
* [st-glyph-wide-support](https://st.suckless.org/patches/glyph_wide_support/)
* [st-scrollback](https://st.suckless.org/patches/scrollback/)
* [xresources](https://st.suckless.org/patches/xresources/)

## Installation
```
git clone https://github.com/bitterhalt/st
cd st
sudo make instal
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
* Default (fallback) theme is Gruvbox Dark
* This build of ST has xresources-patch, meaning you can manage colors, fonts etc. through your .Xresources -file
* You must run: ```xrdb -merge ~/.Xresources``` to apply colors
* If you want, you can copy contents of **example-xresources** to your **$HOME/.Xresources** and xrdb -merge it 

### Credits

* Forked from [https://st.suckless.org/](https://st.suckless.org/)
* Based on Aurélien APTEL aurelien.aptel@gmail.com bt source code.
* patch_column: https://github.com/nimaipatel/st/blob/master/patches/7672445bab01cb4e861651dc540566ac22e25812.diff  
