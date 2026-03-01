# Ödev 1 - Tailwind CSS Landing Page

Tailwind CSS kullanılarak hazırlanmış tek sayfalık (single-page) landing page. Görseller [picsum.photos](https://picsum.photos) üzerinden alınmaktadır.

---

## Proje Hakkında

Bu proje, **Mamba** adlı kurgusal bir design system / ürün tanıtımı için tasarlanmış örnek bir landing sayfasıdır. Tüm stiller Tailwind CSS utility sınıfları ile yazılmıştır; ek CSS dosyası kullanılmamaktadır.

---

## Sayfa Bölümleri

| Bölüm | Açıklama |
|-------|----------|
| **Header** | Logo, navigasyon linkleri, Sign up butonu (sabit üst bar) |
| **Hero** | "Build it with Mamba" başlığı, kısa açıklama, isim/e-posta formu, "Join the waitlist" butonu ve görsel |
| **How it works** | "Building with Mamba is simple" başlığı altında 3 adımlı özellik kartları (numaralı daireler) |
| **Create with us** | Giriş metni, öne çıkan içerik kartı (görsel + Business etiketi, başlık, tarih, yazar), 3 özellik kutusu |
| **Testimonial** | Sol tarafta görsel, sağda müşteri alıntısı, isim, unvan ve sayfalama noktaları |
| **Team** | "Our team is here to help you" metni, "Meet our crew" linki ve geniş görsel |
| **Footer** | Mamba markası ve sosyal medya ikonları (e-posta, Twitter, GitHub) |

---

## Dosya Yapısı

```
tailwind-landing-page/
├── index.html    # Tüm sayfa içeriği ve Tailwind sınıfları
└── README.md     # Bu dosya
```

---

## Çalıştırma

- **Tarayıcıda açma:** `index.html` dosyasına çift tıklayarak veya sürükleyerek tarayıcıda açabilirsiniz.  
  Tailwind CSS CDN üzerinden yüklendiği için **ek kurulum veya build gerekmez.**

- **Yerel sunucu (isteğe bağlı):** Bazı tarayıcılarda `file://` ile açarken kısıtlamalar olabilir. Sorun yaşarsanız:

```bash
# Klasöre girip basit bir sunucu başlatın
cd tailwind-landing-page
npx serve .
# veya
python3 -m http.server 8080
```

Ardından tarayıcıda `http://localhost:3000` veya `http://localhost:8080` adresine gidin.

---

## Kullanılan Teknolojiler

- **HTML5** – Sayfa yapısı ve içerik
- **Tailwind CSS** – [tailwindcss.com](https://tailwindcss.com) (CDN ile)
- **Görseller** – [picsum.photos](https://picsum.photos) (rastgele placeholder görseller)

---

## Ödev Bilgisi

- **Ödev:** Tailwind CSS Landing Page (Ödev 1)
- **Teslim:** Bu klasör (`tailwind-landing-page`) zip’lenerek veya doğrudan gönderilebilir.
