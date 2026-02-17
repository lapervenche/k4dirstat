# Vue d'ensemble
![Capture d'écran de l'interface k4dirstat, avec la 'vue arborescente' en haut et la 'carte d'arborescence' en bas](doc/screenshot.png)
Voir le [wiki](https://github.com/jeromerobert/k4dirstat/wiki/Overview).
# Compilation
Installez d'abord les en-têtes [Qt 5](http://www.qt.io) et [KDE Framework 5](https://www.kde.org). Sur Debian et ses dérivées, cela peut se faire avec :
```
apt-get install extra-cmake-modules qtbase5-dev libkf5coreaddons-dev \
 libkf5i18n-dev libkf5xmlgui-dev libkf5doctools-dev libkf5kio-dev
```
Puis lancez [cmake](http://www.cmake.org) :
    cmake -DCMAKE_INSTALL_PREFIX=/chemin/où/installer
    make install
