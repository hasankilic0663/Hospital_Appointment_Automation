# Hospital_Appointment_Automation
----------------------------------------------------------
#Hastane Randevu  Otomasyon Projesi ->HASAN HÜSEYİN KILIÇ
----------------------------------------------------------
https://www.linkedin.com/posts/hasan-h%C3%BCseyin-kili%C3%A7-368439228_proje-otomasyon-tasaraftm-activity-7022152953771831296-r-FE?utm_source=share&utm_medium=member_desktop


#Proje Açıklaması:
----------------------------------------------------------


Projemde ADO.NET ile SQL kullanmaktansa direkt olarak EntityFramework üzerinden geliştirmelerimi yaptım.
Projede  tasarım Kısmında Framework kullandım.
Bunifu UI ve Guna UI ek paketlerini projemde kullanarak kendi özel tasarımımı oluşturdum.

#Proje Setup:
----------------------------------------------------------

'Beni Oku.txt' dosyasının bulunduğu yolda bir 'Hastane_Randevu_Otomsayonu' isimli '.msi' uzantılı dosya
çalıştırılarak oluşturulacaktır.

#! Önemli Not :
--------------

Proje çalıştıktan sonra bu otomasyonun Özel Hastane Randevu Sistemi Olduğu için Hastanede ki Danışman görevli
giriş yaparak sadece sisteme erişebilir. Randevu Sisteminin çalışma mantığı sadece tek kişi Danışman tarafından 
girilerek randevu ile ilgili hasta işlemleri yapılabilmektedir.Aşağıdaki verdiğim Tc Kimlik no ve Şifre kısmındakileri
yazarak sisteme giriş yapabilirsiniz.

TC KİMLİK NO : 11111111111
Şifre : 1111

Yapılacak İşlemler
Animasyon Giriş Kısmı Karşıladıktan sonra Danışman Girişi kısmı açılacaktır. 
------------------
#DANIŞMAN GİRİŞ KISMI 
-Öncelikle Danışman giriş kısmı ekrana geldiğinde sizi tamamen yeni Modern bir hareketli görsel efektli , gifli bir 
giriş kısmı karşılayacak. Burada Facebook , İnstagram, Twitter, Linkedln butonlu gif kullanarak hepsi aktif 
bir şekilde çalışıp web sitelerine yöneltmektedir. 

-Şifremi unuttum kısmında ise bizleri gerçek e-posta adresimize mail göndererek Şifreyi sıfırlayabiliyoruz. 
tabi bu panellerde de sizleri yine görsel efektler karşılayacak.
------------------

#Ana MENU GİRİ KISMI 
-AnaMenüde bizi modern tasarım karşılayacak. Ana menü de 7 tane normal form 1 tanede gömülü form olmak uzere toplam 
8 pencere karşılıyor bizi. 
PENCERELER
- Randevu Ver: Burada bizi framework ek paketlerini kullanarak yaptığım modern tasarım karşılıyor . Burada kayıtlı hasta 
TC sini girip branş ve doktoru seçtikten sonra randevu saatini Tarihini seçip başarıyla kaydetebiliyoruz. 
RANDEVU VER de Geçmiş Tarihe Randevu , kayıtlı olmayan hasta , eksik girilen bilgi, aynı gün ve aynı saate alınmış 
randevuler gibi bunları önleyecek bilgiler koda dökülmüştür .
- Randevu Sil:Veri Tabanı ekranı gelip istediğiniz hastanın tcsini yazarak onu daha kolay bulup veri tablosundan seçip 
silebiliriz
- Kayıt Ekle: Yeni Hasta kaydı yapılıyor.
- Kayıt Düzenle: Kayıtlı Hastanın bilgileri Güncelleniyor
- Kayıt Sil: Kayıtlı Hastayı siliyoruz
- Aktif Randevular:Hastanedeki tüm aktif randevular gözükmektedir. Ve ayriyetten Doktor Randevularıda özel olarak seçip görebiliriz.
   - Aktif Randevu içerisinde Gömülü Doktor Randevuları var.
- Geçmiş Randevular 
-Destek : Bana ulaşmak için sosyal medya hesaplarımı buton şeklinde yeni bi form yaptım .

İki tanede çıkış butonu bulunuyor.

------------------


#Database Dosyaları Ve Bilgileri
-------------------------------
Veritabanı asıl olarak VS içerisindeki SQL server üzerinden yazılmış olsa da entityframework'ün sağladığı
dinamiklikle her bilgisayarda çalışabilmesi için gömülü bir database kullanılmıştır.

Database yolu : C:\ içerisinde HastaneProjesi_NTP isimli klasörün içerisinde HastaneVeriTABANI.mdf isimli klasör.
