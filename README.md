<div align="center">

# 📍 YerBul — Fırat Üniversitesi Kampüs Radar
### Kitle Kaynaklı (Crowdsourced) Akıllı Kampüs Doluluk Radarı

[![Canlı Demo](https://img.shields.io/badge/Canlı%20Demo-yer--bul.vercel.app-6d131f?style=for-the-badge&logo=vercel&logoColor=white)](https://yer-bul.vercel.app)

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Leaflet](https://img.shields.io/badge/Leaflet-1.9-199900?style=flat-square&logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Lisans: Telifli](https://img.shields.io/badge/Lisans-Telifli%20(All%20Rights%20Reserved)-red?style=flat-square)](LICENSE)

<br/>

**Fırat Üniversitesi kampüsündeki kütüphaneler, etüt salonları, kafeler ve dinlenme alanlarının anlık doluluk durumunu canlı harita üzerinden takip etmeyi sağlayan web uygulaması.**

[🚀 Canlı Uygulamayı Dene](https://yer-bul.vercel.app) • [✨ Özellikler](#-özellikler) • [🛠️ Teknolojiler](#️-teknolojiler) • [👤 İletişim](#-iletişim)

</div>

---

## 📸 Arayüz Vitrini

<div align="center">

| 🗺️ Kampüs Haritası | 📊 Mekan Detay & Doluluk | 📱 QR ile Hızlı Bildirim |
| :---: | :---: | :---: |
| ![Harita Görünümü](screenshots/map-preview.png) | ![Detay Paneli](screenshots/detail-preview.png) | ![QR Okuyucu](screenshots/qr-preview.png) |

</div>

---

## 💡 Proje Hakkında

Sınav dönemlerinde kütüphane ve çalışma salonlarında yer bulamayıp geri dönmek ya da ders aralarında boş kafe aramak öğrenci hayatının en büyük vakit kayıplarından biridir.

**YerBul**, bu problemi kitle kaynaklı (crowdsourced) gerçek zamanlı veri akışıyla çözer. Öğrenciler masalardaki QR kodları okutarak veya harita üzerinden tek tıkla doluluk durumunu bildirir; sistem anlık doluluk oranını (%0 - %100), açık/kapalı durumunu ve çalışma imkanlarını haritada birleştirir.

---

## ✨ Özellikler

- 📍 **İnteraktif Kampüs Haritası:** Ana Kampüs, Çaydaçıra, Malatya Caddesi ve KYK yurtlarını kapsayan 22+ doğrulanmış mekan.
- ⚡ **Kitle Kaynaklı Canlı Doluluk:** Öğrencilerin anlık bildirimleri (*Boş, Müsait, Az Kaldı, Dolu*) ile otomatik hesaplanan doluluk yüzdeleri.
- 📷 **Masa QR Kodu ile Bildirim:** Telefon kamerasından masadaki QR kodu okutarak saniyeler içinde durum bildirme.
- 🕒 **Canlı Çalışma Saatleri:** Saate göre otomatik hesaplanan dinamik `Açık` / `Kapalı` rozetleri.
- 🌙 **Gece Kuşu Modu:** 00:00'dan sonra ve 7/24 açık olan çalışma mekanlarını tek tıkla filtreleme.
- ⭐ **Favori Mekanlar:** Sık kullanılan çalışma salonlarını yer imlerine ekleme.
- 🖨️ **Masa QR Kartları:** Masalara yapıştırılmak üzere çıktıya hazır QR kart şablonları.

---

## 🛠️ Teknolojiler

- **Frontend:** React 18, Vite, React-Leaflet, Framer Motion, html5-qrcode
- **Backend:** Python 3.11, FastAPI, SQLAlchemy, WebSockets
- **Veritabanı:** PostgreSQL
- **Dağıtım:** Vercel & Bulut Barındırma

---

## 🔒 Telif Hakkı & Gizlilik

> **© 2026 Baran Tunca. Tüm Hakları Saklıdır.**  
> Bu depo, projenin arayüz tasarımını ve özelliklerini sergilemek amacıyla hazırlanmış bir vitrindir (Showcase). Kaynak kodlar ve fikri mülkiyet hakları gizli tutulmaktadır; izinsiz kopyalanamaz veya ticari amaçla kullanılamaz.

---

## 👤 İletişim

**Baran Tunca** — Fırat Üniversitesi  
- 🌐 **Canlı Demo:** [yer-bul.vercel.app](https://yer-bul.vercel.app)
- 💼 **LinkedIn:** [linkedin.com/in/baran-tunca](https://www.linkedin.com/in/baran-tunca/)
- 🐙 **GitHub:** [@barantunca](https://github.com/barantunca)
- ✉️ **E-Posta:** [barantunca25@gmail.com](mailto:barantunca25@gmail.com)
