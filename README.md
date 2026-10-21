# Gym Tracker Multi-User

Aplikasi Gym Tracker statis yang siap dipublikasikan melalui GitHub Pages.

## Fitur

- Profil dan data terpisah untuk setiap user
- Workout tracker dan riwayat latihan
- Body progress dan pencatatan berat badan
- Kalori tracker
- Protein, karbohidrat, dan lemak untuk setiap makanan
- Makanan kustom
- Backup dan pemulihan data JSON
- Penyimpanan lokal melalui localStorage browser

## Cara mengunggah ke GitHub Pages

1. Buat repository baru di GitHub.
2. Unggah seluruh isi folder ini ke root repository. Pastikan `index.html` berada di root.
3. Buka **Settings > Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch **main** dan folder **/(root)**, lalu klik **Save**.
6. Tunggu proses deployment selesai, kemudian buka alamat GitHub Pages yang diberikan.

## Catatan penyimpanan data

Data tersimpan di `localStorage` browser, bukan di repository GitHub. Karena itu:

- Data pada browser atau perangkat berbeda tidak otomatis tersinkronisasi.
- Menghapus data situs/browser dapat menghapus data tracker.
- Gunakan fitur Backup secara berkala.
- Jangan menggunakan mode incognito untuk penyimpanan jangka panjang.
