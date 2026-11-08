# Rebut Wilayah

Game kelas multiplayer: murid main di HP masing-masing, merebut blok untuk timnya, dan mengisi bensin dengan menjawab soal dari guru.

- Halaman murid: `/` (bisa langsung `/?r=KODE`)
- Halaman guru: `/#guru`
- Uji lokal tanpa Firebase (beberapa tab satu browser): tambahkan `?mock`

## Isi

- `index.html` – seluruh game (guru + murid) dalam satu file
- `qris.png` – gambar QRIS untuk pop-up traktir kopi (tambahkan sendiri)
- `netlify.toml` – Netlify langsung menyajikan folder ini, tanpa build

## Data

Firebase Realtime Database, satu ruang per kode di `rooms/{kode}`: `meta`, `q`, `players`, `pos`, `tiles`, `stats`, `ans`.
