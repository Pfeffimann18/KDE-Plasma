# KDE 

## Initial Setup
Unter `Verhalten des Arbeitsbereiches` und `Arbeitsflächen-Effekte` aktiviert man Verwischen, Wabernde Fenster, Eltern-Fenster abdunkeln, Nach hinten gleiten, Übersicht und Wunderlampe auf 400ms. Unter `Fensterverwaltung` und `Fensterverhalten` stellt man unter `Erweitert` die Fensterpositionierung auf Zentriert. Den Ànwendungsumschalter stellt man wenn möglich auf Große Symbole, ansonsten auf Breeze. Unter `KWin-Scripte` läd man Force Blur, MACsimize, Latte Window Colors und Latte Launcher Menu herunter und aktiviert diese. Die `Benachrichtigungen` werden unten rechts angezeigt. Die `Skalierungsmethode` wird auf weich gestellt. Anschließedn wird Kvantum installiert.
```
sudo pacman -S kvantum
```
</br>

## Themen, Icons, Cursor und Fonts
Global Theme: Monterey - Vinceluice
Applications Style: Colloid gtk
rename .themes/colloid to colloid-01 and download colloid-dark



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

