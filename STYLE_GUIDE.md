# Notepad++ Türkçe Çeviri Stil Kılavuzu

## 1. Yazım ve Biçimlendirme Standartları

### A. Sentence Case Kullanımı
Arayüzdeki menü, buton ve pencere isimlerinde kelimelerin ilk harflerini büyük yazma yaklaşımı (*Title Case*) yerine Türkçe dil yapısına uygun olan **Sentence Case** (Yalnızca ilk kelimenin ilk harfi büyük) kullanılır.

* **Yanlış:** Dosya Aç, Farklı Kaydet, Tümünü Kapat, Pencereyi Her Zaman Üstte Göster
* **Doğru:** Dosya aç, Farklı kaydet, Tümünü kapat, Pencereyi her zaman üstte göster

### B. Üç Nokta Standartlaştırması
Kullanıcıdan ek bir işlem/onay bekleyen veya bir pencere açan menü ögelerinin sonunda üç adet nokta yan yana (`...`) yazılmalı; özel üç nokta karakteri (`…` - `U+2026`) kullanılmamalıdır.

### C. Geliştirici Yorum Satırları (`<!-- ... -->`)
* **Türkçe Yerelleştirme:** XML dosyası içinde kod blokları ve etiket aralarında yer alan `<!-- ... -->` yorum satırları (örneğin `<!-- HowToReproduce: ... -->` açıklamaları), kodu inceleyen veya projeye katkı sağlayan Türk geliştiriciler/çevirmenler için Türkçe standartlarına ve terim bütünlüğüne uygun olarak Türkçeye çevrilir.
* **Biçim ve Yapı Koruması:** Çeviri yapılırken yorum satırı yapısı (`<!--` ve `-->`) kesinlikle bozulmaz; yorum içerisindeki teknik terimler, kod değişkenleri ve parametreler olduğu gibi korunur.

---

## 2. Katkıda Bulunma

Arayüzde veya kod yorumlarında fark ettiğiniz terim tutarsızlıklarını, imla hatalarını bu stil kılavuzundaki kurallara göre düzenleyerek **Pull Request** gönderebilirsiniz.
