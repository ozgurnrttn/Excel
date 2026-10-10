# Excel Çalışmaları

Excel ile yapılmış iki analiz: PivotTable tabanlı bir satış panosu ve Çözücü (Solver) ile portföy
optimizasyonu.

## Dosyalar

### `2008-2012-Yıllarında-Gayrimenkul-Satışları.xlsx`

Türkiye'de 81 ilin 2008–2012 yılları arasındaki gayrimenkul satışları (konut, ipotekli ve diğer satışlar).

- **VERİ SETİ:** İl, bölge ve yıl bazında satış adetleri
- **DASHBOARD:** PivotTable ve dilimleyicilerle hazırlanmış pano: satışların bölgelere dağılımı,
  bölgelerin satış türleri, seçilen il ve yıl için satış grafiği

### `Hisse-Senedi-Analizi.xlsx`

Konno-Yamazaki modeliyle optimal portföy seçimi. Dokuz BIST hissesinin (GARAN, HALKB, ARCLK, KCHOL,
TUPRS, THYAO, TOASO, MGROS, TTKOM) 31.12.2020 – 29.01.2021 arasındaki günlük getirileri (21 işlem günü)
üzerinden, ortalama mutlak sapmayı en küçükleyen portföy ağırlıkları Excel Çözücü ile bulunur.

Veri: tr.investing.com

## Kullanım

Dosyaları indirip Excel'de aç. Portföy modelini yeniden çözmek için Çözücü (Solver) eklentisinin
etkin olması gerekir.
