# 👗 AffiliateFit

> Upload foto produk + foto model → AI gabungkan jadi foto profesional model pakai produk kamu

**100% GRATIS — Tanpa API Key!**

## ✨ Fitur

- 📸 **Upload foto produk** — Hijab, bergo, pashmina, baju, dll
- 👤 **Upload foto model** — Foto orang yang mau dipakaikan produk
- 🤖 **AI Virtual Try-On** — Powered by Hugging Face Spaces (Free)
- ⬇️ **Download hasil** — Langsung pakai di Threads/Instagram
- 🆓 **100% Gratis** — Tidak perlu API key atau registrasi
- 📱 **Mobile friendly** — Bisa dipakai dari HP
- 🌙 **Dark mode** — Easy on the eyes

## 🪄 Cara Kerja

1. **Upload foto produk** dari Shopee (hijab, bergo, pashmina, dll)
2. **Upload foto model** (foto orang yang mau dipakaikan produk)
3. **Klik Generate** → AI gabungkan otomatis (30-60 detik)
4. **Download hasilnya** → Pakai di Threads/Instagram

## 🤖 Model AI yang Tersedia

| Model | Kelebihan | Speed |
|-------|-----------|-------|
| **IDM-VTON** | Kualitas terbaik, detail bagus | ~30-60s |
| **Kolors Try-On** | Alternatif, cepat | ~20-40s |

## 🛠️ Local Development

```bash
# Langsung buka index.html
open index.html

# Atau serve locally
python3 -m http.server 8080
```

## 📦 Integrasi dengan Threads Bot

Hasil gambar bisa langsung di-attach ke Threads comments:

1. Download gambar dari AffiliateFit
2. Simpan ke `~/threads-bot/product-images/`
3. Bot akan otomatis attach ke comment

## 📄 License

MIT — Made with 🪄 by [gyoomei](https://github.com/gyoomei)
