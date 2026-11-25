# Untitled Boxing Game

Game boxing 3D berbasis HTML, CSS, JavaScript, dan Three.js.

## Cara menjalankan di komputer

1. Ekstrak atau buka folder project ini.
2. Jalankan dengan Live Server di VS Code, atau gunakan server lokal lain.
3. Buka alamat lokal yang diberikan oleh server.

> Game memakai Three.js dari CDN jsDelivr dan Google Fonts, jadi koneksi internet diperlukan saat membuka game.

## Cara upload ke GitHub

1. Login ke [GitHub](https://github.com/).
2. Klik **New repository**.
3. Beri nama repository, misalnya `untitled-boxing-game`.
4. Pilih **Public**, lalu buat repository.
5. Klik **Add file → Upload files**.
6. Upload `index.html` dan `README.md` dari folder ini.
7. Klik **Commit changes**.

## Cara mengaktifkan GitHub Pages

1. Buka repository → **Settings** → **Pages**.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`.
4. Klik **Save**.
5. Tunggu proses deployment selesai. Link game akan muncul di halaman Pages repository.

## Kontrol permainan

- **W / A / S / D**: bergerak
- **J** atau klik kiri: jab / cross
- **K** atau klik kanan: pukulan berat
- **F**: guard
- **Space**: slip / menghindar
- **E**: feint
- **Q / R**: finisher

## Catatan

- Progress permainan disimpan menggunakan `localStorage` pada browser/perangkat yang digunakan.
- Repository ini berisi versi web statis; tidak membutuhkan Node.js, backend, atau proses build.