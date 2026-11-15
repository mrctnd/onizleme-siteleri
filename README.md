# Önizleme Siteleri

Bu repository, birden fazla web tasarım önizleme sitesini tek bir yerden yönetmek için oluşturulmuştur.

## Amaç

- Tek bir katalog sayfası oluşturmak
- Her önizleme sitesine ayrı GitHub Pages linki vermek
- Yeni eklemeleri kolay hale getirmek

## GitHub Pages yapısı

Ana sayfa şu adreste çalışır:

- https://mrctnd.github.io/onizleme-siteleri/

Her site de kendi GitHub Pages URL'si ile açılır:

- https://mrctnd.github.io/crossfitcankaya-onizleme/
- https://mrctnd.github.io/mervet-onizleme/
- https://mrctnd.github.io/onlypilates-onizleme/

## Klasör yapısı

Bu repoda aşağıdaki yapı kullanılabilir:

```text
onizleme-siteleri/
├─ index.html
├─ README.md
├─ sites/
│  └─ README.md
└─ assets/
   └─ styles.css
```

Yeni site eklendiğinde şu yöntem izlenebilir:

1. Site dosyalarını ilgili klasöre koy
2. GitHub Pages için klasör dizin yapısını kontrol et
3. Ana sayfa listesine siteyi ekle

## Not

Bu repo, ana katalog olarak çalışır. Gerçek tasarım örnekleri ayrı repo'larda olduğu için ana sayfa, o repo'ların GitHub Pages URL'lerini gösterir.
