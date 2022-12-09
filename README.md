# README

## How to build stable aur package

- clone the AUR git project with PKGBUILD from aur site and put it in a folder
- go into folder with PKGBUILD build package: **makepkg -s** (-> generate package)
- install package: **pacman -U generated_package.tar.xz**
