# How to Patch
```shell
# install bin86 for as86 and ld86 first
# Ubuntu
sudo apt install bin86
# Archlinux
sudo pacman -S bin86

cd linux-0.11
patch -p1 < ../linux-0.11-SpaceYu.patch

# Complete
```
