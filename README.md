# 💊 Nöbetçi Eczaneler

Türkiye genelinde 81 il ve tüm ilçelerde güncel nöbetçi eczaneler, canlı konum, en yakın 5 eczane ve tek tıkla arama/yol tarifi.

## ✨ Özellikler
- Tamamen istemci taraflı, sunucusuz çalışma.
- LocalStorage ile veri saklama.
- Mistral AI tasarım diliyle optimize edilmiş arayüz.

## 🚀 Hızlı Başlangıç
1. Bu repoyu klonlayın.
2. `index.html` dosyasını tarayıcıda açın.

```bash
git clone https://github.com/melihkarasu/nobetci-eczane.git
cd nobetci-eczane
```

## 🔑 API Anahtarı Gereksinimi
> **⚠️ Önemli:** Bu uygulama eczane verilerini **eczaneapi.com** servisinden çekmektedir.
> 
> Uygulamanın çalışması için **`ECZANE_API_KEY`** ortam değişkeni (environment variable) gereklidir. 
> Güvenlik nedeniyle API anahtarı repoya dahil edilmemiştir.
> 
> **Kendi API anahtarınızı almak için:** [eczaneapi.com](https://eczaneapi.com) adresine gidin, üye olun ve kontrol panelinizden API anahtarınızı kopyalayın.
> 
> **Yerel çalıştırmak için:** `js/app.js` dosyasında `const API_KEY = 'YOUR_KEY_HERE';` satırını kendi anahtarınızla güncelleyebilirsiniz. Alternatif olarak tarayıcı konsolundan `localStorage.setItem('ECZANE_API_KEY', 'ANAHTARINIZ')` komutunu çalıştırın.

## 🛠️ Teknik Detaylar
- **Styling:** Tailwind CSS
- **Design System:** Mistral AI Design System
- **Storage:** Browser LocalStorage API
- **API Source:** Nöbetçi Eczane API (eczaneapi.com)

## 🏆 Krediler & Açık Kaynak Teşekkürleri
- **[Public APIs](https://github.com/public-apis/public-apis):** Uygulamanın kullandığı açık kaynak API ekosistemi için teşekkürler.
- **[OpenClaw](https://github.com/openclaw/openclaw):** Proje mimarisi ve otonom deployment.
- **[Google Gemini](https://github.com/google-gemini):** Kodlama ve istemci tarafı optimizasyonları.
- **[VoltAgent / awesome-design-md](https://github.com/VoltAgent/awesome-design-md):** Mistral AI Tasarım Sistemi.

## 📜 Lisans
MIT Lisansı altında açık kaynak olarak paylaşılmıştır.

---
Daha fazla açık kaynak mikro uygulama için [GitHub profilimi](https://github.com/melihkarasu) ziyaret edebilirsiniz.