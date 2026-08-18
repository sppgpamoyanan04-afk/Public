SPPG PAMOYANAN 04 — PWA

Isi:
- index.html       = aplikasi utama
- manifest.json    = identitas PWA
- sw.js            = service worker/offline cache
- icons/           = ikon aplikasi

CARA MENJADIKAN APLIKASI YANG BISA DI-INSTAL:
1. Upload seluruh isi folder ini ke hosting yang mendukung HTTPS.
2. Pastikan index.html dapat dibuka melalui alamat HTTPS.
3. Buka alamat tersebut di Chrome Android.
4. Pilih "Instal aplikasi" / "Tambahkan ke layar utama".
5. Jika tombol instal di dalam web muncul, tombol tersebut juga dapat digunakan.

CATATAN:
- PWA tidak dapat dipasang dengan benar dari file:///... saja di sebagian besar browser.
- Untuk instal penuh, gunakan HTTPS.
- Data aplikasi saat ini masih memakai penyimpanan browser perangkat (localStorage), sesuai versi web sebelumnya.
