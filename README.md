# winreset
Script for semi-automatic password reset of local Windows users.

**Requires:** ntfsprogs ntfs-3g chntpw  
**Script location:** /usr/bin/winreset

Used [chntpw](http://www.chntpw.com/): change password of a user in a Windows SAM file,
or invoke registry editor. Should handle both 32 and 64 bit windows and
all version from NT3.x to Win8.1. (c) Petter N Hagen.

## LiveUSB
[Download WinReset LiveUSB...](https://cloud.mail.ru/public/sNho/qWbbDc9fn)

How to make a flash drive:
1. Download the *.7z archive with the desired desktop and unpack it to a flash drive with a FAT32 file system
2. Make the flash drive bootable:
     a) In Windows - run Flash Drive as Administrator:\boot\syslinux\BootInstall.bat
     b) In Linux - run in the terminal (su/password) Flash drive/boot/syslinux/BootInstall.bat
3. The flash drive is ready
