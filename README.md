<div align="center">

# ✨ Dashboard Satu Pintu

**Satu pintu untuk semua aplikasi Anda — ringan, modern, dan responsif.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 🌟 Tentang

**Dashboard Satu Pintu** adalah portal tunggal yang menggabungkan beberapa aplikasi web ke dalam satu tampilan yang rapi. Cukup satu halaman HTML, tanpa framework dan tanpa instalasi.

## 🧩 Aplikasi di Dalamnya

| Aplikasi | Deskripsi | Tautan |
|---|---|---|
| 📊 **Awesome Dashboard** | Dashboard utama untuk memantau data dan informasi. | [Buka](https://111118ben.github.io/awesome-dashboard/) |
| 📝 **Format Umpan Balik** | Formulir format umpan balik yang rapi dan siap pakai. | [Buka](https://111118ben.github.io/Format-Umpan-Balik/) |

## 🎨 Fitur

- 🏠 **Beranda** dengan banner sambutan dan kartu aplikasi
- 🖼️ **Tampilan terpadu** — setiap aplikasi dibuka langsung di dalam dashboard (iframe)
- 🌓 **Tema terang & gelap**, otomatis mengikuti perangkat plus tombol ganti tema
- 📱 **Responsif** — sidebar di desktop, menu bawah di HP
- ↗️ **Buka di tab baru** untuk setiap aplikasi
- ⚙️ **Mudah dikonfigurasi** lewat satu file JSON

## 🚀 Cara Pakai

```bash
# 1. Salin repositori
git clone <url-repositori-anda>
cd <nama-folder>

# 2. Generate dashboard dari konfigurasi
python3 build.py

# 3. Buka hasilnya
# dashboard.html  → klik dua kali di browser
```

## ➕ Menambah Aplikasi Baru

Edit `config.json`, tambahkan satu objek pada daftar `apps`, lalu jalankan ulang `python3 build.py`.

```json
{
  "title": "Dashboard Satu Pintu",
  "apps": [
    {
      "id": "contoh",
      "name": "Aplikasi Baru",
      "desc": "Deskripsi singkat",
      "icon": "🚀",
      "url": "https://contoh.com/"
    }
  ]
}
```

## 📁 Struktur Proyek

```text
.
├── config.json      # Daftar aplikasi & judul dashboard
├── build.py         # Generator HTML (Python)
├── dashboard.html   # Hasil akhir
└── README.md
```

## ⚠️ Catatan

Jika sebuah situs menolak ditampilkan dalam iframe (kebijakan `X-Frame-Options`), gunakan tombol **↗ Buka tab baru**.

---

<div align="center">

Dibuat dengan ❤️ untuk memudahkan akses ke semua aplikasi dalam satu tempat.

</div>
