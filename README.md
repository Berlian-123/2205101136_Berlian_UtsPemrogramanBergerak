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
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/e33e99de-f497-49a5-b6dd-93d111fd471b" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/2086bd9c-933d-4d7a-9007-4b7d8a141fa2" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/c4959216-bbda-4c32-b924-50dc57a9fb8c" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/e65c1405-6941-4c51-bc19-f6a1834aeb08" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/ea65b44f-9ff3-43f2-89d1-c4b64539b204" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/edca2464-8cdf-4a8b-81c8-9a9ed3883845" />
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/75624684-ae79-4554-9ab7-0d4e933e1f96" />


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
