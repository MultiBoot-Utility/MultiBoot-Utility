# MultiBoot Utility Tr-En


![alt MultiBoot Utility](https://github.com/MultiBoot-Utility/MultiBoot-Utility/blob/master/MultiBoot%20Utility/Goruntuler/MultiBoot_Utility_1_En.PNG)

## Download
#### English (v1.7)
[![Download MultiBoot Utility](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/multiboot-utility/files/MultiBoot%20Utility%20En.exe/download)

#### Turkish (v1.7)
[![Download MultiBoot Utility](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/multiboot-utility/files/MultiBoot%20Utility%20Tr.exe/download)

[Old Version](https://github.com/MultiBoot-Utility/MultiBoot-Utility/tree/master/MultiBoot%20Utility/Old)

## More Information

[www.tnctr.com](https://www.tnctr.com/topic/642741-multiboot-utility-v10/)

[sourceforge.net](https://sourceforge.net/p/multiboot-utility/)

## Intended Use

#### USB/HDD;
* Grub2 installs. Boot to be ready.
	- IMPORTANT * You can select a folder with the desired name as the boot directory.
* Grub2 version update on the existing MultiBoot systems used.
	- Grub2 files embedded in the program, if you want, you can update with your own downloaded Grub2 files.
	- You can update Legacy, Efi32 and Efi64 separately.
* Creates g2ldr, core.img, bootia32.efi and bootx64.efi files for Grub2 v2.04 and v2.05 and copies them to their respective locations on your system.
* Grub2 File Manager installs. Makes it ready to use.
* Clover downloads the latest version of Bootloader and integrates it into the existing MultiBoot system used to make it ready for use.
	- Internet connection is required as it downloads the current files from the internet.
	- If the system has Clover Bootloader files, it will update as the most current version.
	- If there is no Clover Bootloader in the system, it installs the latest version and makes it ready for use.
* rEFInd downloads the latest version of Bootloader and integrates it with the existing MultiBoot system used to make it ready for use.
	- Internet connection is required as it downloads the current files from the internet.
	- If the system has rEFInd Bootloader files, it will update as the most current version.
	- If there is no rEFInd Bootloader in the system, it installs the latest version and makes it ready for use.
* Downloads current Grub4Dos files to the existing MultiBoot system used and makes them ready to use.
	- Internet connection is required as it downloads the current files from the internet.
	- If no Grub4Dos is present in the system, it installs under the grub directory by default.
	- If there are already Grub4Dos files installed on the system (it doesn't matter which folder it is), it will update by overwriting.
* If Secure Boot is enabled in UEFI, it replaces the current MultiBoot system's UEFI boot method with original efi files signed by Microsoft and makes it ready for use.
* XorBoot Bootloader installs. Makes it ready to use.
	- You can use Xorboot Bootloader configuration programs directly from the program.
* You can run all tests by opening Virtual Disk Management program, QEMU Test program and Bootice program directly through the program.

## Change Log
```
(v1.7)
 # Bug fix (grubenv)
 
(v1.6)
 # Grub2 File Manager for the latest up-to-date files are downloaded and installed from the internet.
 # The latest installation of Grub2 File Manager and Grub4Dos files is provided in zero installation.

(v1.5)
 # Zero installation v2.04 and v2.05 are optional.
 # Added Xorboot bootloader.
 # It is now possible to use XorBoot Bootloader programs through the program.
 # Loader creation and update grubx64.efi and grubia32.efi files are now created.
 # Fixed an error in the installation when there was a space in the Windows user name.
 
(v1.4)
 # Clover and rEFInd Bootloader added.
 # Disc structure information added.
 
(v1.3)
 # Operation on the Windows installed drive is now optional.

(v1.2)
 # The program was opened directly after the first opening unless there was a change of version.

(v1.1)
 # Operations are blocked if Windows is installed on the selected drive.
 # Fixed the error that came after Grub4Dos was completed.

(v1.0)
 # The first version of the program is released.
 ```