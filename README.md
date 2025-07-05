# SOUIY - Tusky Auto Upload Bot

---

## Tusky Testnet | Token-Gated Access

 🪂 Link:  https://testnet.app.tusky.io/vaults

➖ Connect Sui wallet or Google account

➖ Create password (12 words)

➖ Backup phrase > create vault
  
➖ Upload any file

➖ Provide feedback (on the left corner)

Source: https://x.com/TuskyTools/status/1939703089897808251

---

## 📌 Deskripsi
Bot ini dirancang untuk mengotomatisasi proses upload gambar ke platform Tusky menggunakan akun SUI. Bot ini mendukung multi-akun, proxy, dan memiliki antarmuka berbasis terminal yang interaktif.

## 🚀 Fitur Utama
- Upload otomatis gambar acak ke platform Tusky
- Dukungan multi-akun (baca dari file seed.txt)
- Dukungan proxy (SOCKS/HTTP)
- Antarmuka terminal interaktif
- Log aktivitas lengkap
- Konfigurasi fleksibel
- Eksekusi berulang setiap 24 jam

## ⚙️ Persyaratan Sistem
- Node.js v18 atau lebih baru
- NPM/Yarn
- Koneksi internet

## 📥 Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/Souiy/TuskyAutoBot-SOUIY.git
cd TuskyAutoBot-SOUIY
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Persiapan File Konfigurasi
Buat file `seed.txt` yang berisi seed phrase akun SUI Anda (satu seed phrase per baris):
```
nano seed.txt
```

Opsional: Buat file `proxy.txt` untuk menggunakan proxy (satu proxy per baris, format: `socks://ip:port` atau `http://ip:port`):
```
socks://123.123.123.123:1080
http://45.45.45.45:8080
...
```

## 🛠 Konfigurasi
Bot secara default akan melakukan 3 upload per akun. Anda bisa mengubahnya melalui menu:
1. Pilih "Set Manual Config"
2. Pilih "Set Upload Count"
3. Masukkan jumlah upload yang diinginkan (1-100)
4. Tekan Enter untuk menyimpan

Konfigurasi akan otomatis tersimpan di file `config.json`.

## 🏃‍♂️ Cara Menjalankan
```bash
node index.js
```

### Tombol Navigasi:
- **↑/↓**: Navigasi menu
- **Enter**: Pilih menu
- **q/Esc**: Keluar dari aplikasi
- **Mouse**: Juga bisa digunakan untuk navigasi

## 🖥 Tampilan Antarmuka
Antarmuka bot terdiri dari:
1. **Header**: Judul aplikasi
2. **Status Box**: Menampilkan status bot dan informasi akun aktif
3. **Wallet Box**: Daftar alamat wallet yang terdaftar
4. **Log Box**: Catatan semua aktivitas bot
5. **Menu Box**: Menu interaktif untuk mengontrol bot

## 🛑 Menghentikan Bot
- Untuk menghentikan proses upload yang sedang berjalan, pilih menu "Stop Auto Upload"
- Untuk keluar dari aplikasi, pilih menu "Exit" atau tekan `q`/`Esc`

## ⚠️ Catatan Penting
1. Pastikan seed phrase Anda valid dan memiliki saldo SUI untuk transaksi
2. Bot akan berjalan secara otomatis setiap 24 jam sekali
3. Aktivitas upload yang berlebihan mungkin melanggar ToS Tusky, gunakan dengan bijak
4. Jangan bagikan file seed.txt Anda ke siapapun
5. Ikuti perkembangan terbaru di TikTok: [AirdropRefferal (Souiy1)](https://www.tiktok.com/@airdroprefferal)

## 🤝 Donasi Palestina
- Satukan Solidaritas Bantu Palestina!
- [BANTU PALESTINA](https://digital.dompetdhuafa.org/donasi/jagapalestina)

---

---

**Catatan**: Bot ini dibuat untuk tujuan TESTNET. Pengguna bertanggung jawab penuh atas penggunaan bot ini.
