# Skill Lab — LLM Skill Benchmark

![Node.js](https://img.shields.io/badge/Node.js-2f81f7?style=flat) ![Python](https://img.shields.io/badge/Python-2f81f7?style=flat) ![LLM Judge](https://img.shields.io/badge/LLM_Judge-2f81f7?style=flat) ![JSON](https://img.shields.io/badge/JSON-2f81f7?style=flat) ![Markdown](https://img.shields.io/badge/Markdown-2f81f7?style=flat)

> Eksperimen evaluasi yang membandingkan model dengan dan tanpa skill agar peningkatan kualitas dapat diukur.

## Tentang proyek

Eksperimen evaluasi yang membandingkan model dengan dan tanpa skill agar peningkatan kualitas dapat diukur. Dokumentasi ini dibuat sebagai panduan singkat untuk memahami ruang lingkup proyek, menjalankannya secara lokal, dan membaca batasan penggunaannya.

## Fitur utama

- Perbandingan dua kondisi eksperimen
- Grading oleh judge LLM
- Pengukuran timing dan benchmark
- Output JSON terstruktur
- Laporan HTML per iterasi

## Teknologi

- Node.js
- Python
- LLM Judge
- JSON
- Markdown

## Menjalankan secara lokal

Prasyarat dan konfigurasi dapat berbeda menurut sistem operasi. Contoh langkah utama:

```bash
npm install
node --test
```

## Struktur dan pengembangan

Mulai dari entry point dan folder konfigurasi proyek. Pisahkan credential lokal dari source code, tambahkan test untuk perubahan penting, dan gunakan environment variable untuk konfigurasi deployment.

## Keamanan

- Jangan commit API key, password, token, session ID, atau data pribadi.
- Gunakan file environment lokal dan contoh konfigurasi tanpa nilai rahasia.
- Uji perubahan pada environment development sebelum deployment.

## Status

Proyek ini merupakan bagian dari portofolio **Hilman Arifin Ilham** dan dapat dikembangkan sesuai kebutuhan penggunaan.

> **Catatan:** API key model disediakan lewat environment variable. Hasil benchmark bergantung pada model, prompt, dan konfigurasi eksperimen.

## Lisensi

Belum ada lisensi open-source yang dinyatakan di repository ini. Hubungi pemilik repository sebelum menggunakan ulang atau mendistribusikan kode.

---

Dibuat oleh [Hilman Arifin Ilham](https://github.com/hilman-devop).
