# LoputonLinux Two Masami
Bu sürümde genel LoputonLinux sürümündeki UEFI sorunları düzeltildi. 

Bu sürümün amacı Asus Vivobook 16x ve benzeri cihazların kablosuz ağ bağlantısını desteklemesi. Devuan 5.0'da bulunan 6.1.0-13 kernel'in içerisinde rtw89 sürücüleri bulunmuyordu. rtw89 sürücüleri eklendi ve artık direkt olarak USB'den boot edildiği zaman kablosuz bağlantı sağlanacak.

Önceki sürümde bulunan pentesting araçlarının büyük bir kısmı artık desteklenmediği, güncelleme almadığı ve dolayısıyla güncel python sürümleri ile çakışma yaşandığı için kaldırıldı. Artık pentest araçları Debian ve Devuan depolarında yoksa, LoputonLinux'un güncel sürümlerine eklenmeyecektir.

LoputonLinux tam anlamıyla dağıtım sayılmayabilir, bunun nedeni Devuan depolarını kullanmasıdır. LoputonLinux'a destek vermek ve geliştirmeye yardım etmek için profildeki Discord linkine bakabilirsiniz.

Dell Latitude ve Asus Vivobook 16x modelleri üzerinde test edildi.
