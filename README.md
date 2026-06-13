# 👗 AffiliateFit

> Upload foto produk + foto model → AI gabungkan jadi foto profesional model pakai produk affiliate kamu

## ✨ Fitur

- 📸 **Upload foto produk** — Hijab, bergo, pashmina, baju, dll
- 👤 **Upload foto model** — Foto orang yang mau dipakaikan produk
- 🤖 **AI Virtual Try-On** — FAL.AI CAT-VTON / IDM-VTON
- ⬇️ **Download hasil** — Langsung pakai di Threads/Instagram
- 🔑 **API key sendiri** — $5 free credits di FAL.AI (~100 gambar)
- 📱 **Mobile friendly** — Bisa dipakai dari HP
- 🌙 **Dark mode** — Easy on the eyes

## 🪄 Cara Kerja

1. **Upload foto produk** dari Shopee (hijab, bergo, pashmina, dll)
2. **Upload foto model** (foto orang yang mau dipakaikan produk)
3. **Klik Generate** → AI gabungkan otomatis (30-60 detik)
4. **Download hasilnya** → Pakai di Threads/Instagram

## 🔑 Setup

1. Daftar di [fal.ai](https://fal.ai) (gratis)
2. Dapatkan API key ($5 free credits)
3. Masukkan key di web app
4. Generate!

## 🤖 Model yang Tersedia

| Model | Harga | Kelebihan |
|-------|-------|-----------|
| CAT-VTON | ~$0.05/gambar | Cepat, hasil bagus |
| IDM-VTON | ~$0.10/gambar | Kualitas lebih tinggi |

## 🛠️ Local Development

```bash
# Langsung buka index.html
open index.html

# Atau serve locally
python3 -m http.server 8080
```

## 📦 Integrasi dengan Threads Bot

Hasil gambar bisa langsung di-attach ke Threads comments:

```python
# Download gambar dari AffiliateFit
# Simpan ke ~/threads-bot/product-images/
# Bot akan otomatis attach ke comment
```

## 📄 License

MIT — Made with 🪄 by [gyoomei](https://github.com/gyoomei)
