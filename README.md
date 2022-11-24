# KDE 
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Pfeffimann18/KDE)
![GitHub repo size](https://img.shields.io/github/repo-size/Pfeffimann18/KDE)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/Pfeffimann18/KDE)
![GitHub](https://img.shields.io/github/license/Pfeffimann18/KDE)

## Initial Setup
Unter `Verhalten des Arbeitsbereiches` und `Arbeitsflächen-Effekte` aktiviert man Verwischen, Wabernde Fenster, Eltern-Fenster abdunkeln, Nach hinten gleiten, Übersicht und Wunderlampe auf 400ms. Unter `Fensterverwaltung` und `Fensterverhalten` stellt man unter `Erweitert` die Fensterpositionierung auf Zentriert. Den Ànwendungsumschalter stellt man wenn möglich auf Große Symbole, ansonsten auf Breeze. Unter `KWin-Scripte` läd man Force Blur, MACsimize, Latte Window Colors und Latte Launcher Menu herunter und aktiviert diese. Die `Benachrichtigungen` werden unten rechts angezeigt. Die `Skalierungsmethode` wird auf weich gestellt. Anschließedn wird Kvantum installiert.
```
sudo pacman -S kvantum
```
</br>

## Themen, Icons, Cursor und Fonts
Global Theme: Monterey - Vinceluice </br>
Anwendunsg-Stil: Kvantum, GTK: WhiteSur </br>
Startbildschirm: 1604 Arch Splash </br>

## Installing Ulauncher
copy Themes to ~/.config/ulauncher/user-themes

## Installing and Configuring Plasmoids Widgets
copy Widgets to ~/.local/share/Plasma
set filter to installed
```bash 
yay -S plasma5-applets-window-buttons
yay -S plasma5-applets-windos-appmenu
```

## Latte-Dock
```bash
sudo pacman -S latte-dock
```
enable autostart and support borderless maxsimised windows
import config file and remove old panels
füge `OnlyShownIn=KDE` in `~/.config/autostart/org.kde.latte-dock.desktop`

## Firefox
install Firefox-appmenu by Vinceluice

## Konsole
```bash
cp macOS.profile ~/.locale/share/konsole
cp purify.colorscheme ~/.locale/share/konsole


