# Rtx arch repo

my arch repo that I use to easily install my custom build of suckless apps

## adding the repo
at the end of `/etc/pacman.conf` add
```
[rxt-arch-repo]
SigLevel = Optional DatabaseOptional
Server = https://raw.githubusercontent.com/rxt01/$repo/master/$arch
```
