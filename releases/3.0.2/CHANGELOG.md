# Prodeo SIAPSurat Desktop 3.0.2

## Sinkronisasi SIAPSurat otomatis

- Memulai pemeriksaan ringan sekitar 5 detik setelah aplikasi dibuka.
- Memeriksa SIAPSurat setiap 5 menit pada kondisi normal.
- Mempercepat interval menjadi 2 menit ketika ada perkara yang menunggu hasil TTE.
- Memeriksa ulang daftar perkara setiap 15 menit untuk menemukan perkara baru.
- Menggunakan jeda bertahap 10, 20, lalu maksimal 30 menit ketika koneksi atau sesi gagal.
- Menggunakan kembali sesi login SIAPSurat dan hanya login ulang ketika sesi berakhir.
- Menghindari pemeriksaan bersamaan dengan upload, pekerjaan antrean, atau pemeriksaan manual.
- Menyimpan status terakhir agar notifikasi perubahan dan TTE tidak muncul berulang.

## Tampilan dan kontrol

- Menambahkan indikator status sinkronisasi pada header aplikasi.
- Menambahkan tombol **Periksa Sekarang**.
- Menampilkan waktu pemeriksaan terakhir dan jadwal pemeriksaan berikutnya.
- Menambahkan pengaturan interval normal, interval menunggu TTE, timeout, notifikasi, dan sinkronisasi saat aplikasi dibuka.

## Stabilitas

- Menyatukan pemeriksaan manual dan otomatis dalam satu mesin sinkronisasi dengan lock.
- Menambahkan timeout dan pemulihan setelah kegagalan.
- Pemeriksaan otomatis berhenti sepenuhnya ketika aplikasi ditutup.
- Tetap mendukung update ZIP secara offline.
