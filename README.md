# Modified version of Fawzan's dwm

# Description
dwm is a tilling window manager for X server made by people on ([Suckless](https://suckless.org)). 
It is known for its small size, fast performance, and superb customizability options (by directly editing its source file). 


### Hard Dependencies:
You need these for dwm to run or behave as intended:
+ xorg (xorg-server, libx11, libxinerama, libxft, libxcb-res0, libc6)
+ [st](https://gitlab.com/fawzakin/st) (terminal)
+ [dmenu](https://gitlab.com/fawzakin/dmenu) (run launcher and logout menu)

### Soft Dependencies:
You can choose not to install the following but you won't be able to use dwm to the fullest:
+ amixer from alsa-utils (for changing volume)
+ [dmscripts](https://gitlab.com/dwt1/dmscripts) ([my fork](https://gitlab.com/fawzadin/dmscripts) is recommended)
+ flameshot (for taking screenshots)
+ lxsession (for running certain GUI application that requires sudo)
+ lxappearance (for changing your system themes)
+ picom (for compositor and prevent screen tearing)
+ yad and xclip (for displaying and copying window class with `Mod+Insert`)

### List of applied patches:
From [dwm website](https://dwm.suckless.org/patches/):
+ actualfullscreen
+ alternativetags
+ alwayscenter
+ attachsideandbellow
+ autostart
+ cfacts (vanitygaps combo)
+ cyclelayouts
+ focusmaster
+ focusonclick
+ focusurgent
+ noborder (floatingfix)
+ pertag
+ restartsig
+ scratchpads
+ status2d (xrdb)
+ swallow
+ systray
+ vanitygaps
+ warp
+ xresources
+ zoomswap

From [bakkeby](https://github.com/bakkeby/patches/tree/master/dwm):
+ focusdir
+ placedir

From [siduck76](https://github.com/siduck76/chadwm):
+ barborder
+ underlinetags

From [Quentin Franchi](https://gitlab.com/dev.quentinfranchi/dwm):
+ [systray icon size](https://gitlab.com/-/snippets/2184056)
