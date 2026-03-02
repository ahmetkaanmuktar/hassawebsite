# T.C. Hassa Belediyesi - Resmi Web Sitesi

Hatay ili Hassa ilçesi belediyesinin resmi kurumsal web sitesi. Tek sayfa (single-page) yapıda, vatandaş odaklı hizmet bilgileri, duyurular, projeler ve iletişim bilgilerini sunar.

## Özellikler

- **Kurumsal**: Başkan mesajı, meclis, müdürlükler, stratejik plan ve faaliyet raporları
- **Hizmetler**: E-Belediye, duyurular, ulaşım, çözüm masası, nöbetçi eczaneler
- **Haberler & Projeler**: Güncel haberler ve proje kartları
- **İstatistikler**: Nüfus, proje sayısı, dikilen ağaç, memnuniyet oranı (animasyonlu sayaç)
- **İletişim**: Harita, adres, telefon, e-posta, WhatsApp hızlı iletişim butonu
- **Yasal**: KVKK aydınlatma metni, çerez politikası, kullanım koşulları
- **Erişilebilirlik**: Klavye ile "İçeriğe Atla" (skip link), odak (focus) stilleri
- **Mobil uyumlu**: Responsive tasarım, mobil menü

## Teknolojiler

- HTML5, CSS3 (değişkenler, grid, flexbox)
- Vanilla JavaScript (menü, scroll efektleri, sayaç animasyonu)
- Google Fonts (Plus Jakarta Sans, Inter)
- Font Awesome ikonlar
- Google Maps embed

## Yerel Çalıştırma

1. Projeyi indirin veya klonlayın.
2. `index.html` dosyasını tarayıcıda açın veya yerel bir sunucu ile çalıştırın:

   ```bash
   # Örnek: Python 3
   python -m http.server 8000
   # Tarayıcıda http://localhost:8000
   ```

## Klasör Yapısı

```
hassabelediyesi/
├── index.html          # Ana sayfa (tek dosyada stil ve script)
├── assets/
│   ├── css/
│   │   └── style.css   # Opsiyonel harici stil
│   ├── js/
│   │   └── main.js     # Opsiyonel harici script
│   └── img/            # Görseller (logo, hero, haber, başkan vb.)
├── README.md
└── .gitignore
```

## Görseller

Aşağıdaki görsellerin `assets/img/` klasöründe bulunması önerilir:

- `logo.png` – Belediye logosu
- `hero-bg.jpg` – Hero arka plan
- `baskan1.jpg` – Belediye başkanı fotoğrafı
- `haber1.jpg`, `haber2.jpg`, `haber3.jpg` – Haber kartları (isteğe bağlı; yoksa placeholder gösterilir)

## Lisans ve Telif

© 2026 T.C. Hassa Belediyesi. Bu proje belediyenin resmi web sitesi amacıyla hazırlanmıştır.
