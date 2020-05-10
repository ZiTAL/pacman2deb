pacman2deb
==========

Archlinux pacman commands for debian

command:
```
pacman -Scyu
```

result:
```
apt-get clean
apt-get update
apt-get upgrade
```

command:
```
pacman -S firefox fluxbox
```

result:
```
apt-get install firefox fluxbox
```

command:
```
pacman -Scyu firefox fluxbox
```

result:
```
apt-get clean
apt-get update
apt-get upgrade
apt-get install firefox fluxbox
```

command:
```
pacman -R fluxbox
```

result:
```
dpkg -r --force-depends fluxbox
```

command:
```
pacman -Rs fluxbox
```

result:
```
apt-get remove fluxbox
```

command:
```
pacman -Rcs fluxbox
```

result:
```
apt-get remove --purge fluxbox
```

command:
```
pacman -Qi fluxbox
```

result:
```
dpkg -S fluxbox
```

command:
```
pacman -Qs fluxbox
```

result:
```
dpkg -l | grep fluxbox
```

command:
```
pacman -Ss fluxbox
```

result:
```
apt-cache search fluxbox
```

LICENSE
=======
GPLv3

