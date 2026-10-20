# Proma PB - Profil Mahasiswa

**Proma PB** (Profil Mahasiswa - Pemrograman Bergerak) adalah aplikasi portofolio mahasiswa berbasis Android yang dibangun menggunakan **Kotlin**, **Jetpack Compose**, dan **Material Design 3**. Aplikasi ini dirancang untuk memenuhi Tugas Pertemuan 3 Mata Kuliah Pemrograman Bergerak dengan tampilan Dark Slate Theme yang sederhana, rapi, dan responsif.

---

## 👤 Identitas Mahasiswa

* **Nama**: Alia Fellanitami Achyar
* **NIM**: 0102523010
* **Program Studi**: Informatika
* **Universitas**: Universitas Al Azhar Indonesia
* **Mata Kuliah**: Pemrograman Bergerak (Tugas Pertemuan 3)

---

## 🛠️ Teknologi yang Digunakan

* **Bahasa Pemrograman**: Kotlin
* **UI Framework**: Jetpack Compose (Declarative UI)
* **Design System**: Material Design 3 (Material 3)
* **Target SDK**: Android SDK 37 (Min SDK 24)
* **Build System**: Gradle dengan Version Catalog (`libs.versions.toml`)

---

## ✨ Fitur Aplikasi

1. **Header Application**: Menampilkan logo ikon, nama aplikasi **Proma PB**, dan subtitle **Profil Mahasiswa**.
2. **Kartu Profil Mahasiswa**: Menampilkan avatar lingkaran dengan inisial **AF**, Nama Lengkap, Badge NIM, Program Studi, dan Universitas.
3. **Kartu Informasi Pendidikan (Interaktif)**:
   * Menampilkan informasi Universitas, Program Studi, dan Semester.
   * Dilengkapi fitur **Edit Semester** interaktif (tombol Edit & Simpan menggunakan Compose State).
4. **Bagian Keahlian & Skill**: Menampilkan daftar skill (*Kotlin*, *Jetpack Compose*, *Android SDK*, dll.) dalam bentuk chip yang tersusun rapi menggunakan `FlowRow`.
5. **Bagian Proyek Mahasiswa**: Menampilkan kartu proyek portofolio (*Proma Mobile App*, *Sistem Informasi Akademik*, dan *Campus Event Tracker*) lengkap dengan kategori dan *tech stack*.
6. **Footer Identitas**: Menampilkan ringkasan identitas tugas di bagian bawah layar.
7. **Responsif & Scrollable**: Konten dapat di-scroll (`verticalScroll`) dan memiliki tata letak yang rapi tanpa teks bertabrakan.
8. **Pratinjau Android Studio**: Dilengkapi fungsi `@Preview` untuk tampilan lansung di Android Studio.

---

## 📁 Struktur Folder Utama

```text
TugasPertemuan03_AliaFellanitamiAchyar/
├── app/
│   ├── src/main/java/com/example/tugaspertemuan03_aliafellanitamiachyar/
│   │   ├── MainActivity.kt        # Entry point aplikasi & Custom Composables Proma PB
│   │   └── ui/theme/              # Konfigurasi Tema (Color.kt, Theme.kt, Type.kt)
│   ├── src/main/res/              # Resource aplikasi (strings, colors, mipmap, xml)
│   └── build.gradle.kts           # Module build configuration
├── gradle/
│   └── libs.versions.toml         # Version Catalog dependency management
├── README.md                      # Dokumentasi project
├── build.gradle.kts               # Root build configuration
└── settings.gradle.kts            # Gradle settings configuration
```

---

## 🚀 Cara Membuka dan Menjalankan Project

1. **Buka Project di Android Studio**:
   * Jalankan **Android Studio**.
   * Pilih menu **File > Open**, lalu arahkan ke folder project `TugasPertemuan03_AliaFellanitamiAchyar`.
   * Tunggu hingga proses **Gradle Sync** selesai.

2. **Melihat Pratinjau (Preview UI)**:
   * Buka file `app/src/main/java/.../MainActivity.kt`.
   * Klik tombol **Split** atau **Design** di pojok kanan atas editor untuk melihat `@Preview` secara langsung tanpa emulator.

3. **Menjalankan di Emulator**:
   * Pastikan emulator Android (AVD) sudah terpasang dan aktif.
   * Tekan tombol **Run** (Ikon Segitiga Hijau ▶ / `Shift + F10`) di toolbar atas.
