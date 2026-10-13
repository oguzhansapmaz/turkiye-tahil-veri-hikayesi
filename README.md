# Toprağın Hafızası — Veri Hikâyesi

Türkiye'de 1995–2024 döneminde tahıl veriminin (kg/ha) değişimini inceleyen scrollytelling projesi.

## Çalışma sorusu
Türkiye'de hektar başına tahıl verimi 1995–2024 arasında nasıl değişti ve yıllık artış/düşüşler hangi yıllarda belirginleşti?

## Klasörler
- `data/raw/`: Dünya Bankası kaynak dosyaları ve metadata
- `data/processed/`: sitede kullanılan temizlenmiş/özetlenmiş veri
- `notebooks/analiz.ipynb`: tekrar çalıştırılabilir analiz
- `site/`: HTML site ve site verisi/görseli
- `docs/storyboard.pdf`: hikâye akış taslağı
- `docs/tasarim-kararlari.pdf`: renk, tipografi ve grafik seçimleri
- `marketing/`: LinkedIn taslak metni ve paylaşım görseli
- `reports/`: Lighthouse rapor ekran görüntülerini ekleyin

## Yerelde çalıştırma
VS Code Live Server ile `site/index.html` dosyasını açın. CSV dosyası `site/data/` altında, arka plan görseli `site/assets/` altında bulunmalıdır.

## Kaynak
Dünya Bankası, Cereal yield (kg per hectare), `AG.YLD.CREL.KG`:
https://data.worldbank.org/indicator/AG.YLD.CREL.KG?locations=TR

## Teslim öncesi tamamlanacaklar
- [ ] Notebook'u Jupyter'da `Restart & Run All` ile çalıştırın ve çıktıları kaydedin.
- [ ] Gerçek storyboard çizimi/ekran görüntüsünü ekleyin veya bu taslağı kendi son tasarımınıza göre güncelleyin.
- [ ] Lighthouse mobil Performans ve Erişilebilirlik raporlarını alın ve `reports/` klasörüne PNG olarak ekleyin.
- [ ] GitHub deposunu herkese açık yapın ve canlı siteyi HTTPS ile yayımlayın.
- [ ] Portfolyo bağlantısının çalıştığını kontrol edin.
