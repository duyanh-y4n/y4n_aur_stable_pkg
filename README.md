# README

## How to build stable aur package

- download PKGBUILD from aur and put it in a folder
- go into folder with PKGBUILD build package: **makepkg -s** (-> generate package)
- install package: **pacman -U generated_package.tar.xz**
