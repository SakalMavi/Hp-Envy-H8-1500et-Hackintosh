Hp-Envy-H8-1500et Desktop Bilgisayarı olanların Bu repo Sayesinde, hackintosh'un kurulumu sırasında size rehberlik etmesi ve
bu esnada ihtiyacınız olan kaynakları toplayıp hepsini bir arada bulabilmeniz için yapıldı.

KURULUM'a Başlamadan Önce BIOS ayarlarını yapmamız gerekmektedir.
BIOS Ayarları (Intel) :
Başlamadan önce BIOS ayarlarınızı öntanımlı ayarlara çekin (Load Default Settings).
SATA: AHCI olarak ayarlayın
VT-D: Disable olarak ayarlayın
EHCI Hand-off / xHCI Hand-off: Enable olarak ayarlayın.
xHCI Mode: Smart Auto
Secureboot: Disable (Other OS) olarak ayarlayın
CFG-Lock= Disable
Boot Option Priorities: UEFI USB olarak ayarlayın. Yada UEFI and Legacy.
-------------------------------------------------------------------------------
Kurulum Öncesi Sisteminiz için uygun Config.plist seçmek:
Bunu Yapabilmek için pc donanımımızı iyi bilmek gereklidir
Bizim Hp-Envy-H8-1500et Bilgisayarımızın İşlemcisi i7 3770K - Ivy Bridge 3.Nesil
İntel Cpu List
* 1.  Nesil Cpu - Gulftown
* 2.  Nesil Cpu - Sandy Bridge
* 3.  Nesil Cpu - Ivy Bridge
* 4.  Nesil Cpu - Haswell
* 5.  Nesil Cpu - Broadwell
* 6.  Nesil Cpu - Skylake
* 7.  Nesil Cpu - Kaby Lake
* 8.  Nesil Cpu - Coffee Lake
* 9.  Nesil Cpu - Cascade Lake
* 10. Nesil Cpu - Comet Lake
------------------------------------------------------------------------------
# Hp-Envy-H8-1500et-Hackintosh
MacOS Catalina 10.15.2
------------------------------------------------------------------------------
Anakart : Hp Anakart H8-1500et Pegatron 2AP5 Intel Z75 Chip setli
İşlemci : i7 3770K
Ekran Kartı : Hp Nvidia GTX660 DDR5
SSD : 1 TB Samsung
ETERNET KARTI : Athers AR8161 PCI-E
SES KARTI. : IDT 92HD73E1/92HDW74E1
------------------------------------------------------------------------------
Config.plist Dosyasında Cpu SMBIOS MacPro 6.1 Seçilmeli karşılığı i7 3770K - Ivy Bridge
Uyku Moduna Girip Uyuması Sonra Uyanması Için Anakartımız Pegatron 2AP5 Intel Z75 Chip setli
olduğundan İntel 7 series Usb yamamsı ve 0x0D usb power yaması yapılması gerekmektedir
çin DSDT'yi düzeltmeye gerek yok
