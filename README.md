# Delune

Bu paket, ayrı **Delune Server** ve **Delune Client** uygulamalarından oluşan LAN / public IP / Hamachi odaklı bir prototiptir.

## İçerik

- Metin sohbet
- Oda oluşturma / katılma
- Arkadaş isteği ve oda daveti
- Temel sesli konuşma
- Dosya / resim / GIF gönderimi
- Temel ekran paylaşımı önizlemesi
- Server yönetim GUI'si

## Kurulum

```bash
pip install -r requirements.txt
```

## Çalıştırma

Sunucu:


```

İstemci:


```

## Notlar

- Bu sürüm bir **prototip**. Özellikle ses ve ekran paylaşımı tarafı, LAN / Hamachi için uygundur.
- Büyük dosya gönderimi desteklenmez. Varsayılan üst sınır 5 MB.
- Şifreleme, hesap sistemi, kalıcı veritabanı ve ileri seviye ekran paylaşımı bu pakette yok.
- `sounddevice` için sistemde uygun ses sürücüsü gerekir.
- Ekran paylaşımı için `mss` gerekir.


Güncelleme notları:
- Enter ile mesaj gönderme eklendi.
- Oda içinde ayrı ses odası mantığı eklendi.
- Oda sahibi seçili kullanıcıyı sesli odada susturup açabilir.
- Konuşan kullanıcı listede yeşil vurgulanır.
- Ekran paylaşımı akışı güçlendirildi ve yerel önizleme eklendi.
