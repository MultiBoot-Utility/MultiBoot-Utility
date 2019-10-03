# MultiBoot Utility Tr-En


![alt MultiBoot Utility](https://github.com/MultiBoot-Utility/MultiBoot-Utility/blob/master/MultiBoot%20Utility/Goruntuler/MultiBoot_Utility_1_En.PNG)

## More Information

[www.tnctr.com](https://www.tnctr.com/topic/642741-multiboot-utility-tr-en-v12/)

## Download
#### Turkish
[![Download MultiBoot Utility](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/multiboot-utility/files/MultiBoot%20Utility%20Tr_v1.3.exe/download)

#### English
[![Download MultiBoot Utility](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/multiboot-utility/files/MultiBoot%20Utility%20En_v1.3.exe/download)

## Intended Use

#### USB/HDD;
* Grub2 installs. Boot to be ready.
	- IMPORTANT * You can select a folder with the desired name as the boot directory.
* Grub2 version update on the existing MultiBoot systems used.
	- Grub2 files embedded in the program, if you want, you can update with your own downloaded Grub2 files.
	- You can update Legacy, Efi32 and Efi64 separately.
* Creates g2ldr, core.img, bootia32.efi and bootx64.efi files for Grub2 v2.04 and v 2.05 and copies them to their respective locations on your system.
* Grub2 File Manager installs. Makes it ready to use.
* Downloads current Grub4Dos files to the existing MultiBoot system used and makes them ready to use.
	- Internet connection is required as it downloads the current files from the internet.
	- If no Grub4Dos is present in the system, it installs under the grub directory by default.
	- If there are already Grub4Dos files installed on the system (it doesn't matter which folder it is), it will update by overwriting.
* If Secure Boot is enabled in UEFI, it replaces the current MultiBoot system's UEFI boot method with original efi files signed by Microsoft and makes it ready for use.
* You can run all tests by opening Virtual Disk Management program, QEMU Test program and Bootice program directly through the program.

## Change Log
```
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