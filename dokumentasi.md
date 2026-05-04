# Dokumentasi Aplikasi SkyCast - Weather Prediction

SkyCast adalah aplikasi prakiraan cuaca modern yang dirancang untuk memberikan informasi meteorologi yang akurat, interaktif, dan mudah digunakan bagi pengguna di seluruh Indonesia.

## Fitur Utama

### 1. Radar Cuaca Interaktif (Real-Time)
Mengintegrasikan radar dari **Windy** untuk menampilkan pergerakan awan dan curah hujan secara langsung.
- **Interaktivitas:** Pengguna dapat menggeser (pan) dan memperbesar (zoom) peta.
- **Visualisasi:** Menampilkan lapisan curah hujan dan badai secara real-time.

### 2. Pemilihan Lokasi Seluruh Indonesia
Fitur untuk mengganti lokasi cuaca dengan daftar kota yang komprehensif di Indonesia.
- **Cakupan:** Lebih dari 40 kota besar di Indonesia (Sumatera, Jawa, Kalimantan, Sulawesi, Bali, Nusa Tenggara, Maluku, dan Papua).
- **Update Otomatis:** Mengganti kota akan secara otomatis memperbarui radar, data detail cuaca, ramalan harian, dan ramalan per jam.

### 3. Detail Cuaca Mendalam (Current Details)
Menampilkan informasi kondisi saat ini secara mendetail:
- **Terasa Seperti (Feels Like):** Suhu yang dirasakan oleh tubuh.
- **Kelembapan & Tekanan:** Data kelembapan udara dan tekanan atmosfer (mb).
- **Jarak Pandang & Angin:** Informasi visibilitas (km) dan kecepatan angin (km/j).
- **Indeks UV & Fase Bulan:** Informasi tingkat paparan matahari dan fase bulan saat ini.
- **Diagram Jalur Matahari:** Representasi visual waktu terbit dan terbenamnya matahari.

### 4. Ramalan Cuaca 7 Hari (Daily Forecast)
Memberikan gambaran kondisi cuaca selama seminggu ke depan.
- Menampilkan ikon kondisi, suhu rata-rata, dan deskripsi cuaca.
- Data diperbarui secara dinamis setiap kali lokasi diubah.

### 5. Ramalan Per Jam (Hourly Forecast)
Memberikan rincian cuaca setiap jam untuk 24 jam ke depan.
- **Expandable List:** Setiap baris jam dapat diklik untuk melihat detail tambahan seperti Tutupan Awan dan Prediksi Curah Hujan (mm).
- **Informasi Lengkap:** Mencakup suhu, kelembapan, dan kecepatan angin per jam.

### 6. Dukungan Dua Bahasa (Language Switcher)
Mendukung perpindahan bahasa secara instan antara:
- **English (EN)**
- **Bahasa Indonesia (ID)**

---

## Teknologi yang Digunakan
- **Struktur:** HTML5 (Semantic HTML).
- **Styling:** CSS3 & Tailwind CSS (Utility-first framework).
- **Logika:** Vanilla JavaScript (ES6+).
- **Ikon:** Google Material Symbols.
- **Peta Radar:** Embedded Windy API.

## Panduan Penggunaan
1. **Ganti Lokasi:** Klik ikon pensil/lokasi di sebelah nama kota pada kartu utama untuk memilih kota lain.
2. **Lihat Radar:** Gunakan mouse atau sentuhan pada area radar untuk mengeksplorasi kondisi awan.
3. **Pindah Tab Ramalan:** Klik tab "Ramalan Per Jam" untuk melihat rincian cuaca tiap jam, atau "Ramalan 7 Hari" untuk tinjauan mingguan.
4. **Buka Detail Jam:** Klik pada baris jam di tab Ramalan Per Jam untuk melihat rincian seperti Indeks UV dan Curah Hujan untuk jam tersebut.
5. **Ganti Bahasa:** Klik tombol bahasa di pojok kanan atas navigasi untuk beralih antara EN dan ID.

---
*Dikembangkan oleh SkyCast Team - 2024*
