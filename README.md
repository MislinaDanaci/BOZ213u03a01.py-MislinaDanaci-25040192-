# 3.1.6 LAB – Karşılaştırma Operatörleri ve Koşullu İfadeler

Bu proje, **BOZ213** dersi kapsamında hazırlanan **3.1.6 LAB** uygulamasıdır. Program, kullanıcıdan alınan bir tam sayının `100` değerinden büyük veya `100`'e eşit olup olmadığını `if-else` blokları kullanmadan, doğrudan karşılaştırma operatörü (`>=`) ile kontrol eder.

## Proje Bilgileri

* **Ders Kodu:** BOZ213
* **Dosya Adı:** `3.1.6LAB.py`
* **Hazırlayan:** Mislina Danacı (`25040192`)
* **Dil:** Python 3

## Çalışma Mantığı

1. `input("sayi girin:")` fonksiyonu ile kullanıcıdan veri alınır ve `int()` fonksiyonu yardımıyla tam sayıya dönüştürülerek `n` değişkenine atanır.
2. `n >= 100` karşılaştırma operatörü ile sayının `100`'e eşit veya büyük olup olmadığı değerlendirilir.
3. İşlem sonucu ekrana mantıksal (`Boolean`) değer olarak (`True` veya `False`) yazdırılır.

## Kurulum ve Çalıştırma

Repoyu bilgisayarınıza klonladıktan veya dosyayı indirdikten sonra terminal üzerinden aşağıdaki komutla çalıştırabilirsiniz:

```bash
python 3.1.6LAB.py
