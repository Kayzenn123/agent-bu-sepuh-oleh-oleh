# BUILD NOTE — Demo Pusat Oleh-Oleh Bu Sepuh

Dibuat: 2026-10-22 (job j0900-client-prospecting)

## File
- `index.html` — satu file, self-contained. Tanpa font eksternal (system font stack),
  tanpa gambar eksternal (ilustrasi produk = emoji + gradasi CSS), tanpa request
  jaringan kecuali link tel: dan Google Maps.

## Data (dari riset publik, tidak dikarang)
| Data | Sumber publik |
|---|---|
| Nama: Pusat Oleh-Oleh Bu Sepuh — toko oleh-oleh khas Kuningan | klaim "terbesar & terlengkap" dari review publik |
| Alamat: Jl. Raya Bojong No. 144–146, Cilimus, Kab. Kuningan, Jawa Barat | Google Maps |
| Telp (0232) 614228 | listing publik (fixed-line) |
| Jam: setiap hari 07.00–21.00 | listing publik |
| Rating 4,5 dari 52 ulasan | Google Maps (diberi label sumber) |
| Tape ember Rp80.000–95.000 (Sari Wangi / Sari Asri / Rasa Madu) | harga publik; tiap varian ditulis terpisah, tidak diagregasi ngasal |
| Peuyeum, opak ketan bakar, keripik, kue satu, tahu susu, dodol, bumbu rujak | daftar produk publik; harga = "Tanya via telepon" ([ISI MANUAL]) |

## Kepatuhan aturan
- R7: tidak ada nama/menu/harga/jam/alamat yang dikarang. Harga varian lain
  diberi placeholder jujur "Tanya via telepon" + catatan kaki sumber.
- R8: TIDAK ada testimoni/ulasan palsu. Satu-satunya bukti sosial = rating
  Google Maps riil dengan label sumber. Footer jujur: ini contoh website dari Zenn.
- Nomor telepon fixed-line → hanya CTA `tel:`, TIDAK ada tombol WA.

## Keputusan desain (mobile-first)
- Header sticky + tombol Telepon; hero dengan CTA telepon di atas fold;
  rating Google di hero; katalog grid 2 kolom (3 di desktop); info bar
  (jam/rating/lokasi); tentang singkat 3 poin; info praktis (alamat/jam/telp)
  + tombol "Lihat di Google Maps"; sticky CTA telepon bawah (mobile saja,
  disembunyikan di desktop ≥640px).
- Palet: kuning madu #F5A623, coklat tanah #4A2E17, putih/krem.

## Status
- Belum dideploy (atas instruksi: jangan deploy).
- Belum diverifikasi di browser — verifikasi visual menjadi tanggungan parent
  (agen ini tidak punya akses browser live).
- Disarankan: buka file di HP untuk cek keterbacaan di atas fold.
