# RVA Web Dev

Website portofolio satu halaman. Satu file `index.html`, tanpa framework dan tanpa build.

## Jalankan di komputer

Buka `index.html` di browser. Selesai.

## Ubah isi (semua ada di `index.html`)

| Mau ubah | Cari tulisan ini |
|---|---|
| Semua teks (ID dan EN) | `const T=` |
| Tambah proyek portofolio | `const P=[` |
| Daftar tools dan deskripsinya | `const S=[` dan `const DS=` |
| Paket harga, layanan tambahan, ketentuan | `const PL=` dan `const TR=` |
| Nomor WhatsApp, email, Instagram | cari `6287729807011`, `webdevrva@gmail.com`, `rvawebdev` |

### Tambah proyek

Tambah satu baris di `const P=[`:

```js
{t:"Nama Web",u:"https://link-web.vercel.app",d:["Teks Indonesia","English text"],g:["Tag1","Tag2"],f:1},
```

- `u` link web (wajib `https://`)
- `d` deskripsi: Indonesia dulu, Inggris kedua
- `g` tag kecil di kartu
- `f:1` ikut tampil di home (maksimal 3). Tanpa `f:1`, hanya tampil di halaman "Lihat semua portofolio"
- `m:"card"` kalau preview kosong (web itu menolak ditampilkan di iframe)

Jangan lupa koma di akhir baris, dan jangan pakai tanda kutip dua `"` di dalam teks.

## Deploy ke Vercel

1. Push folder ini ke GitHub.
2. Buka vercel.com, Add New, Project, pilih repo ini.
3. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory. Klik Deploy.
4. Setiap kali kamu push perubahan, Vercel deploy ulang sendiri.

Domain sendiri: Vercel, Project, Settings, Domains.
