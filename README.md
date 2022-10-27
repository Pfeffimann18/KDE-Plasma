# KDE 

## Initial Setup
Workspace Behavior -> Desktop Effects
Blur, Wobbly Windows, Magic Lamp (400ms), Dim Screen for Admin Mode, Slide Back, Overview on

Window Managment -> Windows Behavior -> Advanced -> Window Placement: Centered
Task Switcher -> Large Icons
KWin Scripts -> Force Blur, MACsimize, Latte Windows Colors, Latte launcher
Notifications -> Bottom Right
Compositor MEthode -> Smooth, OpenGL 3.0
```
sudo pacman -S kvantum
```

## Installing and Configuring KDE Plasma Tehem, Icons, Cursor and Fonts
Global Theme: Monterey - Vinceluice
Applications Style: Colloid gtk
rename .themes/colloid to colloid-01 and download colloid-dark

## Apply themes
download Wallpaper plugin Inactive Blur
setup kvantum Theme and Title Behavior
sddm theme by Vinceluice

## Installing Ulauncher
copy Themes to ~/.config/ulauncher/user-themes

## Installing and Configuring Plasmoids Widgets
copy Widgets to ~/.local/share/Plasma
set filter to installed
```
yay -S plasma5-applets-windows-buttons
yay -S plasma5-applets-wind-appmenu
```

## Latte-Dock
sudo pacman -S latte-dock
enable autostart and support borderless mximised windows
import config file and remove old panels

## Firefox
install Firefox-appmenu by Vinceluice

