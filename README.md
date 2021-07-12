# Box86 Debian Repository

This is a simple Debian repository for the [box86](https://github.com/ptitSeb/box64) project, intended for my own personal use. New versions are compiled every 24 hours.

### Repository installation
Involves adding .list file and gpg key for added security.
```
sudo wget https://chunky-milk.github.io/box86-debs/box86.list -O /etc/apt/sources.list.d/box86.list
wget -qO- https://chunky-milk.github.io/box86-debs/KEY.gpg | sudo apt-key add -
sudo apt update && sudo apt install box86 -y
```

