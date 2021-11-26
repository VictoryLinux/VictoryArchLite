# VictoryArchLite.

# A WORK IN PROGRESS...not there yet.

<img src="VictoryArch.png" />

This README contains the steps I do to configure a fully-functional Arch Linux installation containing Gnome desktop environment, all the support packages (network, bluetooth, audio, printers, etc.), along with all my preferred applications and utilities. The shell scripts in this repo allow the entire process to be automated.)

---
## Create Arch ISO or Use Image

Download ArchISO from <https://archlinux.org/download/> and put on a USB drive with Ventoy or Popsicle

## Boot Arch ISO

From initial Prompt type the following commands:

```
pacman -Sy git
git clone https://github.com/VictoryLinux/VictoryArch
cd VictoryArch
./victoryarch.sh

restart

cd VictoryArch
./4-finish.sh
```

### System Description
This is completely automated arch install of the Gnome desktop environment on arch using all the packages I use on a daily basis. 
