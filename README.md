# Prodeo SIAPSurat Updates

Repository publik ini merupakan kanal pembaruan resmi **Prodeo SIAPSurat Desktop**.

## Kanal stabil

Aplikasi membaca manifest berikut:

`https://raw.githubusercontent.com/xianjieng-learn/prodeo-siapsurat-updates/main/channel/stable.json`

Manifest menyediakan nomor versi terbaru, URL paket ZIP, checksum SHA-256, ukuran paket, batas versi minimum, dan catatan perubahan.

## Struktur

- `channel/stable.json` — manifest yang dibaca aplikasi.
- `releases/<versi>/` — paket pembaruan dan checksum.
- `schemas/update-manifest.schema.json` — spesifikasi manifest.
- `.github/workflows/validate-release.yml` — validasi otomatis manifest, checksum, dan isi ZIP.

## Keamanan

Aplikasi hanya memasang paket setelah checksum SHA-256 cocok. Repository ini tidak boleh berisi kredensial SIAPSurat/APS, cookie, token, konfigurasi jaringan kantor, atau dokumen perkara.

## Rilis terbaru

**3.0.1** — GitHub menjadi kanal pembaruan online default pada installer Prodeo berikutnya.
