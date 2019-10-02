# MultiBoot Utility Tr-En


![alt MultiBoot Utility](https://github.com/MultiBoot-Utility/MultiBoot-Utility/blob/master/MultiBoot%20Utility/MultiBoot_Utility_1_Tr.PNG)

## Kullanım Amaçları

USB/HDD lerde;

* qemu emulated Q35 systems
* [Intel S2600WF](https://trmm.net/S2600wf)
* [Dell R630](https://trmm.net/NERF)
* Winterfell Open Compute node (works well)
* Leopard Open Compute node (works well)
* Tioga Pass Open Compute node (works well)
* Monolake Open Compute node (not tested)

* Grub2 kurulumu yapar. Boot olacak şekilde hazır duruma getirir.
 ÖNEMLİ * Boot dizinini olarak istediğiniz isimdeki bir klasörü seçebilirsiniz.
Kullanılan mevcut MultiBoot sistemlerde Grub2 versiyon güncellemesi yapar.
İster program üzerinde gömülü Grub2 dosyalarla, isterseniz kendi indirmiş olduğunuz Grub2 dosyaları ile güncelleme yapabilirsiniz.
Güncelleme işlemini Legacy, Efi32 ve Efi64 ayrı ayrı seçmeli olarak yapabilirsiniz.
Grub2 v2.04 ve v 2.05 için g2ldr, core.img, bootia32.efi ve bootx64.efi dosyalarını oluşturarak sisteminizdeki ilgili yerlere kopyalar.
Grub2 Dosya Yönetici kurulumu yapar. Kullanıma hazır hale getirir.
Kullanılan mevcut MultiBoot sistemine güncel Grub4Dos dosyalarını indirir ve kullanmaya hazır hale getirir.
Güncel dosyaları internetten indirdiği için internet bağlantısı gerekmektedir.
Sistemde Grub4Dos hiç yoksa default olarak grub dizininin altına kurar.
Sistemde önceden yüklü Grub4Dos dosyaları varsa (Hangi klasörde olduğu önemli değil) üzerine yazarak güncelleme yapar.
UEFI de Secure Boot aktif iken boot sorunu yaşanması durumunda kullanılan mevcut MultiBoot sisteminin UEFI boot yöntemini Microsoft tarafından imzalanmış orijinal efi dosyaları ile değiştirir ve kullanıma hazır hale getirir.
Program üzerinden direk Sanal Disk Yönetim programı, QEMU Test programı ve Bootice programını açarak bütün testleri yapabilirsiniz.

## Deneme 2

MultiBoot 2