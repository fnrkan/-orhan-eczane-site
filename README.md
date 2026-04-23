# Orhan Eczanesi — Statik Web Sitesi

Fatsa, Ordu'daki Orhan Eczanesi için hazırlanmış, framework gerektirmeyen
saf HTML / CSS / JavaScript sitesi.

## İçerik

```
orhan-eczanesi/
├── index.html          # Anasayfa (hero, hizmetler, güven, CTA)
├── hizmetler.html      # Hizmetler kataloğu (8 hizmet)
├── blog.html           # Sağlık blogu (6 yazı önizleme kartı)
├── iletisim.html       # Adres, telefon, saatler ve harita
├── styles.css          # Tüm stiller (Güven Mavisi paleti, Outfit + Figtree)
├── script.js           # Mobil menü, aktif link, footer yılı
└── assets/
    └── hero-pharmacy.jpg
```

## Çalıştırma

Hiçbir build adımı yok. Klasördeki `index.html` dosyasını tarayıcıda aç,
veya basit bir statik sunucu kullan:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Sonra `http://localhost:8080` adresine git.

## Yayınlama

Tüm dosyaları herhangi bir statik hosting'e (Netlify, Vercel, GitHub Pages,
cPanel, vb.) yükle. Server tarafı bir gereksinim yok.

## Özelleştirme

- Renk ve tipografi değişkenleri `styles.css` üst kısmındaki `:root` bloğunda.
- Telefon numarası ve adres her HTML dosyasında düz metin olarak yer alıyor;
  toplu değişiklik için bir editörde "Bul & Değiştir" kullanın.
- Hero görselini `assets/hero-pharmacy.jpg` ile değiştirebilirsiniz.
