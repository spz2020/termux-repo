# termux-repo
install key
```
wget -qO- https://spz2020.github.io/termux-repo/key.gpg | gpg --dearmor -o $PREFIX/etc/apt/trusted.gpg.d/spz2020.gpg 
```
nano $PREFIX/etc/apt/sources.list.d/spz2020.list
```
deb https://spz2020.github.io/termux-repo termux spz2020
```
