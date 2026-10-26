# Diary App 2

Aplikasi buku harian sederhana berbasis React Native + Expo.

## Identitas

- **Nama:** Samie Al Fauzan
- **NIM:** 2430511009
- **Mata Kuliah:** Mobile Programming (React Native + Expo CLI)

## Fitur yang Diselesaikan

- Total 5 entri diary, termasuk 2 entri baru dengan ID 4 dan 5.
- Gambar mood menggunakan gambar lokal dari folder `assets/moods`.
- Avatar pengguna pada header menggunakan komponen `Image` dari `assets/avatar/profile.jpg`.
- Variasi tampilan kartu berdasarkan mood, meliputi warna border, warna latar, ketebalan border, aksen kiri, dan label mood.
- Struktur folder dipisahkan menjadi data, konstanta, komponen, dan layar.

## Struktur Folder

```text
diary-app-2/
├── App.js
├── assets/
│   ├── avatar/
│   │   └── profile.jpg
│   └── moods/
│       ├── happy.jpg
│       ├── focus.jpg
│       ├── calm.jpg
│       ├── sad.jpg
│       └── excited.jpg
└── src/
    ├── components/
    │   ├── DiaryCard.js
    │   └── Header.js
    ├── constants/
    │   └── moodStyles.js
    ├── data/
    │   └── diaryEntries.js
    └── screens/
        └── DiaryListScreen.js
```

## Cara Menjalankan

1. Pastikan Node.js dan npm sudah terpasang.
2. Masuk ke folder proyek.
3. Pasang dependensi:

   ```bash
   npm install
   ```

4. Jalankan aplikasi:

   ```bash
   npx expo start -c
   ```

5. Scan QR code menggunakan Expo Go di HP atau tekan `a` untuk menjalankan emulator Android.

## Teknologi

- React Native
- Expo
- JavaScript
