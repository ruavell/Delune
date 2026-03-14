# Delune
   ![image alt](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg2hoHvqE3-whQKK2QnBh9d1WAMc6AbuTqExk3i7NVTD0b1yCep0I30eBVuN3HT5BcHwvueRoRA8cC3bvmp0PHT06k64gYmQMXmFIUNHFGtzgtbSeRH4BPlX1ySG-NNCj7COVwpGnEMTW4VYgtBiiOgtw1gPKOOp6ytFtlTEYwYj6v243_8NZ_if3y-Ots/s320/logodelune.png)


**Delune**, relay altyapısı kullanan, klasik masaüstü iletişim uygulamalarından ilham alan, **Aero tarzı arayüze** sahip, **ücretsiz**, **güvenli**, **sesli ve yazılı iletişim** odaklı bir sohbet platformudur.

Uygulama; klasik sunucu mantığı, gelişmiş oda sistemi, sesli sohbet, yazılı sohbet, resim ve dosya paylaşımı gibi özellikleri tek bir masaüstü deneyiminde birleştirmeyi hedefler.

> Bu proje, modern ama ağır tasarımlar yerine daha çok klasik desktop uygulama hissi veren, hızlı ve işlevsel bir iletişim istemcisi sunmak için geliştirilmektedir.

---

## Özellikler
  ![image alt](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj9ylzumKK9qsS5eNmYsSFppOkSHRyMmew8DmCXzDHOyMM9JvG2ukFWhNd4NXIjOzhlEmYL0XiTWaava0HqiTz4B7erChLzcL0QHpPcOvY48i_SPWz2ZmEUxz60KoLeu2kK_LCIQJ487mRiDyPTrEzZlF-SUlaOcjCKiMnqqBAm_oeQReLomGfHYqGPh40/s320/img1.png)

   ![image alt](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiQ-3LqMHcFoJG2j7hBa-NkGdF3vlbMP3P1Ge9Whp5_7gm3N4Czaf99tjShmkhf1-eCJ7ZvgjUhopxV5ChyphenhyphenykvIyiwLWCJ7TdS4Gbr_6W6c7FMDq9vk6sFEXpHb5u2cXYR9RNfc1FVayIetsEOA4Pwd6Re1gR9zoSa9HDnS0Xx7ujZ-kazqYeI0UWNhWvs/s320/img3.jpeg)



- Relay tabanlı altyapı

- Relay tabanlı altyapı
- Klasik **Aero / eski masaüstü stiline** yakın arayüz
- Yazılı sohbet
- Sesli sohbet
- Oda oluşturma ve odaya katılma
- Oda sahibi sistemi
- Oda sahibinin kullanıcı susturma ve odadan atma yetkileri
- Resim gönderme
- Dosya gönderme
- Mesaj geçmişi
- Mesaj silme sistemi
- Ses testi
- Ses seviyesi göstergesi
- Sınırsız oda mantığı
- Ücretsiz kullanım mantığı
- İstemci ve sunucu tarafının ayrı çalışabilmesi
- EXE olarak paketlenmiş istemci ve sunucu

---

## Hedeflenen Yapı

Delune, doğrudan kullanıcıdan kullanıcıya çalışan P2P mantığı yerine daha güvenli ve daha yönetilebilir bir **relay mimarisi** kullanır.

Bu sayede:

- kullanıcılar birbirine doğrudan bağlanmaz
- mesajlar sunucu üzerinden iletilir
- sesli iletişim sunucu relay mantığıyla yürür
- istemci tarafında daha düzenli ve kontrollü bir yapı sağlanır

---

## Proje Amacı

Delune’un amacı:

- eski masaüstü iletişim uygulamalarının sadeliğini korumak
- modern ama gereksiz karmaşık olmayan bir deneyim sunmak
- ücretsiz, topluluk odaklı ve geliştirilebilir bir yapı kurmak
- sesli ve yazılı sohbeti tek yerde toplamak
- ileride daha gelişmiş medya ve oda özellikleri eklenebilecek sağlam bir temel oluşturmaktır

---

## Planlanan / Geliştirilen Özellikler



Aşağıdaki özellikler proje için aktif hedefler arasındadır:

- Gelişmiş oda yönetimi
- TV / video oynatma mantığına benzer medya paylaşım sistemi
- Gelişmiş kullanıcı rolleri
- Profil sistemi
- Rozet sistemi
- Oda içi medya deneyimi
- Daha gelişmiş ses yönetimi
- Cihaz seçimi
- Gelişmiş moderasyon araçları
- Güncelleme kontrol sistemi
- Daha kararlı relay altyapısı
- Daha gelişmiş log sistemi

---

## Mimarî

### Client
İstemci tarafı kullanıcı arayüzünü, sohbeti, sesli odaları ve medya etkileşimini yönetir.

