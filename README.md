# LoputonLinux UEFI sistemde boot sorunu
LoputonLinux imajı ayarlanırken MBR sistem üzerinde test edildi. UEFI sistemlerde çalışabilirliği test edilmeden yayinlandi. USB belleğe doğrudan yazdırıldığı zaman UEFI sistem üzerinde boot edilmeyebililr.

Bu sorunun çözümü ise USB belleğe Ventoy'u GPT olarak yazdırmak, Ventoy yüklü olan USB belleğin içine de LoputonLinux imajını kopyalamak.

LoputonLinux'u Ventoy ile önyükleme yaptığınız zaman herhangi bir hata vermeden açılması gerekir.

# LoputonLinux Gelecek Yenilikler
LoputonLinux'un amacı USB bellekte birden fazla Linux dağıtımı bulundurulmasının önüne geçmek. Her bir dağıtımın sunduğu özellikler farklıdır ancak temelde hepsinde aynı işlevler yapılabilir. LoputonLinux tek başına USB'de bulunup bütün işlerinizi yapabileceğiniz Devuan imajıdır. İster pentesting çalışın, ister günlük kullanın, isterseniz de disk onarmak/kurtarmak için kullanın. Tamamen bağımsız ve özgür bir imaj dosyası geliştiriliyor.

Gelecek sürümde içerisine retro oyunlar eklenecek, daha fazla araç eklenecek, tasarımda değişiklikler olacak, UEFI sistemlerde olan sorunlar çözülecek ve sürücü desteği artacak.

# Desteklenen Cihazlar
-Excalibur G770 | NVIDIA GTX 1650, i5-9300H, 16GB

Çalışan Özellikler:
* WIFI
* Ses
* Touchpad
* Parlaklık
* Uyku modu
* Ses artırma/kısma/kapama kısayolları
* Parlaklık kısma/artırma
* RGB Klavya Işığı açma/kapama kısayolu

Çalışmayan Özellikler:
* SD Card Reader
* Touchpad açma/kapama kısayolu
* WIFI kapatma kısayolu
