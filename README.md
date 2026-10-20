# Proma PB - Profil Mahasiswa

Proma(Profil Mahasiswa) PB adalah aplikasi Android sederhana yang dibuat untuk memenuhi tugas mata kuliah Pemrograman Bergerak, Pertemuan 3. Aplikasi ini menampilkan informasi mahasiswa, pendidikan, keahlian, dan beberapa contoh proyek. Aplikasi dibuat menggunakan Kotlin dan Jetpack Compose dengan tampilan tema gelap.

## Identitas Mahasiswa

- **Nama:** Alia Fellanitami Achyar
- **NIM:** 0102523010
- **Program Studi:** Informatika
- **Universitas:** Universitas Al Azhar Indonesia
- **Mata Kuliah:** Pemrograman Bergerak

## Teknologi yang Digunakan

Beberapa teknologi yang digunakan dalam project ini adalah:

- **Kotlin** untuk bahasa pemrograman.
- **Jetpack Compose** untuk membuat tampilan aplikasi.
- **Material 3** untuk komponen dan desain antarmuka.
- **Gradle** untuk mengatur proses build dan dependency project.

## Fitur Aplikasi

Aplikasi Proma PB memiliki beberapa bagian, yaitu:

1. **Header**, berisi nama aplikasi dan keterangan singkat.
2. **Profil mahasiswa**, menampilkan nama, NIM, program studi, universitas, dan inisial nama.
3. **Informasi pendidikan**, berisi informasi universitas, program studi, dan semester. Semester juga dapat diedit melalui tombol yang tersedia.
4. **Keahlian**, menampilkan daftar skill dalam bentuk chip.
5. **Daftar proyek**, menampilkan beberapa contoh proyek beserta kategori dan teknologi yang digunakan.
6. **Footer**, berisi informasi singkat terkait identitas mahasiswa.
7. **Tampilan yang bisa di-scroll**, sehingga seluruh informasi dapat dilihat meskipun tidak muat dalam satu layar.
8. **Preview**, untuk melihat tampilan aplikasi melalui fitur Preview di Android Studio.

## Struktur Folder

Berikut gambaran singkat struktur folder project:

```text
TugasPertemuan03_AliaFellanitamiAchyar/
├── app/
│   ├── src/main/java/
│   │   ├── MainActivity.kt
│   │   └── ui/theme/
│   ├── src/main/res/
│   └── build.gradle.kts
├── gradle/
│   └── libs.versions.toml
├── README.md
├── build.gradle.kts
└── settings.gradle.kts
```

Keterangan:
- `MainActivity.kt` berisi kode utama aplikasi dan komponen tampilannya.
- `ui/theme/` berisi pengaturan tema aplikasi.
- `res/` berisi resource yang digunakan oleh aplikasi.
- `libs.versions.toml` digunakan untuk mengatur versi dependency.
- `build.gradle.kts` dan `settings.gradle.kts` digunakan untuk konfigurasi project Gradle.

## Cara Menjalankan Aplikasi

1. Buka Android Studio.
2. Pilih **File > Open**, lalu pilih folder project.
3. Tunggu sampai proses Gradle Sync selesai.
4. Jalankan emulator Android atau hubungkan perangkat yang tersedia.
5. Pilih konfigurasi aplikasi, kemudian klik tombol **Run** untuk menjalankan aplikasi.

Untuk melihat tampilan tanpa menjalankan aplikasi di emulator, buka `MainActivity.kt` dan gunakan fitur Preview jika tersedia.

