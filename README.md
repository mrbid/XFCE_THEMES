# XFCE_THEMES
Some window panel themes for XFCE.

Looking for themes online for a FreeBSD install I stumbled across [this](https://www.ubuntupit.com/best-xfce-themes-for-linux/) website titled "Top 20 Best Xfce Themes".

This is where I discovered the Hitori and Dots window panel themes. Although I was not _that_ impressed by them, the Dots theme removed the application icon from the window panel and the Hitori theme was more blue than black.

So I made some variations where I combined the two:

- [`HitoriDots1`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots1/xfwm4) This is the regular Dots Black theme but with the Hitori `menu-active.png` so that the application icon is now displayed.
- [`HitoriDots2`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots2/xfwm4) This is the regular Dots Black theme but with an easier on the eye colour pallet that more resembels the original Hitori theme.
- [`HitoriDots3`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots3/xfwm4) This is HitoriDots1 but the window panel buttons only light up when hovered over.
- [`HitoriDots4`](https://github.com/mrbid/XFCE_THEMES/tree/main/HitoriDots4/xfwm4) This is HitoriDots3 but now the buttons also have small graphics indicators when they light up.

The original themes are included in the repsitory for comparison and reference. Since both Hitori and Dots themes had been released as "GPLv2 or later" that is the same licence used for these modifications.

When it comes to Desktop Icon and Appearance themes, I really like the [elementary-xfce-darker](https://github.com/shimmerproject/elementary-xfce/) icons and the [Greybird-dark](https://github.com/shimmerproject/Greybird) appearance. Configurable from the Appearance [`xfce4-appearance-settings`](https://docs.xfce.org/xfce/xfce4-settings/appearance) application.

Alternatively [Numix](https://www.xfce-look.org/p/1013541/) is also pretty good.

[Trimage](https://trimage.org/) was used to compress the PNG files to something more suitable in size.

## Installation
Copy these themes into either: `~/.local/share/themes/` or `/usr/share/themes/`<br>
e.g: `~/.local/share/themes/HitoriDots4`

Then you can use the Window Manager [`xfwm4-settings`](https://docs.xfce.org/xfce/xfwm4/preferences) application to select between themes.
