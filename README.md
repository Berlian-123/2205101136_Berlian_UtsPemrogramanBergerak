 LaporBukti (Offline-First Report App)

Aplikasi pelaporan kerusakan fasilitas kampus/umum berbasis Android Native (Jetpack Compose).
Dibuat sebagai tugas  **Mata Kuliah Pemrograman Bergerak**.


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
<img width="1905" height="967" alt="image" src="https://github.com/user-attachments/assets/65f1bee9-afe9-4bc0-b642-07f7b58df41d" />
<img width="1919" height="971" alt="image" src="https://github.com/user-attachments/assets/378784f5-ed43-40c2-a6f8-908ec36c85f2" />
<img width="1915" height="976" alt="image" src="https://github.com/user-attachments/assets/5068b98c-2ac6-4ae9-b7af-d1f94af4ca85" />
<img width="1912" height="967" alt="image" src="https://github.com/user-attachments/assets/2bd6babd-ee78-4f4c-8b79-7b1267af14c4" />
<img width="1914" height="966" alt="image" src="https://github.com/user-attachments/assets/192cbe3f-6643-4918-9e5b-7d2f5e4de2bd" />
<img width="1908" height="964" alt="image" src="https://github.com/user-attachments/assets/b16fc0f9-986e-40d4-aeec-d6f403ef5c78" />


 Cara Menjalankan
1. Clone repository ini.
2. Buka di **Android Studio Ladybug/Meerkat**.
3. Sync Gradle.
4. Run di Emulator/Device Fisik (Min SDK 24).
5. **Login:**
   - Pilih "Warga" untuk mode pelapor.
   - Pilih "Admin" untuk mode petugas.

---

Developed by **[Berlian Nanda Prisilia Nugroho]** - [2205101136]
