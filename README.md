# Önizleme Siteleri

Bu repository, tüm web sitesi tasarım önizlemelerini tek yerde tutar. Her sitenin dosyaları `sites/<repo-adı>/` klasöründedir ve kendi GitHub Pages bağlantısından açılır.

## Yayın adresleri

- Katalog: <https://mrctnd.github.io/onizleme-siteleri/>
- Site örneği: <https://mrctnd.github.io/onizleme-siteleri/sites/crossfitcankaya-onizleme/>
- Site örneği: <https://mrctnd.github.io/onizleme-siteleri/sites/mervet-onizleme/>

## Klasör yapısı

```text
onizleme-siteleri/
├─ index.html                 # Önizleme kataloğu
├─ .nojekyll                  # Statik dosyaları olduğu gibi yayınla
└─ sites/
   ├─ README.md
   ├─ crossfitcankaya-onizleme/
   │  ├─ index.html
   │  └─ assets/
   └─ mervet-onizleme/
      ├─ index.html
      └─ assets/
```

## Yeni önizleme ekleme

1. Sitenin yayınlanabilir dosyalarını `sites/<repo-adı>/` klasörüne kopyala. `index.html` bu klasörün kökünde, görseller ve diğer dosyalar da mevcut göreli yollarında olmalı.
2. Kök `index.html` dosyasındaki `sites` listesine ad, klasör adı ve kısa açıklama ekle.
3. `main` dalına gönder. GitHub Pages, repository kökünü yayınladığı için site şu adreste açılır: `https://mrctnd.github.io/onizleme-siteleri/sites/<repo-adı>/`.

Her site klasörünü kendi içinde tut; aynı isimli `index.html`, `assets/` veya font dosyaları diğer sitelerle çakışmaz.
