# termux-repo
install key
```
apt install wget gnupg
wget -qO- https://spz2020.github.io/termux-repo/key.gpg | gpg --dearmor -o $PREFIX/etc/apt/trusted.gpg.d/spz2020.gpg
mkdir $PREFIX/etc/apt/sources.list.d
nano $PREFIX/etc/apt/sources.list.d/spz2020.list
```
```

deb https://spz2020.github.io/termux-repo termux spz2020
```
