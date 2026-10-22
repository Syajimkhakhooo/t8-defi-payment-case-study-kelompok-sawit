# 💸 DeFi Payment & Cross-Border Transfer: Real Yield vs Token Incentives

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Colab-orange.svg)](https://colab.research.google.com/)

Proyek riset dan simulasi edukatif yang menganalisis efisiensi, potensi imbal hasil (*yield*), serta risiko dalam sistem pembayaran terdesentralisasi (*DeFi Payment*) dan transfer lintas negara (*cross-border*) menggunakan *stablecoin*.

---

## 📌 Latar Belakang & Masalah

Sistem pembayaran lintas negara tradisional seringkali dihadapkan pada masalah biaya administrasi yang tinggi, potongan nilai tukar (*spread*) yang besar, serta proses penyelesaian (*settlement*) yang memakan waktu beberapa hari kerja. *DeFi Payment* menggunakan *stablecoin* (seperti USDC/USDT) di jaringan *Layer-2* atau *blockchain* berkecepatan tinggi hadir sebagai solusi dengan biaya transaksi mendekati $0 dan penyelesaian instan.

Namun, masyarakat dan mahasiswa sering terkecoh oleh promosi nilai **APR/APY tinggi** pada penyedia likuiditas (*Liquidity Provider*) protokol pembayaran, tanpa memahami dari mana sumber pendapatan tersebut berasal dan risiko kerugian di baliknya.

---

## 🎯 Tujuan Penelitian & Mini Project

1. **Membandingkan Efisiensi:** Menganalisis perbandingan biaya dan kecepatan transfer *DeFi Payment* vs perbankan tradisional.
2. **Dekomposisi Yield:** Membedakan antara *Real Economic Revenue* (pendapatan riil dari *fee* transaksi) dengan *Token Incentives* (hadiah emisi token spekulatif).
3. **Analisis Skenario Pasar:** Menguji dampaknya terhadap *total return* penyedia likuiditas jika harga token hadiah mengalami penurunan drastis (*bear market*).
4. **Riset Peluang Tanpa Modal:** Melakukan *due diligence* terhadap program Web3 berisiko $0 (seperti *bounty*, *learning platform*, dan audit kerentanan).

---

## 📊 Hasil Utama & Temuan Simulasi

### 1. Dekomposisi Sumber Return (Modal Virtual: $1.000)
- **Economic Revenue (Real Yield):** **5.0% APR** (berasal dari *fee* transaksi riil pengguna).
- **Token Incentives:** **12.0% APR** (berasal dari emisi token *native* protokol).

| Skenario Pasar | Economic Revenue | Token Incentive (Awal) | Speculative Price Change | Total Return ($) | Total Return (%) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Bear (-70%)** | $50.00 | $120.00 | -$84.00 | **$86.00** | **+8.60%** |
| **Turun (-30%)** | $50.00 | $120.00 | -$36.00 | **$134.00** | **+13.40%** |
| **Datar (0%)** | $50.00 | $120.00 | $0.00 | **$170.00** | **+17.00%** |
| **Naik (+50%)** | $50.00 | $120.00 | +$60.00 | **$230.00** | **+23.00%** |

> **Kesimpulan:** Jika emisi token insentif dihentikan, *return* yang tersisa hanya **5%** (murni dari *economic revenue*). Nilai ini tetap menarik bagi investor *low-risk* karena berbasis pada utilitas dunia nyata (*stablecoin*), tetapi tidak lagi menarik bagi spekulan *yield farming*.

---

## 🛡️ Checklist Due Diligence & Risk Mitigation

Dalam mengeksplorasi peluang tanpa modal (*Free Opportunities*), dilakukan evaluasi ketat dengan kriteria utama **Modal = Rp0** dan **Bebas Scam**.

| Program | Kategori | Keputusan | Mitigasi Risiko |
| :--- | :--- | :---: | :--- |
| **Superteam Earn** | Bounty / Content | 🟡 **CAUTION** | Menggunakan *wallet* Solana baru tanpa saldo utama; KYC dilakukan hanya di platform resmi jika menang. |
| **Cyfrin Updraft** | Learn & Reward | 🟡 **CAUTION** | Menyelesaikan seluruh kursus gratis; **STOP** dan tidak membeli *voucher* sertifikasi berbayar. |
| **Code4rena** | Security Research | 🟡 **CAUTION** | Pembelajaran mandiri melalui laporan audit publik; tidak memasang taruhan/modal. |
| **ETHGlobal Mumbai** | Hackathon | 🔴 **STOP** | Dieliminasi karena memerlukan biaya *staking*/deposit awal dan transportasi. |

---

## 📖 Glosarium Istilah DeFi Payment

- **Stablecoin:** Token kripto yang nilainya dipatok (*pegged*) ke mata uang fiat (misal 1 USDC = 1 USD).
- **Liquidity Provider (LP):** Pengguna yang menyetorkan dana ke *smart contract* untuk memfasilitasi pertukaran dan transaksi pembayaran orang lain.
- **Gas Fee:** Biaya jaringan yang dibayarkan untuk memproses transaksi di *blockchain*.
- **Real Yield:** Imbal hasil yang bersumber dari pendapatan bisnis riil (seperti biaya transaksi), bukan dari pencetakan token baru.
- **Slippage:** Perbedaan harga antara harga yang diharapkan dengan harga saat transaksi dieksekusi.

---

## 🚀 Cara Menjalankan Notebook Simulasi

1. *Clone repository* ini:
   ```bash
   git clone https://github.com/<kelompok>/t8-defi-payment-case-study.git
   ```
2. Buka berkas Jupyter Notebook (`.ipynb`) di **Google Colab** atau **Jupyter Lab**.
3. Jalankan seluruh *cell* secara berurutan untuk melihat grafik interaktif dan tabel analisis dekomposisi *yield*.

---

## 🤝 Anggota Kelompok
* **[Nama Anggota 1]** - *Riset & Analisis Kasus*
* **[Nama Anggota 2]** - *Simulasi Python & Visualisasi*
* **[Nama Anggota 3]** - *Due Diligence & Penyusunan Dokumen*

---
*Proyek ini disusun sebagai bagian dari Tugas Logbook / Analisis Studi Kasus Ekosistem DeFi.*