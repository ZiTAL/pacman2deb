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
aptitude safe-upgrade
```

command:
```
pacman -S iceweasel fluxbox
```

result:
```
aptitude install iceweasel fluxbox
```

command:
```
pacman -Scyu iceweasel fluxbox
```

result:
```
apt-get clean
apt-get update
aptitude safe-upgrade
aptitude install iceweasel fluxbox
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
aptitude remove fluxbox
```

command:
```
pacman -Rcs fluxbox
```

result:
```
aptitude purge fluxbox
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
GPL