### Server

 ![image alt](https://blogger.googleusercontent.com/img/a/AVvXsEiY2cXT-yptvgfzVCDRhcz679bu-S7dAyu0om7HwlYi7qCiISrX-FuGCRRNAHCIvz-t37AQBGX2mll4FUeZPKlmmEm5ZH9WXKOLXxVjO0vb6lBt3ZgtjYQAZkVFkNqd0mX75b2R27b0cqFajFS_PxJnjgv96ciKHMMBJO7rOx76uFtNocSbdLUwrXPHksA)


 ![image alt](https://blogger.googleusercontent.com/img/a/AVvXsEgQQdpVgkZQZNrQk4E_WJihvpfzPfcxSqKpS-EpFdnr2OEV4FWJ12UaLh7HWnfftENmKpvuyboLFO-SuqZWt9vfaI9AdZfwhC_23INUHMvCCudcufkDnLKpDEzJzGczKaItAg3M1exwe8R54xQUNlsczbi7bZq922escdwu6B4k3P8d8m2q94ZXrIbkGkc)


Sunucu tarafı:

- oda yönetimini
- kullanıcı bağlantılarını
- relay mantığını
- mesaj geçmişini
- yetki sistemini

kontrol eder.

---

## Kullanılan Teknolojiler

- **Python**
- **PySide6**
- **WebSocket**
- **UDP relay**
- **Nuitka / EXE packaging**
- Desktop odaklı klasik arayüz yaklaşımı

---

## Güvenlik Yaklaşımı

Delune’da temel hedef, kullanıcı deneyimini bozmadan daha kontrollü bir iletişim yapısı sunmaktır.

Temel yaklaşım:

- relay tabanlı bağlantı
- istemci tarafında gereksiz ağ bilgisinin gösterilmemesi
- oda sahibi kontrollü moderasyon
- daha güvenli mesaj ve ses iletim mantığı
- zamanla geliştirilecek sürüm / güncelleme kontrol sistemi

> Not: Güvenlik tarafı hâlâ geliştirme sürecindedir ve proje ilerledikçe daha da güçlendirilecektir.

---

## EXE Durumu

İstemci ve sunucu tarafı **EXE olarak paketlenmiştir**.

Şu anda proje:

- **Client EXE**
- **Server EXE**

olarak çalıştırılabilmektedir.

---

## Çalıştırma Mantığı

### Sunucu
Önce sunucu açılır.

Sunucu tarafında:
- host
- websocket portu
- udp portu

tanımlanır ve istemciler bu sunucuya bağlanır.

### İstemci
İstemci açıldıktan sonra kullanıcı:

- sunucu adresine bağlanır
- kullanıcı adını girer
- oda oluşturur veya mevcut bir odaya katılır
- yazılı ve sesli iletişime geçer

---

## Şu Anda Bulunan Ana Özellikler

- Sunucuya bağlanma
- Oda listesi
- Oda oluşturma
- Odaya katılma
- Yazılı sohbet
- Sesli sohbet
- Ses testi
- Dosya gönderme
- Resim gönderme
- Mesaj geçmişi
- Oda sahibi yetkileri
- Susturma
- Kick

---

## Arayüz Vizyonu

Delune’un arayüzü, klasik masaüstü yazılımlarından ilham alır.

Hedef stil:

- temiz
- açık renkli
- eski Aero / masaüstü hissi
- işlev odaklı
- hızlı
- sade ama güçlü

---

## Geliştirme Durumu

Bu proje aktif geliştirme altındadır.

Bazı modüller stabil çalışırken bazı bölümler hâlâ geliştirilmektedir. Amaç, Delune’u zaman içinde:

- daha kararlı
- daha güvenli
- daha estetik
- daha özellikli

bir masaüstü iletişim uygulamasına dönüştürmektir.

---

## Katkı
![image alt](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj8K0aKKly-Zd3Y4JpKPRb-g4ml2EbARF-Lvjv22hIuOCaBiIr6vzYOAyP7jW33D1bnrsSTa55JbeBEcB8_e7wnPkCWW6UOauqLFyCMma5O9SMXyXQ3uuWUh1-Wgq9Xm_6c1bju5HlyLRcpgqp2V_rk10GFOgPBe74NHfH4qRKU4NQQp_SiUw-pBNREpTY/s320/maskot.png)



Projeye katkı sağlamak isteyenler:

- hata raporu açabilir
- özellik önerisi paylaşabilir
- arayüz geliştirmeleri önerebilir
- altyapı iyileştirmeleri sunabilir

---

## Yol Haritası

- Stable istemci arayüzü
- Stable relay sunucu
- Gelişmiş ses sistemi
- Medya / TV / video oynatma sistemi
- Profil sistemi
- Güncelleme sistemi
- Moderasyon araçları
- Daha kararlı dosya aktarımı
- Gelişmiş oda yapısı

---

## Uyarı

Bu proje geliştirme sürecindedir. Bazı özellikler tam kararlı olmayabilir. Yeni sürümlerde arayüz, altyapı ve özellikler değişebilir.

---

## Lisans

Bu proje için lisans tercihi henüz netleştirilmediyse burayı daha sonra güncelleyebilirsin.

Örnek:

```md
MIT License
