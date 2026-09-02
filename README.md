# 𓏲 tumblrone — Tumblr Dashboard Interactive Website

> **Harga / Price:** **Rp10.000 (10k)**  
> **Kategori:** Ready-Made Website (Not a one-time sale)  
> **Desain & Konsep:** Catamourie (`@liltz`)  
> **Order Form Online:** [`form.html`](form.html) atau via Telegram [`t.me/mirssy`](https://t.me/mirssy)

---

## ✦ Tentang Website (About tumblrone)

**tumblrone** adalah template website interaktif bertema **Tumblr Dashboard Aesthetic (Midnight Blue)** yang dibuat khusus untuk momen perayaan (mensive, anniversary, birthday, atau private love confession). 

Website ini menampilkan feed 5 postingan bergaya khas Tumblr dengan interaksi lengkap:
1. **Scene 01 — Masterpost Cover:** Postingan pembuka arsip foto dan quote estetik.
2. **Scene 02 — The List (Evidence):** Postingan daftar 4 hal favorit yang bisa dibuka satu per satu (*interactive reveal*).
3. **Scene 03 — Tumblr Poll & Portrait:** Polling interaktif persentase suara Tumblr yang langsung membuka foto potret candid tercantik saat opsi dipilih.
4. **Scene 04 — Milestone Stepper:** Garis waktu interaktif (01, 02, 03 bulan) yang bisa diklik per bulan hingga perayaan milestone hari ini.
5. **Scene 05 — Final Love Note & Confession:** Surat cinta romantis bernada *effortless Gen Z* dengan foto penutup berpelukan yang langsung tampil utuh.
6. **Tumblr Comments Drawer & Auto-Reply:** Kolom komentar interaktif di setiap postingan dengan respon balasan otomatis yang nyambung secara natural dengan apa pun yang diketik.
7. **Web Audio FX:** Efek suara lembut (*heart pop*, klik tombol, chime penerimaan) yang disintesis native tanpa file MP3 eksternal.
8. **100% Multi-Device Responsive:** Tampil rapi di iPhone (bebas auto-zoom & safe area notch), Android, Tablet, dan Desktop.

---

## ✦ Struktur File Proyek

```
TUMBLRONE/
├── index.html       # Halaman utama website tumblrone
├── style.css        # Desain & styling sistem Tumblr Midnight Blue
├── script.js        # Logika interaktif, data config, dan auto-reply engine
├── form.html        # Form pemesanan online otomatis (Rp10.000)
├── README.md        # Panduan & dokumentasi lengkap
└── assets/          # Folder 7 aset gambar & foto
    ├── avatar-keith.jpg    # Foto profil Keith (1:1)
    ├── avatar-keisha.jpg   # Foto profil Keisha (1:1)
    ├── photo-entry.jpg     # Foto Scene 01 (Cover)
    ├── photo-list.jpg      # Foto Scene 02 (Daftar Favorit)
    ├── photo-01.jpg        # Foto Scene 03 (Hasil Polling)
    ├── photo-02.jpg        # Foto Scene 04 (Milestone 3 Bulan)
    └── photo-final.jpg     # Foto Scene 05 (Foto Penutup)
```

---

## ✦ Panduan Kustomisasi (Cara Edit Data & Foto)

### 1. Mengubah Teks, Nama, dan Tanggal
Buka file **`script.js`**, lalu sesuaikan data pada objek `siteData` di bagian paling atas:
* `senderName`: Nama display Keith (`Keith.`)
* `senderHandle`: Username Keith (`@keonho`)
* `recipientName`: Nama display Keisha (`keisha!`)
* `recipientHandle`: Username Keisha (`@kya`)
* `dateFormatted`: Tanggal perayaan (`September 1, 2026`)
* `entry`, `listScene`, `quizScene`, `counterScene`, `finalScene`: Sesuaikan judul, quote, caption, dan surat cinta sesuai keinginan.

### 2. Mengubah Foto
Cukup siapkan **7 foto** Anda sendiri, beri nama sesuai daftar file di bawah ini, lalu timpa ke dalam folder **`assets/`**:
1. `avatar-keith.jpg` *(Foto profil pembuat)*
2. `avatar-keisha.jpg` *(Foto profil penerima)*
3. `photo-entry.jpg` *(Foto cover pembuka)*
4. `photo-list.jpg` *(Foto candid / makanan)*
5. `photo-01.jpg` *(Foto solo candid tercantik)*
6. `photo-02.jpg` *(Foto suasana malam / hangat)*
7. `photo-final.jpg` *(Foto penutup / minta peluk)*

---

## ✦ Cara Deploy / Publikasi Website ke Netlify (Gratis)

1. Buka [app.netlify.com](https://app.netlify.com) dan login/daftar.
2. Drag & Drop folder **`TUMBLRONE`** ke area *Deploy manually*.
3. Masuk ke **Site configuration** → **Change site name** untuk mengubah subdomain menjadi link custom Anda (contoh: `keonho-kya.netlify.app`).
4. Website siap dibagikan ke pasangan Anda!

---

## ✦ Form Pemesanan (`form.html`)

Untuk pembeli baru yang ingin memesan template **tumblrone**:
1. Buka **`form.html`** di browser.
2. Lengkapi identitas, pilihan palet warna (default / recolor +2k), teks kustom, dan pilihan link.
3. Klik tombol **Submit** → Rincian pesanan otomatis tersalin ke clipboard dan Telegram [`t.me/mirssy`](https://t.me/mirssy) akan terbuka otomatis untuk mengirim form dan 7 foto.