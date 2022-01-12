# XFCE_THEMES
Some window panel themes for XFCE.

Looking for themes online for a FreeBSD install I stumbled across [this website](https://www.ubuntupit.com/best-xfce-themes-for-linux/) titled "Top 20 Best Xfce Themes".

This is where I discovered the Hitori and Dots window panel themes. Although I was not _that_ impressed by them, the Dots theme removed the application icon from the window panel and the Hitori theme was more blue than black.

#### So I made some variations where I combined the two:
- [`HitoriDots1`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots1/xfwm4) This is the regular Dots Black theme but with the Hitori `menu-active.png` so that the application icon is now displayed and at a regular scale.
- [`HitoriDots2`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots2/xfwm4) This is the regular Dots Black theme but with an easier on the eye colour pallet that more resembels the original Hitori theme.
- [`HitoriDots3`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots3/xfwm4) This is HitoriDots1 but the window panel buttons only light up when hovered over.
- [`HitoriDots4`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots4/xfwm4) This is HitoriDots3 but now the buttons also have small graphics indicators when they light up.

_The original themes are included in the repsitory for comparison and reference._

#### Licensing:
Since both Hitori and Dots themes had been released as "GPLv2 or later" on xfce-look.org. Although I have since noticed Dots Black specifies "GPL-3.0+" in the [`themerc`](https://github.com/mrbid/XFCE_THEMES/blob/main/Dots%20Black/xfwm4/themerc) file. Technically all of the image assets are from the Dots theme and the `menu-active.png` taken from Hitori is so basic and only retains its original image dimensions and not colour shade... The license should continue as the Dots licence [`GPL-3.0+`](https://www.gnu.org/licenses/gpl-3.0.html). The themerc is also taken from the Hitori theme but again this is just a basic configuration file.

#### Notes:
- Alternatively [Numix](https://www.xfce-look.org/p/1013541/)[[2](https://github.com/numixproject/numix-gtk-theme/tree/master/src)] window panel theme is also pretty good.
- When it comes to Desktop Icon and Appearance themes, I really like the [elementary-xfce-darker](https://github.com/shimmerproject/elementary-xfce/) icons and the [Greybird-dark](https://github.com/shimmerproject/Greybird) appearance.
- [Trimage](https://trimage.org/) was used to compress the PNG files to something more suitable in size.

## Installation
Copy these themes into either: `~/.local/share/themes/` or `/usr/share/themes/`<br>
e.g: `~/.local/share/themes/HitoriDots4`

Or for desktop icon packs: `~/.local/share/icons/` or `/usr/share/icons/`

Then you can use the Window Manager [`xfwm4-settings`](https://docs.xfce.org/xfce/xfwm4/preferences) application to select between themes or the Appearance [`xfce4-appearance-settings`](https://docs.xfce.org/xfce/xfce4-settings/appearance) application to select between desktop icons and appearances.

## Button Layout
By default the window panel buttons are left aligned in the respective `themerc` file: `#button_layout=CHM|O`<br>
however some people may prefer right aligned: `#button_layout=O|HMC`
