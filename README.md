# Olimpiyat Exploratory Data Analysis
<br/>

## Projenin Amacı
**Olimpiyatlar Veri Setini Kullanılarak Veriyi Analiz Etmek**

## 120 Yıllık Olimpiyat Tarihi Veri Seti 
- Olimpiyat Oyunları kapsamında, toplamda 13.000'in üzerinde sporcu 400'den fazla kategoride mücadele etmektedir. Gerçekleştirilen mücadeleler sonucunda, belli bir kategoride en iyi sırayı elde eden sporcular sırasıyla ALtın Gümüş ve Bronz madalyalar kazanmıştır.ç
- 120 Yıllık Olimpiyat Tarihi Veri Seti, Atina 1896'dan Rio 2016'ya kadar tüm oyunlar dahil olmak üzere modern Olimpiyat Oyunlarına ilişkin tarihsel bir veri kümesidir.

### Veri Seti İçerisinde Bulunan Sütunların İsimleri ve Açıklamaları
- ID - Her sporcu için benzersiz numara
- Name - Sporcunun ismi
- Gender - Cinsiyet
- Age - Yaş
- Height - Boy
- Weight - Ağırlık
- Team - Takım ismi
- NOC - Uluusal Olimpiyat Komitesi 3 harfli kod
- Games - Yıl ve Sezon
- Year - Yıl
- Season - Sezon (yaz -kış)
- City - Düzenlenen Şehir
- Sport- Spor
-Event -Etkinlik
- Madal- Madalya (altın- gümüş- bronz ve madalya yok)


## İçerik
1. Veri Hakkında Bilgiler
2. Verinin Temizlenmesi
3. Eksik Verilerin Doldurulması
4. Tek Değişkenli Veri Analizi
- sayısal değişkenler
- kategorik değişkenler
- cinsiyete göre boy ve ağırlık karşılaştırılması
- sayısal sütunlar arasındaki ilişki
5. Çok Değişkenli Veri Analizi
- aykırı değer tespiti ve işlemleri
- IQR( IQR = Inter Quartile Range) hesaplamsı
6. Zaman Serilerinde Veri Analizi
- yıllara göre boy, yaş,kilo değişimi
- yıllara göre madalya değişimi
- yıllara ve sezonlara göre madalya sayilari 

### Kullanılan Kütüphaneler ve Yüklemeleri
- Pandas
- Numpy 
- Matplotlib 
```
{
  import pandas as pd
  import matplotlib.pyplot as plt
  import numpy as np
}
```
