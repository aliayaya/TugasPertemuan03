# Proma PB - Profil Mahasiswa

**Proma PB** (Profil Mahasiswa - Pemrograman Bergerak) adalah aplikasi Android sederhana yang dibuat untuk memenuhi Tugas Pertemuan 3 Mata Kuliah Pemrograman Bergerak. Aplikasi ini menampilkan portofolio profil mahasiswa, informasi pendidikan, keahlian, dan contoh proyek berbasis **Kotlin**, **Jetpack Compose**, serta **Material Design 3** dengan tema Dark Slate.

---

## 👤 Identitas Mahasiswa

- **Nama**: Alia Fellanitami Achyar
- **NIM**: 0102523010
- **Program Studi**: Informatika
- **Universitas**: Universitas Al Azhar Indonesia
- **Mata Kuliah**: Pemrograman Bergerak (Tugas Pertemuan 3)

---

## 🛠️ Teknologi yang Digunakan

- **Kotlin**: Bahasa pemrograman utama Android.
- **Jetpack Compose**: Framework deklaratif untuk membuat tampilan UI.
- **Material Design 3**: Komponen dan sistem desain antarmuka aplikasi.
- **Gradle & Version Catalog (`libs.versions.toml`)**: Pengelolaan versi dependency dan konfigurasi build project.

---

## ✨ Fitur Aplikasi

1. **Header Application**: Menampilkan nama aplikasi **Proma PB** dan subtitle **Profil Mahasiswa**.
2. **Profil Mahasiswa**: Menampilkan avatar lingkaran inisial **AF**, Nama Lengkap, Badge NIM, Status Mahasiswa, Program Studi, dan Universitas.
3. **Informasi Pendidikan**: Menampilkan Universitas, Program Studi, dan Semester. Dilengkapi tombol **Edit & Simpan Semester** interaktif.
4. **Keahlian & Skill**: Menampilkan daftar keahlian dalam bentuk chip yang tersusun rapi menggunakan `FlowRow`.
5. **Proyek Mahasiswa**: Menampilkan daftar card contoh proyek portofolio beserta kategori dan *tech stack*.
6. **Footer Identitas**: Menampilkan ringkasan identitas tugas dan NIM mahasiswa.
7. **Responsif & Scrollable**: Tampilan dapat di-scroll (`verticalScroll`) sehingga semua konten dapat dilihat dengan rapi.
8. **Pratinjau Android Studio**: Fitur `@Preview` untuk melihat tampilan UI secara langsung tanpa menjalankan emulator.

---

## 📁 Struktur Folder Project

Berikut adalah gambaran lokasi file utama di dalam project:

```text
TugasPertemuan03_AliaFellanitamiAchyar/
├── app/
│   ├── src/main/java/com/example/tugaspertemuan03_aliafellanitamiachyar/
│   │   ├── MainActivity.kt        # File utama berisi Screen Proma PB & Custom Composables
│   │   └── ui/theme/              # Pengaturan tema aplikasi
│   │       ├── Color.kt           # Definisi palet warna Dark Slate & Muted Olive
│   │       ├── Theme.kt           # Konfigurasi MaterialTheme
│   │       └── Type.kt            # Hirarki tipografi teks
│   ├── src/main/res/              # Resource aplikasi (strings, colors, launcher icons, xml)
│   └── build.gradle.kts           # Konfigurasi build modul aplikasi
├── gradle/
│   └── libs.versions.toml         # Version Catalog untuk versi pustaka/dependency
├── README.md                      # Dokumentasi project
├── build.gradle.kts               # Konfigurasi build root project
└── settings.gradle.kts            # Pengaturan modul project Gradle
```

---

## 🚀 Cara Menjalankan Aplikasi

Berikut langkah-langkah untuk membuka dan menjalankan project melalui Android Studio:

### 1. Membuka Project
1. Buka aplikasi **Android Studio**.
2. Pilih menu **File > Open** (atau *Open Project* pada layar awal).
3. Arahkan dan pilih folder project `TugasPertemuan03_AliaFellanitamiAchyar`.
4. Tunggu beberapa saat hingga proses **Gradle Sync** selesai secara otomatis.

### 2. Melihat Tampilan via Preview (Tanpa Emulator)
1. Buka file `MainActivity.kt` di lokasi `app/src/main/java/.../MainActivity.kt`.
2. Klik tombol **Split** atau **Design** di pojok kanan atas editor Android Studio.
3. Tampilan pratinjau aplikasi akan muncul melalui fungsi `@Preview`.

### 3. Menjalankan di Emulator / Perangkat HP
1. Pastikan **Android Virtual Device (Emulator)** sudah terpasang atau hubungkan HP Android via kabel data/WiFi.
2. Pastikan modul yang dipilih adalah **`app`**.
3. Klik tombol **Run ▶** (atau tekan `Shift + F10` / `Control + R` pada Mac).
4. Aplikasi **Proma PB** akan otomatis terpasang dan berjalan di emulator/HP.
