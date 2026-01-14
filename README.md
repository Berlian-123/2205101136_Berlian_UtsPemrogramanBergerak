 LaporBukti (Offline-First Report App)

Aplikasi pelaporan kerusakan fasilitas kampus/umum berbasis Android Native (Jetpack Compose).
Dibangun sebagai tugas  **Mata Kuliah Pemrograman Mobile**.


 Fitur Unggulan
Aplikasi ini menerapkan arsitektur **Offline-First** menggunakan Room Database, sehingga tetap berfungsi penuh tanpa internet.

 Role: Warga (Pelapor)
- **Buat Laporan:** Input judul, kategori, deskripsi.
- **Bukti Foto:** Mengambil foto dari galeri (Photo Picker) dengan permission aman.
- **Lokasi Akurat:** Mengambil titik koordinat GPS (High Accuracy) secara real-time.
- **Riwayat:** Melihat status laporan sendiri (Draft, Terkirim, Selesai).

 Role: Admin (Petugas)
- **Dashboard:** Melihat ringkasan jumlah laporan masuk.
- **Pencarian:** Filter laporan berdasarkan judul/kategori secara real-time.
- **Peta Interaktif:** Membuka lokasi kejadian langsung di Google Maps.
- **Statistik:** Visualisasi data laporan (Pie Chart) menggunakan Canvas.
- **Manajemen Status:** Mengubah status laporan (Terima -> Selesai).


  Teknologi yang Digunakan
- **Bahasa:** Kotlin
- **UI Toolkit:** Jetpack Compose (Material Design 3)
- **Database:** Room (SQLite Local Database)
- **Async:** Coroutines & Flow
- **Image Loading:** Coil
- **Maps:** Google Maps Intent & Location Services (FusedLocationProvider)
- **Architecture:** MVVM (Model-View-ViewModel) + Repository Pattern


 Screenshot
<img width="1913" height="976" alt="image" src="https://github.com/user-attachments/assets/24f27d5f-bcd7-474b-96d6-cce959fc11ca" />




 Cara Menjalankan
1. Clone repository ini.
2. Buka di **Android Studio Ladybug/Meerkat**.
3. Sync Gradle.
4. Run di Emulator/Device Fisik (Min SDK 24).
5. **Login:**
   - Pilih "Warga" untuk mode pelapor.
   - Pilih "Admin" untuk mode petugas.

---

Developed by **[Nama Kamu]** - [NIM Kamu]
