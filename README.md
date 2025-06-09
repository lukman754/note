# 💰 Catatan Keuangan Plus

Aplikasi web sederhana untuk mencatat pemasukan dan pengeluaran harian dengan fitur kalkulator otomatis dan multi-user.

## ✨ Fitur Utama

### 🧮 Kalkulator Otomatis
- **Input dengan Perhitungan**: Masukkan ekspresi matematika langsung (contoh: `50000+25000-5000`)
- **Real-time Calculation**: Hasil perhitungan ditampilkan secara otomatis
- **Operasi Matematika**: Mendukung `+`, `-`, `*`, `/`, dan tanda kurung

### 👥 Multi-User Support
- **Pengguna Multiple**: Buat dan kelola beberapa pengguna
- **Data Terpisah**: Setiap pengguna memiliki data keuangan terpisah
- **Ganti Pengguna**: Mudah beralih antar pengguna

### 📊 Manajemen Keuangan
- **Pencatatan Pemasukan**: Catat semua sumber pemasukan
- **Kategorisasi Pengeluaran**: Makanan, Minuman, Bensin, dan Lainnya
- **Ringkasan Harian**: Lihat ringkasan keuangan hari ini
- **Total Keseluruhan**: Ringkasan semua transaksi

### 📤 Export/Import Data
- **Export JSON**: Backup data dalam format JSON
- **Export CSV**: Export untuk spreadsheet
- **Import Data**: Restore data dari file backup

## 🚀 Demo Live

Akses aplikasi di: `https://[username].github.io/[repository-name]/`

## 🛠️ Cara Deploy di GitHub Pages

### 1. Fork/Clone Repository
```bash
git clone https://github.com/[username]/[repository-name].git
cd [repository-name]
```

### 2. Rename File
Rename `note.html` menjadi `index.html` untuk GitHub Pages

### 3. Enable GitHub Pages
1. Buka repository di GitHub
2. Masuk ke **Settings** → **Pages**
3. Pilih source: **Deploy from a branch**
4. Pilih branch: **main** dan folder: **/ (root)**
5. Klik **Save**

### 4. Akses Aplikasi
Aplikasi akan tersedia di: `https://[username].github.io/[repository-name]/`

## 💡 Cara Menggunakan

### Kalkulator Otomatis
Pada setiap field input, Anda bisa memasukkan perhitungan langsung:
- `50000 + 25000` → Hasil: 75,000
- `100000 - 15000` → Hasil: 85,000
- `20000 * 2` → Hasil: 40,000
- `(50000 + 30000) / 2` → Hasil: 40,000

### Multi-User
1. Pilih dropdown **"Pilih Pengguna"**
2. Untuk menambah user baru, masukkan nama di field **"Nama pengguna baru"**
3. Klik **"Tambah"**
4. Data setiap user disimpan terpisah

### Export/Import
- **Export JSON**: Untuk backup lengkap
- **Export CSV**: Untuk analisis di Excel/Google Sheets
- **Import**: Restore data dari file backup

## 🏗️ Struktur File

```
finance-app/
│
├── index.html          # File utama aplikasi
├── README.md          # Dokumentasi
└── assets/            # (optional) folder untuk assets
```

## 🔧 Fitur Teknis

### Local Storage
- Data disimpan di browser menggunakan `localStorage`
- Data tidak hilang saat browser ditutup
- Setiap user memiliki storage key terpisah

### Responsive Design
- Kompatibel dengan desktop dan mobile
- Desain modern dengan gradient dan animasi
- Interface yang intuitif

### Security
- Input sanitization untuk mencegah XSS
- Safe evaluation untuk kalkulator
- Validasi input yang ketat

## 🎨 Customization

### Warna Tema
Edit CSS variables di bagian `:root` untuk mengubah tema warna:

```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #45a049;
  --danger-color: #f44336;
  --info-color: #2196F3;
}
```

### Kategori Pengeluaran
Tambah kategori baru dengan mengedit:
1. Form HTML
2. JavaScript functions
3. Data structure

## 🚀 Peningkatan Masa Depan

- [ ] Grafik dan chart visualisasi
- [ ] Reminder dan notifikasi
- [ ] Backup cloud otomatis
- [ ] Mobile app (PWA)
- [ ] Tema dark/light mode
- [ ] Laporan bulanan/tahunan

## 🤝 Kontribusi

1. Fork repository
2. Buat branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📝 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Kontak

Project Link: [https://github.com/[username]/[repository-name]](https://github.com/[username]/[repository-name])

---

⭐ **Jangan lupa berikan star jika aplikasi ini bermanfaat!** ⭐
