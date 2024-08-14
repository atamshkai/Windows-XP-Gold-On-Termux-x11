# Windows-XP-Gold-On-Termux-x11

This is Windows XP Gold for Termux-x11.You can run Photoshop,Blender,PowerISO,Microsoft Office & etc on your android phone.Before you install it on android 12 and 13,disable phantom process killer.

[Here](https://github.com/atamshkai/Phantom-Process-Killer/tree/main)

## Install Termux-Desktop 

[Termux-Desktop]
(https://github.com/atamshkai/Termux-Desktop)

## Preview

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold.png)

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold2.png)

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold3.png)

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold4.png)

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold5.png)

![](https://raw.githubusercontent.com/atamshkai/Windows-XP-Gold-On-Termux-x11/main/xpgold6.png)

# To Do

Download xpgold.7z from here first.

[Download](https://archive.org/download/atamshkai-xpgold-qcow2/xpgold.7z)

Unzip xpgold.7z 

#### ES File Explorer 

[Download](https://archive.org/download/es-file-explorer-4-4-0-2-1_202308/es-file-explorer-4-4-0-2-1.apk)


#### Winrar

[Download](https://archive.org/download/rar_20230806/RAR.apk)

#### ISO Maker

[Download](https://archive.org/download/isocraft-v-1.4/ISOCraft_v1.4.apk)

## Installation

Install Qemu

```
pkg up -y;pkg i -y qemu-system-x86-64
```

Give Storage Permission

```
termux-setup-storage
```

Add xpgold to ~/../usr/bin

```
bash /storage/emulated/0/Download/xpgold/xpgold.txt
```

Symlink SDCARD to termux's home

```
ln -s /sdcard ~/sdcard
```

Start Termux Desktop

```
tm-x11 &>/dev/null
```

In Termux-Desktop's Terminal

```
xpgold
```

### Microsoft Office 
[Download](https://mega.nz/file/NEkXTRTZ#cfvEP6htugaJLdhRjjQmkBee8GtnuNDNFUet69NQBQU)

## Termux 
[Download](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk) 

## Termux-x11 
[Download](https://archive.org/download/atamshkai-termux-x11/app-universal-debug.apk) 

## Termux-x11 Custom Resolution
1920:1080
